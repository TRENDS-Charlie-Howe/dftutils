# dftutils package

The purpose of this package is to create a package of commonly used, simple utility functions for people within DfT to make use of in analytical code. All of the functions in this code are designed to work in any project, and are general functions that would be of use to a wide range of people.

## Installation

The package can be installed directly from Github using the remotes install_github call

```
install.packages("remotes")
remotes::install_github("department-for-transport-public/dftutils")
```

## Overview

The package contains the following functions:

* `addSuperScriptToCell`: function to present text as superscript values in Excel workbooks.
* `recent_file`: Search function to find most recently updated file in a given directory.
* `round`: Mathematical rounding function which rounds values which end in 5 up, in contrast to the default behaviour of R (round to even).
* `writeClipboard`: write a data frame to an appropriately sized clipboard in Windows.
