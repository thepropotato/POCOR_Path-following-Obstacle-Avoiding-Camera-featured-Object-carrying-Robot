# POCOR : Path following Object avoiding Camera featured Object carrying Robot

## Description
This is a project that involves a robot built on the ROS2 (Robot Operating System 2) framework with the simulation in gazebo. The robot is designed to perform several tasks including path following, object avoidance (using Nav2), and carrying objects and also has a camera feature to the bot.

## Requirements:
* Ubuntu 22.04
* ROS2-HUMBLE
* Gazebo
* rviz2

## Process to run the robot:
Open a new terminal in the workspace directory, run the following command <br>
<code> ros2 launch pocor launch_sim.launch.py world:=./src/pocor/worlds/final_worl.world</code> <br>
Open a another new terminal window in the same workspace directory and run the following command <br>
<code> ros2 launch pocor path_navigation_launch.py</code> <br>
Open a another termial window in the same workspace, and change the path to <code> /src/pocor/scripts </code>, run the below command:<br>
<code>python3 path1.py</code>
Path can be changed by replacing the the above path1.py script file with the respected the path file.

## File Tree:
<code>!![alt text](image.png)
</code>

## Implementation Image:
  ![alt text](pocor.png)

## Sample Video of implementation:
In the following video, the path is given from the initial pose of the robot to post office.<br><br>
[![YouTube Video](http://img.youtube.com/vi/KBPrTQj0oMI/0.jpg)](https://youtu.be/KBPrTQj0oMI)

## Real life implementations:
* Industrial Automation
* Home cleaning
* Health care


