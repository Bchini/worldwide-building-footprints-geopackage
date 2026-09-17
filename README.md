# Worldwide Building Footprints (GeoPackage)

![License: ODbL](https://img.shields.io/badge/license-ODbL--1.0-blue)
![Format](https://img.shields.io/badge/format-GeoPackage-green)
![Coverage](https://img.shields.io/badge/coverage-198%20countries-orange)
[![Buy Me A Coffee](https://img.shields.io/badge/Buy%20Me%20A%20Coffee-ffdd00?style=flat&logo=buy-me-a-coffee&logoColor=black)](https://buymeacoffee.com/bchini)

One [GeoPackage](https://www.geopackage.org/) per country or territory —
ready to open in **QGIS**, **ArcGIS**, or any GDAL/OGR-based tool. No need to
download or process a multi-terabyte global dataset just to work with a
single country.

## Quick start

1. Open the [Releases](../../releases) page and find your country's release,
   tagged by its [ISO 3166-1 alpha-3](https://en.wikipedia.org/wiki/ISO_3166-1_alpha-3)
   code (e.g. `FRA` for France, `BRA` for Brazil).
2. Download all of its `.rar` assets (`<ISO3>.part01.rar`, `.part02.rar`, ...
   or a single `<ISO3>.rar` for smaller countries).
3. Extract with WinRAR or 7-Zip, keeping every volume in the same folder ->
   produces `<ISO3>.gpkg`.
4. Open the `.gpkg` directly in QGIS / ArcGIS / GDAL.

## Why this exists

Global building-footprint datasets are usually distributed as one massive
file (or a handful of continent-scale files), which is impractical if you
only need one country: you either download everything or wrangle a
multi-hundred-GB source yourself just to extract a subset. This repository
splits that data by country so you can grab exactly what you need, in a
format that opens directly in standard GIS software.

## Coverage & methodology

- 198 countries and territories.
- For most countries: a single, high-quality building-footprint source per
  country.
- For African countries: cross-checked against an independent reference
  dataset. Whichever source was more complete and geometrically valid was
  kept; where neither clearly dominated, the two were merged with automatic
  spatial de-duplication (overlapping polygons collapsed, invalid/null
  geometries removed).

<!-- STATS_START -->
## Global statistics

- **Total building footprints published**: 2,719,625,406
- **Total data size published**: 226.4 Go

<!-- STATS_END -->

## License & attribution

See [ATTRIBUTION.md](ATTRIBUTION.md). Data is distributed under the
[Open Data Commons Open Database License (ODbL) v1.0](https://opendatacommons.org/licenses/odbl/1-0/) —
share-alike: any redistribution must preserve attribution and remain
ODbL-compatible.

## Support this project

If this saved you time, consider [buying me a coffee](https://buymeacoffee.com/bchini) ☕
or sponsoring via the button above.
