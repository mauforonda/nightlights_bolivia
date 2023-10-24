> Monthly nightlights for bolivian cities between January 2014 and September 2023.

- City limits correspond to polygons in the [Urban Centre Database UCDB R2019A](https://ghsl.jrc.ec.europa.eu/ghs_stat_ucdb2015mt_r2019a.php) plus a 5 Km. convex hull.
- Nightlight data comes from the [VIIRS Stray Light Corrected Nighttime Day/Night Band Composites Version 1](https://developers.google.com/earth-engine/datasets/catalog/NOAA_VIIRS_DNB_MONTHLY_V1_VCMSLCFG) collection on Google Earth Engine.

You can see:

- [Monthly mean light radiance nanoWatts/sr/cm2f for every city](outputs/ciudades_mean_light.csv)
- [Monthly sum of light radiance nanoWatts/sr/cm2f for every city](outputs/ciudades_sum_light.csv)
- [The Jupyter notebook with all code and some visualizations](nightlights.ipynb) (*interactive GEE maps require a GEE account*)

The cities included are:

- El Alto; La Paz
- Caranavi
- Riberalta
- Oruro
- Cochabamba; Sacaba; Quillacollo; Colcapirhua; Tiquipaya; Vinto
- Trinidad
- Potosí
- Sucre
- Tarija
- Montero
- Santa Cruz de la Sierra

