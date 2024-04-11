# Earth Magnetic Field Viewer :earth_americas:

The code presented here uses the International Geomagnetic Reference Field version 13 ([IGRF-13](https://www.ngdc.noaa.gov/IAGA/vmod/igrf.html)) to calculate the magnetic field elements to create a visualization of the Earth's magnetic field.

For this code, we use the igrf_utils.py file from the [python package](https://www.ngdc.noaa.gov/IAGA/vmod/pyIGRF.zip).

In the notebook, the magnetic field elements are presented at a single point.

The strength of the magnetic field is also displayed over a basemap. The result is shown below:

![Magnetic field map](/Figures/MagneticFieldMap.png)


[Basemap](https://matplotlib.org/basemap/stable/) was used to achieve this result.

