^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package ouster_client
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

0.1.3 (2019-06-03)
------------------
* removed devel check
* Contributors: Marc Hanheide

0.1.2 (2019-06-03)
------------------
* Merge pull request `#3 <https://github.com/LCAS/ouster_example/issues/3>`_ from LCAS/scosar-dev
  Included roscpp in package.xml
* Included roscpp to package.xml of ouster_client
* Fix header dependencies
* Typo in CMakelist
* Fix CMakelist of ouster_client
* Contributors: Serhan Cosar, scosar

0.1.1 (2019-05-31)
------------------
* Removing ouster_viz (`#2 <https://github.com/LCAS/ouster_example/issues/2>`_)
  * Removing ouster_viz
  * Remove dependencies on ouster_viz
  * Fix CMakelist of ouster_client
  * Typo in CMakelist
  * Remove visualization example code and Fix timestamp problem
  * Fix tf2 error in build
  * Added tf2_geometry_msgs in CMakelist and package.xml
  * Fix header dependencies
* Update CMakefile
* Install target for include (ouster_client)
* Merge pull request `#1 <https://github.com/LCAS/ouster_example/issues/1>`_ from LCAS/marc-hanheide-patch-1
  merging despite not fully fix to hand over to @scosar
* use include_directories
* change jsoncpp keys
* Changed maintainer in package.xml files
* Performance improvements and bug fixes
  * Should fix packet dropping in 2048x10 mode
  * Minor functionality changes to visualizer
  * Client sets lidar_mode
  * Client queries calibration values from sensor
  * Publish frame transforms and ROS image topics
  * See CHANGELOG.md for details
* Initial commit of the example visualizer
  * Uses VTK6 to display point clouds and range/intensity/noise images
  * No dependencies other than VTK6, Eigen3, and a C++11 compiler
  * Currently only supports linux; tested on multiple distributions and platforms
* OS1 example client and ROS node
* Contributors: Dima Garbuzov, Marc Hanheide, Serhan Cosar, scosar
