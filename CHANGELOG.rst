^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package occupancy_grid_utils
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^


0.0.10 (2016-04-19)
-------------------
* new maintainer
* Contributors: Marc Hanheide

0.0.9 (2016-04-19)
------------------

0.0.8 (2016-04-13)
------------------
* Merge pull request `#11 <https://github.com/clearpathrobotics/occupancy_grid_utils/issues/11>`_ from clearpathrobotics/CORE-3712_handle_raytrace_out_of_bounds
  Handle raytrace out of bounds
* :lipstick:
* Rename project_target_onto_grid param in cpp
  Make the name in the cpp consistent with the name in the header.
* Project target onto grid
  fixes CORE-3712
  This projects the target point onto the grid before ray tracing, so
  it'll never fail to produce a scan, even if the robot is outside the
  map.
* Change maintainer
* Merge pull request `#9 <https://github.com/clearpathrobotics/occupancy_grid_utils/issues/9>`_ from hrnr/build-fix
  do not export python library
* do not export python library
  it is outdated (eg. generates messages) and gets linked to c++ code which then have dependency on python
* Contributors: Enrique Fernandez, Enrique Fernández Perdomo, James Servos, Jiri Horner

0.0.7 (2015-09-22)
------------------
* Merge pull request `#8 <https://github.com/clearpathrobotics/occupancy_grid_utils/issues/8>`_ from clearpathrobotics/raytrace_free_space
  Raytrace free space based on max_distance
* Update raytrace comment
* Raytrace free space based on max_distance
* Contributors: James Servos

0.0.6 (2015-08-30)
------------------
* Fix non-installed *.hpp headers
* Contributors: Enrique Fernandez

0.0.5 (2015-02-25)
------------------
* Changed OpenCV dependency to 'cv_bridge' to work on hydro and indigo
* Compile in Boost libraries
* Fix compilation, gcc doesn't like use of the optional vars
* Fix some cppcheck warnings
* Use boost::ref(), not just ref()
* Contributors: Alex Bencz, Jonathan Jekir, Mike Purvis, Siegfried-A. Gevatter Pujals

0.0.4 (2014-02-19)
------------------
* change libopencv-dev to opencv2, since libopencv-dev is not present in the rosdep database for precise
* 0.0.4
* update changelog
* fixed a dependency issue with opencv
* Contributors: y22ma

0.0.3 (2014-02-16)
------------------
* remove dependency on SDL, which is terrible for CI build due to X server dependencies
* fix crlf for package.xml
* Contributors: y22ma

0.0.2 (2014-02-13)
------------------

0.0.1 (2014-02-13)
------------------
* Initial Hydro release catkinized from https://code.ros.org/svn/ros-pkg/stacks/graph_mapping/trunk/occupancy_grid_utils r40053.
* Contributors: Andreas Wachaja, Bhaskara Marthi, Mac Mason, Yan Ma
