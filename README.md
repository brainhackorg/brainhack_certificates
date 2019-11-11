# Name badges and participation certificates for Brainhack events

This repository contains the tools to create name badges and participation
certificates for Brainhack events.

A `CSV` file containing the names and affiliations of event attendees is
required to make the badges and certificates.

## Making name cards and certificates for your event

1. Create a `CSV`containing names and affiliations for your attendees. See
[`example_namelist.csv`](data/namelist/example_namelist.csv) for an example.
2. Modify [`brainhack_id_cards.tex`](latex/brainhack_id_cards.tex) and [`brainhack_certificate.tex`](
latex/brainhack_NYC_2017_certificate.tex) to reflect your event information and
the filename of your participant list.
3. [`brainhack_certificate.tex`](latex/brainhack_NYC_2017_certificate.tex) will
additionally need to modified to contain the name of the local event chair, and
a `PDF` of their signature. Note that the **current signature** in the
[`data/signature`](data/signature) folder is a **mock signature** and **does not
and cannot be accounted for anyone's signature or endorsement**.
4. Compile the cards and certificates into a `PDF` using `pdflatex`, for
example:

```bash
pdflatex examples/brainhack_NYC_2017_id_cards.tex
```
or
```bash
pdflatex examples/brainhack_NYC_2017_certificate.tex
```

You can upload the files to `Sharelatex` or `Overleaf` and compile them there
or install `LaTeX` on your local system.
