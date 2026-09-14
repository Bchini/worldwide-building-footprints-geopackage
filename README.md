# building-footprints-gpkg

Building footprint polygons, one GeoPackage per country, compressed as
`.rar` volumes (99 MB max each) under `countries/<ISO3>/`.

## Reassembler un pays

1. Telecharger tous les volumes `<ISO3>.part*.rar` (ou `<ISO3>.rar`) du
   dossier `countries/<ISO3>/`.
2. Extraire avec WinRAR / 7-Zip (les volumes doivent rester dans le meme
   dossier) -> produit `<ISO3>.gpkg`.

See [ATTRIBUTION.md](ATTRIBUTION.md) for data licensing.
