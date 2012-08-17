Title
=====
A new open source spatial interpolation toolkit and its application to volume and sediment estimates for Texas lakes.

Summary
=======


Abstract
========

With increasing population and water use demands in Texas, accurate estimates of lake and sediment volumes is a critical part of planning for future water supply needs. Lakes are large and surveying them is expensive in terms of labor, time and cost. Over the years, the Texas Water Development Board has settled on a 500ft spacing of survey lines for hydrographic data collection as a good balance between survey effort and level of data coverage. While this choice reduces the time spent in data collection, it increases the time needed for post processing significantly through the requirement for accurate spatial interpolation

In lakes and river channels bathymetric variability is greater transverse to the flow direction than along the flow direction. Standard spatial interpolation techniques available in commercial software are not well suited to this type of spatial interpolation. To improve the efficiency and repeatibility of our lake volumetric and sediment surveys we have developed an extendable open source toolkit for spatial interpolation.

This toolkit utilizes several open source Python scientific and GIS libraries to implement several common spatial interpolation algorithms. In addition, it implements a channel following anistropic interpolation algorithm for features where the direction of the anistropy changes in space such as in a river channel. Large datasets are handled efficiently through the use of k-dimensional trees for efficient nieghborhood searches and a parallel implementation based on the IPython parallel architecture allows use of multicore systems and hpc clusters. 


Bios
====

 Dharhas is a scientist in the Surface Water Resources division of the Texas Water Development Board. He has extensive experience in hydrodynamic modeling, spatial and time series analysis, data collection and data interoperability. He has led several internal and collaborative scientific software development projects to their successful conclusion and has developed new workflows and software tools to improve efficiency and reproducibility of scientific analyses conducted by TWDB. He is the project lead for the ongoing statewide Water Data for Texas initiative and has pioneered the use of web services to share water data from large data providers across the state of Texas.