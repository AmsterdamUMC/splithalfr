Below is an example SMP of the R-package `splithalfr`

# Purpose
Estimates split-half reliabilities for scoring algorithms of cognitive tasks and questionnaires. *Add a brief description of what your software does*


# License
The splithalfr package is made available under the [GNU Lesser Public License v3.0](https://github.com/tpronk/splithalfr/blob/main/LICENSE). *Add a software license; we'll provide some more info on this later.*


# User guide

## System Requirements
The splithalfr was developed on a Windows 10, but I haven't heard any complaints about issues with other operating systems. *What operating system or platforms does the software run on? Do any applications or libraries be installed beforehand?*

## Installing the software
*It can be useful to offer multiple ways to obtain your software. Below we recommend some, based on the type of software:*
* The latest development version is available via this repo at [https://github.com/tpronk/splithalfr](https://github.com/tpronk/splithalfr). Beware: this version may contain errors and can change at any time. *This is where the version of your software lives as it is being developed, but there are no guarantees that it runs well or is easy to install, nor that this repo will stay available in the long-term.*
* Stable software releases are archived at Zenodo under the DOI [10.5281/zenodo.8346856](https://doi.org/10.5281/zenodo.8346856) *Zenodo is a service for long-term archiving of your software and providing it with an enduring DOI. To setup archiving and DOI, connect Zenodo to your GitHub repo and make a software release in GitHub. Use [SemVer](https://semver.org/) to number your releases and consider keeping a [ChangeLog](https://keepachangelog.com/en/1.0.0/) for your release notes.*
* The latest stable release is on CRAN at [https://cran.r-project.org/package=splithalfr](https://cran.r-project.org/package=splithalfr). Install it by running `install.packages("splithalfr")` *Package managers, such as pip/CRAN/npm, offer an easy way to install a tool. Add the URL of your package entry in the online catalogue of the package manager and a brief installation instruction* 
* *If you've published a paper analizing a specific dataset with a specific software version, consider archiving the software at the same place you archive the data. To link the data with a software version, add a hyperlink to the corresponding GitHub commit ([https://github.com/tpronk/splithalfr/tree/643f740a021d010b7eb2118858305e36000c5f9a](https://github.com/tpronk/splithalfr/tree/643f740a021d010b7eb2118858305e36000c5f9a)) or the DOI of a software release ([splithalfr v2.2.2](https://github.com/tpronk/splithalfr/releases/tag/v2.2.2)).

## Running the software
We've got six vignettes to help you get started. You can open a vignette bij running the corresponding code snippet in the R console.

* `vignette("rapi_sum")` Sum-score for data of the 23-item version of the Rutgers Alcohol Problem Index ([White & Labouvie, 1989](https://doi.org/10.15288/jsa.1989.50.30))
* `vignette("vpt_diff_of_means")` Difference of mean RTs for correct responses, after removing RTs below 200 ms and above 520 ms, on Visual Probe Task data ([Mogg & Bradley, 1999](https://doi.org/10.1080/026999399379050))
* *(four more vignettes)*

The splithalfr supports a variety of methods for splitting your data. We review and assess each  method in the compendium paper ([Pronk et al., 2021](https://doi.org/10.3758/s13423-021-01948-3)). This vignette illustrates how to apply each splitting method via the splithalfr: `vignette("splitting_methods")`

*How do you use it? Brief guides and tutorials can help new users getting started. Consider adding "further reading" on technical/methodological topics.*

# Developer guide
Be welcome to modify the source code! If you do, keep the following in mind:
* Please follow the [Google R Style Guide](https://google.github.io/styleguide/Rguide.html).
* Please add some automated unit tests of your code using [testthat](https://testthat.r-lib.org/). Add them to `tests/testthat`
* If you've got manual tests of your code, add them to `tests/`

*If you expect other developers, add some information to help them get stared: How do you set up the development environment? What kind of of coding conventions do you use? Are their (automated) tests?*


# Citing the splithalfr
*Add (1) a textual style citation, but also (2) a [CITATION.cff](https://citation-file-format.github.io/) file (which shows up as a "cite this" button in GitHub) and (3) any citation standard popular in your programming language, such as [citation(...)](https://rdocumentation.org/packages/utils/versions/3.6.2/topics/citation) for R. The example splithalfr software comes with a paper, so that one is mentioned too.*

Please cite the compendium paper ([Pronk et al., 2022](https://doi.org/10.3758/s13423-021-01948-3)) and the software. To cite the software, see the [CITATION.cff](https://github.com/tpronk/splithalfr/blob/main/CITATION.cff) file, type `citation("splithalfr")` in R, or use the reference below.

Pronk, T. (2023). *splithalfr: Estimates split-half reliabilities for scoring algorithms of cognitive tasks and questionnaires* (Version 2.2.2) [Computer software]. https://doi.org/10.5281/zenodo.7777894


# Getting help
For questions or comments, please make a post in the [splithalfr forum](https://github.com/tpronk/splithalfr/discussions). If you found a bug, please tell me in the [splithafr issues](https://github.com/tpronk/splithalfr/issues). I am maintaining this package in my spare time, so I'll try to help you out on a best-effort basis. *Tell users how to get help and what kind of service they can expect.*

