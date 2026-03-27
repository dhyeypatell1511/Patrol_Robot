# Patrol_Robot
simulation of patrol robot on ROS2 and Gazebo.

the packages and other things are done in ROS2 Humble


replace turtlebot3_world.world original file code with the given file code below..

do colcon build --symlink-install

ros2 launch roboai_patrol turtlebot3_world.launch.py 
opens gazebo

open new terminal :
ros2 launch roboai_patrol nav2.launch.py

opens rviz

open new terminal:
ros2 launch roboai_autonomy autonomy.launch.cpp
starts the robot to move to the given coordinates one after the other.
