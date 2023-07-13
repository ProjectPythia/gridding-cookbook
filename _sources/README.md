<img src="thumbnail.png" alt="thumbnail" width="300"/>

# (re)Gridding with xarray Cookbook

[![nightly-build](https://github.com/ProjectPythia/gridding-cookbook/actions/workflows/nightly-build.yaml/badge.svg)](https://github.com/ProjectPythia/gridding-cookbook/actions/workflows/nightly-build.yaml)
[![Binder](https://binder.projectpythia.org/badge_logo.svg)](https://binder.projectpythia.org/v2/gh/ProjectPythia/gridding-cookbook/main?labpath=notebooks)
[![DOI](https://zenodo.org/badge/540167581.svg)](https://zenodo.org/badge/latestdoi/540167581)

This small cookbook will introduce three python packages that grids and re-grids data, that can interface with the xarray ecosystem. This is a common workflow, as modeling (climate, ML, etc.) outputs might not be all on the same scale or same grid. 

## Motivation

Quick repo to check out a few different gridding packages within short notebooks.

Packages:

[Verde](https://www.fatiando.org/verde/latest/)

[xESMF](https://xesmf.readthedocs.io/en/latest/)

[pyresample](https://pyresample.readthedocs.io/en/latest/)

Pangeo thread covering an (no package) alternative to xESMF: https://discourse.pangeo.io/t/conservative-region-aggregation-with-xarray-geopandas-and-sparse/2715


[Gio](https://github.com/agilescientific/gio) is a neat package for importing some subsurface formats into xarray datasets. This will not be covered in this cookbook, as it is a file converter than a (re)gridder. 

## Authors

[Thomas Martin](https://github.com/ThomasMGeo)

### Contributors

<a href="https://github.com/ProjectPythia/gridding-cookbook/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=ProjectPythia/gridding-cookbook" />
</a>

## Structure
There are three notebooks, each one stands on there own, but reccomend doing them in the order below:

1. xESMF
2. Verde
3. pyresample
