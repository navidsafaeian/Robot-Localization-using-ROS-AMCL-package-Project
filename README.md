# Robot Localization using ROS Navigation Slack and AMCL ROS Package 

[rvizgif]:WhereAmI.gif
[writeup]:writeup-WhereAmI.png

![rvizgif]

## RoboND __'Where am I?'__ Project 

This project utilizes ROS packages to accurately localize a mobile robot inside a provided map in the Gazebo and RViz simulation environments. <br>
Two mobile robot simulated in this project (Udacity bot benchmark model and Safa bot personal model).

## Run the Project
- For the __udacity bot benchmark model__ run the following in separate terminal: <br>
``` bash
$ roslaunch udacity_bot masterRun_udacity_bot.launch 
$ rosrun udacity_bot navigation goal
```
or <br>
``` bash
$ roslaunch udacity_bot udacity_bot 
$ roslaunch udacity_bot amcl
$ rosrun udacity_bot navigation goal
``` 

- For the __Safa bot benchmark model__ run the following in separate terminal: <br>
``` bash
$ roslaunch udacity_bot masterRun_safa_bot.launch 
$ rosrun udacity_bot navigation goal
```
or <br>
``` bash
$ roslaunch udacity_bot safa_bot
$ roslaunch udacity_bot safa_amcl
$ rosrun udacity_bot navigation goal
```
## Project Writeup:

![writeup]



