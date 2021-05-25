## This is fork of `ros_controllers/diff_drive_controller` 
---

* It's forked from `noetic-devel` branch.
* It contains an implementation of odometry computation using velocity feedback.
* Original implementation use position feedback for odom computation and velocity estimation.
* Reasoning for using velocity feedback:  `RoboteQ` motor controllers already perform velocity estimation in their firmware, so it's simpler to directly use that and not having to worry about encoder count overflow.







## Original README.md
---
Controller for a differential drive mobile base.

Detailed user documentation can be found in the controller's [ROS wiki page](http://wiki.ros.org/diff_drive_controller).
