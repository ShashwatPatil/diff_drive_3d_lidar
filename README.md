# diff_drive_3d_lidar 
## All packages were made for ROS1 (Noetic)
### The urdf is in xacro so it will work for both ROS1 and ROS2, for ROS2 just new launch files would be required 



put all the contents of this git in a workspace/src folder 

build the workspace 

to  launch the gazebo and rviz visualization run the cmd 
```
# source your ws first 
roslaunch differential_drive_robot_description final.launch
```

to launch the teleop node run the cmd 
```
roslaunch differential_drive_robot_control teleop.launch
```

