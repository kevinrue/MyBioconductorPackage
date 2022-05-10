
<!-- README.md is generated from README.Rmd. Please edit that file -->

# MyBioconductorPackage

<!-- badges: start -->

[![GitHub
issues](https://img.shields.io/github/issues/kevinrue/MyBioconductorPackage)](https://github.com/kevinrue/MyBioconductorPackage/issues)
[![GitHub
pulls](https://img.shields.io/github/issues-pr/kevinrue/MyBioconductorPackage)](https://github.com/kevinrue/MyBioconductorPackage/pulls)
<!-- badges: end -->

The goal of `MyBioconductorPackage` is to …

## Installation instructions

Get the latest stable `R` release from
[CRAN](http://cran.r-project.org/). Then install `MyBioconductorPackage`
from [Bioconductor](http://bioconductor.org/) using the following code:

``` r
if (!requireNamespace("BiocManager", quietly = TRUE)) {
    install.packages("BiocManager")
}

BiocManager::install("MyBioconductorPackage")
```

And the development version from
[GitHub](https://github.com/kevinrue/MyBioconductorPackage) with:

``` r
BiocManager::install("kevinrue/MyBioconductorPackage")
```

## Example

This is a basic example which shows you how to solve a common problem:

``` r
library("MyBioconductorPackage")
## basic example code
```

What is special about using `README.Rmd` instead of just `README.md`?
You can include R chunks like so:

``` r
summary(cars)
#>      speed           dist       
#>  Min.   : 4.0   Min.   :  2.00  
#>  1st Qu.:12.0   1st Qu.: 26.00  
#>  Median :15.0   Median : 36.00  
#>  Mean   :15.4   Mean   : 42.98  
#>  3rd Qu.:19.0   3rd Qu.: 56.00  
#>  Max.   :25.0   Max.   :120.00
```

You’ll still need to render `README.Rmd` regularly, to keep `README.md`
up-to-date.

You can also embed plots, for example:

<img src="man/figures/README-pressure-1.png" width="100%" />

In that case, don’t forget to commit and push the resulting figure
files, so they display on GitHub!

## Citation

Below is the citation output from using
`citation('MyBioconductorPackage')` in R. Please run this yourself to
check for any updates on how to cite **MyBioconductorPackage**.

``` r
print(citation('MyBioconductorPackage'), bibtex = TRUE)
#> It is recommended to use 'given' instead of 'middle'.
#> 
#> To cite package 'MyBioconductorPackage' in publications use:
#> 
#>   Kevin Christophe Rue (2022). MyBioconductorPackage: Demonstration of
#>   a Bioconductor Package. R package version 0.99.0.
#>   https://github.com/kevinrue/MyBioconductorPackage
#> 
#> A BibTeX entry for LaTeX users is
#> 
#>   @Manual{,
#>     title = {MyBioconductorPackage: Demonstration of a Bioconductor Package},
#>     author = {Kevin Christophe Rue},
#>     year = {2022},
#>     note = {R package version 0.99.0},
#>     url = {https://github.com/kevinrue/MyBioconductorPackage},
#>   }
```

Please note that the `MyBioconductorPackage` was only made possible
thanks to many other R and bioinformatics software authors, which are
cited either in the vignettes and/or the paper(s) describing this
package.

## Code of Conduct

Please note that the `MyBioconductorPackage` project is released with a
[Contributor Code of
Conduct](http://bioconductor.org/about/code-of-conduct/). By
contributing to this project, you agree to abide by its terms.

## Development tools

-   Continuous code testing is possible thanks to [GitHub
    actions](https://www.tidyverse.org/blog/2020/04/usethis-1-6-0/)
    through *[usethis](https://CRAN.R-project.org/package=usethis)*,
    *[remotes](https://CRAN.R-project.org/package=remotes)*, and
    *[rcmdcheck](https://CRAN.R-project.org/package=rcmdcheck)*
    customized to use [Bioconductor’s docker
    containers](https://www.bioconductor.org/help/docker/) and
    *[BiocCheck](https://bioconductor.org/packages/3.14/BiocCheck)*.
-   Code coverage assessment is possible thanks to
    [codecov](https://codecov.io/gh) and
    *[covr](https://CRAN.R-project.org/package=covr)*.
-   The [documentation
    website](http://kevinrue.github.io/MyBioconductorPackage) is
    automatically updated thanks to
    *[pkgdown](https://CRAN.R-project.org/package=pkgdown)*.
-   The code is styled automatically thanks to
    *[styler](https://CRAN.R-project.org/package=styler)*.
-   The documentation is formatted thanks to
    *[devtools](https://CRAN.R-project.org/package=devtools)* and
    *[roxygen2](https://CRAN.R-project.org/package=roxygen2)*.

For more details, check the `dev` directory.

This package was developed using
*[biocthis](https://bioconductor.org/packages/3.14/biocthis)*.

## Code of Conduct

Please note that the MyBioconductorPackage project is released with a
[Contributor Code of
Conduct](http://bioconductor.org/about/code-of-conduct/). By
contributing to this project, you agree to abide by its terms.
