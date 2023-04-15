# homeRobot
Udacity Robotic Software Engineering Course- home robot that can navigate in a given environment, finding objects and depositing them at a given location. Created and performed in gazebo. Involves gazebo basics, localisation, simultaneous localisation and mapping (SLAM), and path planning and navigation.

Instructions:
On a linux pc... 

1. Create "catkin_ws" directory
2. Create a directory "src" within this
3. Clone homeRobot into src
4. Initialise catkin workspace with $ catkin_init_workspace
5. In catkin_ws, compile files with $ catkin_make
    Other files should generate as a result
7. $ source devel/setup.bash
8. Now launch/run any files as needed

Project 2 - Go Chase It! ***

In terminal 1:

$ cd /home/workspace/catkin_ws/
$ source devel/setup.bash
$ roslaunch my_robot world.launch

In terminal 2:

$ cd /home/workspace/catkin_ws/
$ source devel/setup.bash
$ roslaunch ball_chaser ball_chaser.launch

In terminal 3:

$ cd /home/workspace/catkin_ws/
$ source devel/setup.bash
$ rosrun rqt_image_view rqt_image_view 
