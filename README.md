# blob-chase-bveeta-mini

Compilation
===========
1. Follow ROS installation (Desktop Full Install): http://wiki.ros.org/kinetic/Installation/Ubuntu
2. Create catkin workspace:
	mkdir -p ~/catkin_ws/src
	cd ~/catkin_ws
	catkin_make
3. Clone project:
	cd ~
	git clone https://github.com/joffman/ros_object_recognition.git
4. Copy/Move src folder into your workspace.
	cp -r ~/ros_object_recognition/src/* ~/catkin_ws/src/
5. Compile:
	cd ~/catkin_ws
	catkin_make
