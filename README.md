# robot_steering_rwt

Emulates the rqt_robot_steering plugin (https://github.com/ros-visualization/rqt_robot_steering) in HTML and JavaScript.

Uses Robot Web Tools' roslibjs library: https://github.com/RobotWebTools/roslibjs/blob/develop/build/roslib.js

Controls a turtlesim turtle by default, but you can change the topic to control anything that uses geometry_msgs/Twist messages.

Usage:
1. roslaunch rosbridge_server rosbridge_websocket.launch port:=<port_number>
2. Open robot_steering.html in your browser (may only work in Firefox)
