# CoppeliaSim_Robotics
### This repo contains all the stuff that I am trying out on CoppeliaSim. 

## FILES COMMITTED TILL NOW
### 1. LuaScriptForJointRecordingUR5 : A classic UR 5 recording the Joint angle details using sysCalls. The data is saved in the form of a CSV [File name : robot_data.csv] 
### 2. PythonControllerForRobots : A python script that can send data about the waypoints usingg ZMQ API. Here, the IK engine of Coppelia is used for calculations.
### 3. 6dofcontrolFK : A python script to send joint angles(forward kinematics mode) Currently, there is smoothened trajectory. The arms jumps to the position.
