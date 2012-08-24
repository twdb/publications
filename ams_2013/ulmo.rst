Title
=====
An open source library for clean, simple and fast access to public hydrology and climatology data


Abstract
========

There are many high quality hydrology and climatology datasets available over
the web, but these datasets are usually structured uniquely, with distinct
querying mechanisms and delivery formats. Liberating data from their native
structures is often tedious and error-prone. This is why we created Ulmo, an
open source python library for clean, simple and fast access to public hydrology
and climatology data.

Ulmo retrieves and parses datasets from the web and returns simple python data
structures that can be easily pulled into more sophisticated tools for analysis.
Working directly over the network is often impractical, particularly with large
datasets, so Ulmo also provides fast local caches. Data can be initially
downloaded once and updates harvested as needed, conserving bandwidth and time. 

Ulmo currently supports CUAHSI WaterOneFlow services, United States Geologic
Survey National Water Information System web services and data from the National
Climatic Data Center's Global Summary of the Day, with support for more datasets
on the way. Ulmo is being actively used by the Texas Water Development Board in
support of our Surface Water Resources program.



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

