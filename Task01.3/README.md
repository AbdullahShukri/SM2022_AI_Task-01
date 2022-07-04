## Install xubuntu in  Jetson Nano
This repo aims to describe step by step the process and algorithms used to install xubuntu in  Jetson Nano
<br>

### Table of Contents
* [Install xubuntu in Jetson Nano](#install_xubuntu_in_Jetson_Nano)
* [Download balena](#download_balena)
* [Watch the video](#Watch_the_video)
* [Installation](#Installation)
* [Testing](#testing)
* [Concluion](#concluion)
<br>


## Install xubuntu in  Jetson Nano
#### https://github.com/Discombobulated88/Xubuntu-20.04-L4T-32.3.1/releases/download/v1.0/Xubuntu-20.04-l4t-r32.3.1.tar.tbz2
<br>


## Download balena
#### https://www.balena.io/etcher/
after we download both Should be write xubuntu to flash or card useing balena
![Alt Text](https://www.balena.io/static/steps-8006dca57323756b1b84fb9408742409.gif)
<br>
<br>


## Watching the video
#### https://www.youtube.com/watch?v=6WZOlkS4D7c
<br>


## Installation
#### https://docs.ros.org/en/foxy/Installation/Ubuntu-Install-Debians.html


## Testing
If you installed ros-foxy-desktop above you can try some examples.
<br>

In one terminal, source the setup file and then run a C++ ``` talker```:
```
source /opt/ros/foxy/setup.bash
ros2 run demo_nodes_cpp talke
```
In the below image on the left Terminal.

In another terminal source the setup file and then run a Python ```listener```:
```
source /opt/ros/foxy/setup.bash
ros2 run demo_nodes_py listener
```
In the below image on the right Terminal.


![Task 01 2](https://user-images.githubusercontent.com/101488769/176994276-2ff7332f-40bb-4b92-ad6f-a5aa9768025c.png)
<br>
<br>

## Concluion 
there are few ways to install and set up ROS2 on Ubuntu which usually is a straight fowrward process. I chose to do this task using this method since it simplifies the process and prevent possiople errors.
