---
sidebar_position: 7
---

# Spatial climate normals

The [maps of normal values](https://www.meteoswiss.admin.ch/climate/the-climate-of-switzerland/climate-normals/norm-value-charts.html) show the long-time averages for temperature, precipitation, sunshine duration and various climate indicators in Switzerland. Several normal periods as well as their differences are illustrated. The spatial illustration is based on a 2 km grid point data set, calculated using all available measurements from ground-based measuring stations.

MeteoSwiss provides monthly and annual maps for normal periods 1961-1990 and 1991-2020.

<!--
| PERIOD_TX    | BOUND_BOX_COORD_SYS_TX | OUTPUT_COORDSYS_TX | OUTPUT_FORMAT_TX | filename                                                  |
| ------------ | ---------------------- | ------------------ | ---------------- | --------------------------------------------------------- |
| previous_day | CH1995                 | EPSG:2056          | NETCDF           | RnormM9120 Normwert Monatsniederschalg 1991-2020          |
| previous_day | CH1995                 | EPSG:2056          | NETCDF           | RnormY9120 Normwert Jahressniederschalg 1991-2020         |
| previous_day | CH1995                 | EPSG:2056          | NETCDF           | TnormM9120 Normwert Monats-Mitteltemperatur 1991-2020     |
| previous_day | CH1995                 | EPSG:2056          | NETCDF           | TnormY9120 Normwert Jahres-Mitteltemperatur 1991-2020     |
| previous_day | CH1995                 | EPSG:2056          | NETCDF           | TminnormM9120 Normwert Monats-Minimumtemperatur 1991-2020 |
| previous_day | CH1995                 | EPSG:2056          | NETCDF           | TminnormY9120 Normwert Jahres-Minimumtemperatur 1991-2020 |
| previous_day | CH1995                 | EPSG:2056          | NETCDF           | TmaxnormM9120 Normwert Monats-Maximumtemperatur 1991-2020 |
| previous_day | CH1995                 | EPSG:2056          | NETCDF           | TmaxnormM9120 Normwert Jahres-Maximumtemperatur 1991-2020 |
| previous_day | CH1995                 | EPSG:2056          | NETCDF           | SnormM9120 Normwert Monats-Sonnenscheindauer 1991-2020    |
| previous_day | CH1995                 | EPSG:2056          | NETCDF           | SnormY9120 Normwert Monats-Sonnenscheindauer 1991-2020    |
-->

## Data download

You can access the available Open Data via [opendata.swiss](https://opendata.swiss/en/dataset?q=klimanormwerte&sort=score%20desc%2C%20metadata_modified%20desc&organization=bundesamt-fur-meteorologie-und-klimatologie-meteoschweiz&res_format=SERVICE):

**Monthly and yearly averages of precipitation**
- [over the norm period 1991-2020](https://data.geo.admin.ch/browser/index.html#/collections/ch.meteoschweiz.klimanormwerte-niederschlag_aktuelle_periode)
- [over the norm period 1961-1990](https://data.geo.admin.ch/browser/index.html#/collections/ch.meteoschweiz.klimanormwerte-niederschlag_1961_1990)

**Monthly and yearly averages of temperature**
- [over the norm period 1991-2020](https://data.geo.admin.ch/browser/index.html#/collections/ch.meteoschweiz.klimanormwerte-temperatur_aktuelle_periode)
- [over the norm period 1961-1990](https://data.geo.admin.ch/browser/index.html#/collections/ch.meteoschweiz.klimanormwerte-temperatur_1961_1990)

**Monthly and yearly averages of relative sunshine duration**
- [over the norm period 1991-2020](https://data.geo.admin.ch/browser/index.html#/collections/ch.meteoschweiz.klimanormwerte-sonnenscheindauer_aktuelle_periode)
- [over the norm period 1961-1990](https://data.geo.admin.ch/browser/index.html#/collections/ch.meteoschweiz.klimanormwerte-sonnenscheindauer_1961_1990)

## Data format

The data formats are 
- [`NetCDF`](https://www.unidata.ucar.edu/software/netcdf/) with an estimated volume of 1.1 MB for *individual files [to be verified]*, and 13 MB for monthly files with daily data;
- [`GeoTIFF`](https://trac.osgeo.org/geotiff).

## Coordinate system

The coordinate system is [`Swiss LV95`](https://www.swisstopo.admin.ch/en/the-swiss-coordinates-system) / [`EPSG:2056`](https://epsg.io/2056). 

## Data usage

See e.g. MeteoSwiss' [Norm value charts](https://www.meteoswiss.admin.ch/services-and-publications/applications/ext/climate-norm-maps-public.html#https%3A%2F%2Fservice.meteoswiss.ch%2Fproductbrowser%2FproductDisplay%2Fclimate-norm-maps-public%3Flang=en&cg1.parameter=FrostDays&cg1.normalPeriod=1961-1990&cg1.productName=climate-indicators-maps-norm) application.
