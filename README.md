# my_robot_urdf
Assignment for Mobile Robotics examination. 

To run this code you need Ubuntu 18.04 and ROS Melodic.
Open the terminal and digit the following lines:

'''
cd catkin_ws/src
git clone https://github.com/rbngpp/my_robot_urdf.git
cd ~
cd catkin_ws
catkin_make
roscd my_robot_urdf
roslaunch my_robot_urdf display_x.launch model:=urdf/my_robot_x.urdf
'''

