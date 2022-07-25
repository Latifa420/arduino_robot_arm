# arduino_robot_arm
Install and run the arm package on the ROS system

ROS packages that can be used to plan and execute motion trajectories for a robot arm in simulation and real-life.
These packages were tested under ROS kinetic and Ubuntu 16.04 and it works perfectly on ROS melodic and noetic
The robot arm uses Moveit plugin to apply kinematics by the KDL solver. These packages can be tested in the gazebo simulation tool and the real robot arm, where the ROS system and Arduino code share the /joint_states topic to control motors.

Robot Arm:

The robot arm has 5 joints only 4 joints can be fully controlled via ROS and Rviz, the last joint (gripper) has a default motion executed from the Arduino code directly.

Circuit diagram
![image](https://user-images.githubusercontent.com/86505558/180885414-a8e47ca8-1384-4943-ba67-34b5fcc64e42.png)


Robot initial positions
![image](https://user-images.githubusercontent.com/86505558/180885441-59070702-6e9d-4aa5-948e-0aadad3aa8a0.png)
