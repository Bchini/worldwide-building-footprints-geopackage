# building-footprints-gpkg

Building footprint polygons, one GeoPackage per country, compressed as
`.rar` volumes (~1.9 GB max each) and published as a GitHub Release per
country (see the [Releases](../../releases) page, one release tagged
`<ISO3>` per country).

## Reassembler un pays

1. Ouvrir la Release taguee `<ISO3>` et telecharger tous ses assets
   (`<ISO3>.part*.rar`, ou `<ISO3>.rar` si un seul volume).
2. Extraire avec WinRAR / 7-Zip (les volumes doivent rester dans le meme
   dossier) -> produit `<ISO3>.gpkg`.

See [ATTRIBUTION.md](ATTRIBUTION.md) for data licensing.
