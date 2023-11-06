# zau2

## Dependencies
First of all, make sure you have `mmtbot` (and its dependencies) installed and working properly.

```
git clone https://bitbucket.org/DataspeedInc/velodyne_simulator -b master
git clone https://github.com/ros/geometry2.git
git clone https://github.com/nilseuropa/realsense_ros_gazebo


git clone https://github.com/IntelRealSense/realsense-ros.git
cd realsense-ros/
git checkout `git tag | sort -V | grep -P "^2.\d+\.\d+" | tail -1`
```

## Launching the system

To launch the system in Gazebo and RViz:

`roslaunch zau2_bringup zau2_bringup.launch`

To start the teleop:

`roslaunch zau2_bringup zau2_teleop.launch`
