# Geothermal Atlas for Africa data

The raw data for the Geothermal Atlas for Africa project can be found [here on Google Drive](https://drive.google.com/drive/folders/1UD3zWj2aqo0pMv6K1_qv4l6r_h-DiFnK?usp=sharing).

The folder contains the following files:
- `.zip`: Vector data as ShapeFile data as zip archive
- `.tif`: Raster data as GeoTiff
- `.qml`: Style files for QGIS
- `.sld`: Style files for GeoServer

The metadata for each individual data layer can be found [here on Google Drive](https://docs.google.com/spreadsheets/d/1Sy01x1ol6826SWHs5T4ZbIrpI--1J2QJ/edit?usp=sharing&ouid=100635536029075275866&rtpof=true&sd=true). The columns of the metadata reflect the following: 

- `Parent group`: The main group of the layer
- `Layer group`: The subgroup the layer
- `Filename`: The filename of the raster/vector file
- `Full name`: The full name of the layer. As short as possible.
- `Description`: A short description of the layer
- `Keywords`: Comma separated keywords
- `Source`: A URL to a paper or link to organization
- `Date`: Date of creation
- `Coverage`: Area the layer covers
- `Unit`: In case of a raster, a string of the unit such as T, K, MW. Otherwise “-”.
- `Resolution`: In case of a raster, the spatial resolution as a string. Otherwise “-”.
- `Type`: Either raster or vector
