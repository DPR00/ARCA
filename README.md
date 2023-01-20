To test ARCA joints run the following commands:

$ roslaunch arca3_description arca3_joint_control.launch

Then you must open Gazebo and Rviz. It will be displayed in both.

To move arca with the keyboard (similar to turtlebot), run the following command:

$ rosrun teleop_twist_keyboard teleop_twist_keyboard.py
