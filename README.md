# shinyMlr: Integration of the mlr package into shiny

[![Build Status](https://travis-ci.org/mlr-org/shinyMlr.svg?branch=master)](https://travis-ci.org/mlr-org/shinyMlr)
[![CRAN Status Badge](http://www.r-pkg.org/badges/version/shinyMlr)](https://CRAN.R-project.org/package=shinyMlr)
[![CRAN Downloads](http://cranlogs.r-pkg.org/badges/shinyMlr)](https://cran.rstudio.com/web/packages/shinyMlr/index.html)

With help of this package [**mlr**](https://github.com/mlr-org/mlr#-machine-learning-in-r) can be accessed via a shiny interface. 

This project has started last year and contains now **mlr**'s major functionalities:

- Data import
- Data exploration and preprocessing
- Creating regression or classification tasks
- Making use of any **mlr** learner
- Tuning of learner hyper parameters
- Training and predicting a model
- Benchmark experiments with different learners and measures
- Many visualisations

## Installation and starting shinyMlr

### Windows
We're unfortunately facing a bug which throws an error when trying to install the package on windows machines.
However, you can start shinyMlr directly via github:

```r
shiny::runGitHub('mlr-org/shinyMlr', 'YourGithubAcountName')
```

### Mac and Linux

You can simply install the package from github:

```r
devtools::install_github("mlr-org/shinyMlr/package")
```
Starting shinyMlr:

```r
runShinyMlr()
```
