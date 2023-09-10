# Sortes: Statistical Analysis Software

**Sortes** is a statistical analysis package built with clarity, instructiveness, and analysis precision in mind. The main goal of Sortes is to bring the non-statistical analysis work to the forefront. Power analysis, SESOI definition, model assumption checking - all things that most scientists know they *should* do, but don't necessarily *do*.

## Framework

Sortes is built as a Shiny application, wrapped as an executable for Windows operating systems. The GitHub repository contains the necessary source code to build and run the application, but through a shell script. For the executable, please see (link to come).

## Installing from GitHub

Install the currently published version of Sortes from GitHub in `r` with:

``` r
# install.packages("devtools")
devtools::install_github("osaal/sortes")
```

Development of Sortes is done using separate branches for each version. Once the version is completed and checked, it is merged into the `master` branch, compiled locally, and published as an executable.

Install a developmental branch of Sortes from GitHub in `r` with:

``` r
# install.packages("devtools")
devtools::install_github("osaal/sortes@branch_name")
```

## Licensing

Sortes is published using the MIT license. Please read the license file in `docs/LICENSE.md` for more information.

## Contact

If you encounter a problem with Sortes or have suggestions for changes or additions, the easiest way to contact me is to open an Issue on GitHub. If you're uncertain whether the topic is big enough for an Issue, bring it up in the Discussions section for me and others to chime in on!
