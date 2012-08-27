Title
=====
Smear: An open source, parallel python toolkit for spatial interpolation of large irregular two-dimensional scattered datasets

Abstract
========

Geophysical datasets collected to study the Earth often come in the form of
two-dimensional scattered points to which measurements are attached. These
datasets often have highly irregular spatial distributions. Examples
include bathymetric data, which are normally collected at high sample rates
along a boat track but can have significantly large distances between each
boat track. Rain gauge networks are also representative datasets, where the
locations of gauges are often determined by factors like funding and available
cooperators. Values for unsampled locations must be interpolated for use in
visualization products, simulation models or aggregations to larger spatial
units. The properties of the feature being modeled and the spatial distribution
of measurements determine which interpolation methods are appropriate. For
example, anisotropic systems like river channel beds where bathymetric
variability is greater transverse to the flow direction, are usually more
accurately modeled by methods that account for the anisotropy.


Most current spatial interpolation software are commercial and are often
accessible only through a GUI interface and are not easily scriptable or
extendable. Smear was developed to provide an extendable open source toolkit for
spatial interpolation.


Smear utilizes open source python scientific and GIS libraries to implement
several of these algorithms, including a channel-following anisotropic
interpolation algorithm. Large datasets are efficiently managed through the use
of k-dimensional trees for efficient neighborhood searches and a parallel
implementation based on the IPython parallel architecture allows use of
multicore systems and HPC clusters. 


At the Texas Water Development Board, this toolkit has been used to improve lake
volume and sediment estimates and to improve the representation of river and
channel bathymetry within hydrodynamic models.


Authors
=======
Dharhas Pothina
Andrew Wilson
Solomon Negusse
Tyler McEwen
