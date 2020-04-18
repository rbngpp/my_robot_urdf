# my_robot_urdf
Assignment for Mobile Robotics examination. 

To run this code you need Ubuntu 18.04 and ROS Melodic.
Open the terminal and digit the following lines (just once):

```
pip install readchar
cd catkin_ws/src
git clone https://github.com/rbngpp/my_robot_urdf.git
cd ~
cd catkin_ws
catkin_make
```
And the following (any time you want to open the script):
```
roscd my_robot_urdf
roslaunch my_robot_urdf display_x.launch model:=urdf/my_robot_x.urdf
```
In a second terminal window do (just once):
```
roscd my_robot_urdf
cd src
sudo chmod +x talker.py
cd ..
```
Any time you want to open the script:
```
rosrun my_robot_urdf talker.py
```
With talker.py is possible to control the robot using the 'W-A-S-D' keys from keyboard.
Typing any other key will call the exit() function. 

