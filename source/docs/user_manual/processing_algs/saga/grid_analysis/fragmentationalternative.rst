Fragmentation (alternative)
===========================

Description
-----------

<put algortithm description here>

Parameters
----------

``Classification`` [raster]
  <put parameter description here>

``Class Identifier`` [number]
  <put parameter description here>

  Default: *1*

``Neighborhood Min`` [number]
  <put parameter description here>

  Default: *1*

``Neighborhood Max`` [number]
  <put parameter description here>

  Default: *1*

``Level Aggregation`` [selection]
  <put parameter description here>

  Options:

  * 0 --- [0] average
  * 1 --- [1] multiplicative

  Default: *0*

``Add Border`` [boolean]
  <put parameter description here>

  Default: *True*

``Connectivity Weighting`` [number]
  <put parameter description here>

  Default: *1.1*

``Minimum Density [Percent]`` [number]
  <put parameter description here>

  Default: *10*

``Minimum Density for Interior Forest [Percent]`` [number]
  <put parameter description here>

  Default: *99*

``Search Distance Increment`` [number]
  <put parameter description here>

  Default: *0.0*

``Density from Neighbourhood`` [boolean]
  <put parameter description here>

  Default: *True*

Outputs
-------

``Density [Percent]`` [raster]
  <put output description here>

``Connectivity [Percent]`` [raster]
  <put output description here>

``Fragmentation`` [raster]
  <put output description here>

``Summary`` [table]
  <put output description here>

Console usage
-------------

::

  processing.runalg('saga:fragmentationalternative', classes, class, neighborhood_min, neighborhood_max, aggregation, border, weight, density_min, density_int, level_grow, density_mean, density, connectivity, fragmentation, fragstats)

See also
--------

