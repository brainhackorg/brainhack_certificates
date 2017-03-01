# Name badges and participation certificates for Brainhack events.

A csv file containing the names and affiliations of event attendees is required to make the badges and certificates.

### Making name cards and certificates for your event.

1. Create a csv containing names and affiliations for your attendees. See ```example_namelist.csv``` for an example.
2. Modify ```brainhack_nyc_id_cards.tex``` and ```brainhackNYC2017_certificate.tex``` to reflect your event information and the filename of your participant list.
3. ```brainhackNYC2017_certificate.tex``` will additionally need to modified to contain the name of the local event chair, and a pdf of their signature.
4. Compile the cards and certificates into a pdf using pdflatex, for example: ```pdflatex brainhack_nyc_id_cards.tex``` or ```pdflatex brainhackNYC2017_certificate.tex```.

You can upload the files to sharelatex or overleaf and compile them there or install latex on your local system. 
