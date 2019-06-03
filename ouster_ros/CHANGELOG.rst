^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package ouster_ros
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

0.1.5 (2019-06-03)
------------------
* Merge pull request `#4 <https://github.com/LCAS/ouster_example/issues/4>`_ from LCAS/scosar-dev
  Fix missing launch file
* Fix missing launch file
* Contributors: Serhan Cosar, scosar

0.1.4 (2019-06-03)
------------------

0.1.3 (2019-06-03)
------------------

0.1.2 (2019-06-03)
------------------
* Fix header dependencies
* Added tf2_geometry_msgs in CMakelist and package.xml
* Fix tf2 error in build
* Remove visualization example code and Fix timestamp problem
* Remove dependencies on ouster_viz
* Contributors: Serhan Cosar

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
* Changed maintainer in package.xml files
* Performance improvements and bug fixes
  * Should fix packet dropping in 2048x10 mode
  * Minor functionality changes to visualizer
  * Client sets lidar_mode
  * Client queries calibration values from sensor
  * Publish frame transforms and ROS image topics
  * See CHANGELOG.md for details
* Fix minor bugs and typos
  * Improve positional argument parsing in viz
  * Use allocate_shared for Eigen compatibility
  * Fix typo in readme
* Initial commit of the example visualizer
  * Uses VTK6 to display point clouds and range/intensity/noise images
  * No dependencies other than VTK6, Eigen3, and a C++11 compiler
  * Currently only supports linux; tested on multiple distributions and platforms
* Use correct units in sensor_msgs::Imu
* Deal with time going backwards in replays
* OS1 example client and ROS node
* Contributors: Dima Garbuzov, Roy Rinberg, Serhan Cosar, scosar
