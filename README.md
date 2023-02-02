# FlatsimDashboard
An interactive tool to explore Flatsim InSAR time-series

In order to run the notebook, you may need to install a few libraries.

Here is the receipe to create a fresh conda environment that embed the necessary libraries:
```code
conda create --name GeoViews_py39 python=3.9 \
  geoviews-core \
  datashader \
  matplotlib \
  netcdf4 \
  pyproj \
  pyarrow \
  fastparquet \
  python-snappy \
  hvplot \
  ipywidgets \
  pooch \
  rioxarray \
  intake intake-parquet intake-xarray \
  s3fs \
  pykml \
  --yes

conda activate GeoViews_py39
```

