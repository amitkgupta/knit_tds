# Requirements

1. R
1. Python
1. Selenium for Python
1. TeX
1. Knitr for TeX

# Instructions

Just run `./factory` from the command line within this directory.  It will:  

1. Run a Python script which will use Selenium to scrape a web page for football statistics.
1. "Knit" a TeX file with embedded R that cleans the raw scraped data, produces a histogram of touchown passes for teams, and displays the teams with the least and greatest number of touchdowns.
1. Compile the resulting TeX file and opens the resulting PDF.
1. Clean up any temporary work files.

# Troublshooting

* Make sure `pdflatex` is on your `$PATH`
* If your `python` or `Rscript` interpreters are in different locations than those used in the `scrape` and `knit` scripts, modify those scripts accordingly
