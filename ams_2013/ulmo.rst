Title
=====


Abstract
========

There is an abundance of high quality public hydrology datasets available over
the web. But very often these datasets are structured differently and so before
we can actually work with the data we have to slog through a bit of tedious work
to liberate data from the formats they are served in. This is why we've created
Ulmo, an open source python library for clean, simple and fast access to public
hydrology datasets.


Ulmo retrieves and parses datasets from the web and returns simple python data
structures that can be easily pulled into more sophisticated tools for analysis.
Work directly over the network can be impractical, particularly with large
datasets, so Ulmo also provides fast local caches. Data can be initially
downloaded once and updates are harvested as needed, conserving bandwidth and
time. 



Ulmo currently supports CUAHSI WaterOneFlow services, United States Geologic
Survey water web services, National Climatic Data Center Global Summary of the
Day.



Authors
=======
Andy Wilson
Dharhas Pothina





Outline
=======

- intro
  - about the name
  - TWDB


- simple
  consistent API 
  examples


- fast
  HDF5 (pytables) backed datastores


- datasets
  WOF
  USGS
  NCDC
  others(?)


- open source
  github


- demo?

