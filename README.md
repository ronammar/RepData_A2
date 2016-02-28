## *This is my solution for the Coursera Reproducible Research project #2*

If you want the tables to render nicely, use `printr`:

```r
install.packages(
  'printr',
  type = 'source',
  repos = c('http://yihui.name/xran', 'http://cran.rstudio.com')
)
```

Then, to render this analysis into html, do the following:

```r
setwd("<DIRECTORY TO WHICH THIS REPO HAS BEEN CLONED>")
library(rmarkdown)
rmarkdown::render("analysis.Rmd")
```
