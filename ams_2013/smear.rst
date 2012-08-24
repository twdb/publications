Title
=====
Smear: An open source, parallel python toolkit for spatial interpolation of large irregular two-dimensional scattered datasets

Abstract
========

Geophysical datasets collected to study the Earth often come in the form of
two-dimensional scattered points to which measurements are attached. These
datasets will often have a highly irregular spatial distribution. For example, bathymetric
data are normally collected at high sample rates along a boat track but there can
be significantly large distances between each boat track. Another example is
rain gauge networks, where the location of the gauges is often determined by
factors like funding and available cooperators. In order to use these datasets
in visualization products, simulation models or aggregations to larger spatial
units, interpolation is required to estimate the value of a measurement at
unsampled locations. Depending on the properties of the feature being modeled
and the spatial distribution of measurements, varying spatial interpolation
methods may be appropriate. In many cases, anisotropy may be present and the
interpolation algorithm needs to be able to incorporate this anisotropy. An
example of this is river channel bed morphology where bathymetric variability is
greater transverse to the flow direction than along the flow direction.

Most current spatial interpolation software are commercial and are often
accessible only through a GUI interface and are not easily scriptable or
extendable. Smear was developed to provide an extendable open source toolkit for
spatial interpolation.

Smear utilizes open source python scientific and GIS libraries to
implement several of these algorithms. In addition, it implements a channel
following anistropic interpolation algorithm for features where the direction of
the anistropy changes in space such as in a river channel. Large datasets are
handled efficiently through the use of k-dimensional trees for efficient
neighborhood searches and a parallel implementation based on the IPython
parallel architecture allows use of multicore systems and hpc clusters. 

At the Texas Water Development Board, this toolkit has been used to improve lake
volume and sediment estimates and to improve the representation of river and
channel bathymetry within hydrodynamic models.

Authors
=======
Dharhas Pothina
Andrew Wilson
Solomon Negusse
Tyler McEwen
