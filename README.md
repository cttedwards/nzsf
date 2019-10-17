
<!-- README.md is generated from README.Rmd. Please edit that file -->

# New Zealand Spatial Features <img src="man/figures/sticker.png" align="right" height=140/>

![Build Status](https://travis-ci.org/quantifish/nzsf.svg?branch=master)

New Zealand Spatial Features (`nzsf`) is a package for creating
scientific maps in New Zealand waters. The `nzsf` package relies heavily
on the R packages `ggplot2`, `dplyr`, and `sf` providing a fresh and
easy approach for complex mapping tasks. Maps can be built up in layers
in the same way as `ggplot2` so users can easily add points,
lines/arrows, polygons, coastlines, and much more.

## Installation

The `nzsf` package can be installed from within R using:

``` r
library(devtools)
install_github("quantifish/nzsf", build_vignettes = TRUE)
```

## Help

The package vignettes are a great place to see what `nzsf` can do. You
can view the package vignettes from within R using:

``` r
browseVignettes(package = "nzsf")
vignette(package = "nzsf")
```

## Species

The `nzsf` package can plot New Zealand Quota Management Area (QMA)
boundaries for many finfish and shellfish stocks
including:

| Species code | Common name            | Scientific name             | Maori name           |
| :----------: | :--------------------- | :-------------------------- | :------------------- |
|     HAK      | Hake                   | *Merluccius australis*      | Kehe, tiikati        |
|     HOK      | Hoki                   | *Macruronus novaezelandiae* | Hoki                 |
|     LIN      | Ling                   | *Genypterus blacodes*       | Hoka, hokarari, rari |
|     OEO      | Oreo                   |                             |                      |
|     ORH      | Orange roughy          | *Hoplostethus atlanticus*   |                      |
|     SWA      | Silver warehou         | *Seriolella punctata*       | Warehou hiriwa       |
|     SBW      | Southern blue whiting  | *Micromesistius australis*  |                      |
|     CRA      | Red rock lobster       | *Jasus edwardsii*           | Kōura                |
|     PHC      | Packhorse rock lobster | *Sagmariasus verreauxi*     | Kōura Papatia        |
|     COC      | Cockle                 | *Austrovenus stutchburyi*   | Tuangi               |
|     PPI      | Pipi                   | *Paphies australis*         | Pipi                 |
|     PAU      | Paua                   | *Haliotis iris*             | Pāua                 |
|     SCA      | Scallop                | *Pecten novaezealandiae*    | Tupa                 |

Other useful

If you would like additional shapefiles added just let me know in the
issues (please include a link to the shapefiles).
