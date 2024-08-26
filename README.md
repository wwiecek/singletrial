# Code supplement for "Meta-analysis of a single trial"

Code was prepared by [Erik van Zwet](https://scholar.google.co.uk/citations?user=DaWYR90AAAAJ), then minimally cleaned up and uploaded by me (Witold).

Results are available in the PDF file in the main folder.

## Re-rendering file with all results

All of the code is contained in a single Rmarkdown file, making use of objects saved in 
`results/`. In addition to generating a PDF, it saves some stand-alone figures in `figures/`.

## Generating all results

To re-generate some results, you need to change various `eval=FALSE` flags in the Rmd to `TRUE`. 
Some of this will take considerable amount of time to re-run (each Bayesian model may take a few seconds and 
there are tens of thousands of them to fit).

A few objects are constructed in stages, so you may need to re-run several chunks in the order
that they appear in the Rmd file.
