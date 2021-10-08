#Directions to successfully run project code

The data used in this project were simulated from an observational Zika virus study.

All packages required to run the program successfully are found at the top of the Rmd file, but do not need to installed by you separately. They will install once you execute the analysis. R packages include sas7bdat, dplyr, table1 and ggplot2.

In order to execute the analysis, open WLS and run the following code from the info550 repository:

```bash
Rscript -e "rmarkdown::render('Fogleman_INFO550_HW2.Rmd')"
```

You should expect to see an html markdown file as your output titled 'Fogleman_INFO550_HW2.html', which will contain two tables.
