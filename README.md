# ROS_Packages_Download

The second task that was required to do in AI track in Smart Methods summer internship was to download the packages and the dependencies of the ROS so we start by:
Firstly, we will create a directory and change the directory to the newly made one.

Then, we download the Kinetic Distro Packages which are:

$ sudo apt-get install ros-kinetic-moveit
$ sudo apt-get install ros-kinetic-joint-state-publisher ros-kinetic-joint-state-publisher-gui
$ sudo apt-get install ros-kinetic-gazebo-ros-control joint-state-publisher
$ sudo apt-get install ros-kinetic-ros-controllers ros-kinetic-ros-control

Then, we download the Noetic Distro Packages which are:

$ sudo apt-get install ros-noetic-moveit
$ sudo apt-get install ros-noetic-joint-state-publisher ros-noetic-joint-state-publisher-gui
$ sudo apt-get install ros-noetic-gazebo-ros-control joint-state-publisher
$ sudo apt-get install ros-noetic-ros-controllers ros-noetic-ros-control

Then, we will open another terminal and change directory to the one that we made.

Then we will write catkin init , and catkin_make

Lastly, we will clone from git https://github.com/smart-methods/arduino_robot_arm and then put the source /home/abdulrhmanaissa/catkin_ws/devel/setup.bash

Launch ROS
