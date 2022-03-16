# ROSbot-Swarms-Exploration-and-Mapping

The robost_multi_sim package is a package that launch multi ROSbot simulation under ROS Noetic.
The main file is the rosbots_starter_gazebo_main.launch

This package requires a few other packages :
  * [rosbot_description](https://github.com/husarion/rosbot_description)
  * [multirobot_map_merge](https://github.com/sugnite/m-explore/)
  * [gmapping](https://github.com/ros-perception/slam_gmapping)


Installing
----------

You can run the following commands to setup a build from source:

```
 cd catkin_ws/src
```
Clone the package
```
 git clone https://github.com/sugnite/ROSbot-Swarms-Exploration-and-Mapping
```
Build and update the workspace
```
 catkin_make
 rosdep update

```
