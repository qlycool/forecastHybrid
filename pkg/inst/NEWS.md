# Version 0.2.0 [Unreleased]
* Add parallel processing between models TODO
* Add timeseries cross validation wtih `cvts()`
* Fix model weights when `weights = "insample.errors"` and one or more component models perfectly fit the time series TODO
* Fixed erroneous warning message when `xreg` is included in `n.args` but a `nnetar` model is not included in the model list

# Version 0.1.7 [2016-06-04]
* Build vignette with `knitr rmarkdown` engine
* Build vignette with travis

# Version 0.1.6 [2016-05-31]
* Fix broken S3 generic `accuracy()` and `hybridModel.accuracy()`
* Add vignette
* Add NEWS
* Remove "fpp" from dependencies
* Fix warning for unimplemented parameter `weights = "cv.errors"`
* Fix error with `nnetar` and `stlm` models when `2 * frequency(y) >= length(y)`
* Documentation improvements MORE TODO
* Migrate unit tests away from deprecated `not()` function from "testthat" package
* Add additional unit tests for bugfixes (accuracy fix, nnetar/stlm `2 * frequency(y) >= length(y)`, `weights = "cv.errors"`)

# Version 0.1.5 [2016-04-16]
* First CRAN release
