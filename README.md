
# Species Distribution Models for Colombian Endemic Birds 🇨🇴 🦜 🌎 🛰️ 💻 🗺️

This repository contains a series of documented notebooks as a first approach to **Species Distribution Models** implemented in Python.

## Data Used

The data used comes from the following sources:

 * [WorldClim 2.1](https://www.worldclim.org/data/bioclim.html): Bioclimatic and elevation variables.

 * [MapBiomas Colombia](https://colombia.mapbiomas.org/segunda-coleccion-de-mapbiomas-colombia/): Data obtained through Google Earth Engine.

 * [eBird](https://ebird.org/region/CO): Bird observation data (including effort variables and sightings).

## Repository Contents

* `graficas_preprocesamiento_aves_endemicas_gh.ipynb` this notebook contains a series of graphs generated for the different stages of the environmental and observation data processing flow.

* `raster_align_for_sdm.ipynb` code to impute environmental data from rasters aligned to the bird observation locations.

* `sdm_co.ipynb` code to train a Logistic Regression model under three scenarios: without imbalance treatment, with imbalance treatment using Random Oversampling, and with imbalance treatment using the SMOTE technique.

## Contacto

If you have any questions or suggestions, feel free to open an issue or contact me via [email](juansblandon@gmail.com).
