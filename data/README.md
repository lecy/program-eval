# Instruction Datasets

This folder contains files to generate data used in Program Evaluation courses. 

( placeholder files for the R package: programeval )


# File Structure

### File name

time_series_data.R 

### Function and code

```r
gen_time_series <- function()...

example graphs ...

example models ...
```

# Documentation

The roxygen documentation looks something like this:

```
#' Prices of 50,000 round cut diamonds.
#'
#' A dataset containing the prices and other attributes of almost 54,000
#' diamonds.
#'
#' @format A data frame with 53940 rows and 10 variables:
#' \describe{
#'   \item{price}{price, in US dollars}
#'   \item{carat}{weight of the diamond, in carats}
#'   ...
#' }
#' @source \url{http://www.diamondse.info/}
"diamonds"
```

Which will look like [THIS](https://ggplot2.tidyverse.org/reference/diamonds.html).
  
  
---------

# Creating R Package Tutorial

http://tinyheero.github.io/jekyll/update/2015/07/26/making-your-first-R-package.html

http://r-pkgs.had.co.nz/description.html

### Documenting datasets

http://r-pkgs.had.co.nz/data.html#documenting-data


  
# Example Book Plus Package

http://rcompanion.org/documents/RHandbookProgramEvaluation.pdf

https://cran.r-project.org/web/packages/rcompanion/rcompanion.pdf

# Anatomy of an R Package

https://hilaryparker.com/2014/04/29/writing-an-r-package-from-scratch/

https://github.com/r-lib/devtools

http://r-pkgs.had.co.nz/man.html

