Pionner Simulator
===========

A ROS/Gazebo Pioneer 3DX simulator.

To start the simulator:

	$ roslaunch p3dx_gazebo pioneer_office.launch

In order to move the robot, publish control commands to ROS topic /cmd_vel. You can also get laser scan reading from topic /p3dx/laser/scan.