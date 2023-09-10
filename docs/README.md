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

Development of Sortes is done using the GitFlow workflow. The `master` branch contains the currently stable, published version. The branch `develop` contains an unstable development version, which would at the time be tested for release. Features are developed on separate branches and merged into `develop` when completed. Hotfixes are developed on separate branches and merged into `main` for immediate release.

Install the developmental branch of Sortes from GitHub in `r` with:

``` r
# install.packages("devtools")
devtools::install_github("osaal/sortes@develop")
```

## Licensing

Sortes is published using the MIT license. Please read the license file in `docs/LICENSE.md` for more information.

## Contact

If you encounter a problem with Sortes or have suggestions for changes or additions, the easiest way to contact me is to open an Issue on GitHub. If you're uncertain whether the topic is big enough for an Issue, bring it up in the Discussions section for me and others to chime in on!
