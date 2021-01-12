# UD_GO_CHASE_IT

A project of Udacity Nano-degree Robotics Software Engineer. 

A simple robot build in Gazebo with lidar and camera follows a white ball. 

# Tools 
1. ROS
2. GAZEBO
3. C++ 

## Installation
```
cd catkin_ws/src/
git clone https://github.com/gauti1311/UD_GO_CHASE_IT.git
```
## Build
```
cd ~/catkin_ws
caktin_make
```
## Run the Project
open a termnial
```
cd catkin_ws
source devel/setup.bash
roslaunch my_robot world.launch
```
in another terminal 
```
cd catkin_ws
source devel/setup.bash
roslaunch ball_chaser ball_chaser.launch
```

