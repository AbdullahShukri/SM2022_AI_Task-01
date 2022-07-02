# Install ROS2 Foxy in Ubuntu 20.04
This repo aims to describe step by step the process and algorithms used to install ROS2 on a Ubuntu
<br>
<br>

### Table of Contents
* [Installation](#installation)
* [Video to help](#video_to_help)
* [Testing](#testing)
* [Concluion](#concluion)
<br>


## Installation
Install the `ros-foxy-ros-base` package following these directions:
* ROS2 Foxy - [ROS2 Install Instructions](https://docs.ros.org/en/foxy/Installation/Ubuntu-Install-Debians.html)
<br>


## Video to help
https://www.youtube.com/watch?v=fxRWY0j3p_U
<br>


## Testing
If you installed ros-foxy-desktop above you can try some examples.
<br>

In one terminal, source the setup file and then run a C++ ``` talker```:
```
source /opt/ros/foxy/setup.bash
ros2 run demo_nodes_cpp talke
```

In another terminal source the setup file and then run a Python listener:
```
source /opt/ros/foxy/setup.bash
ros2 run demo_nodes_py listener
```


![Task 01 2](https://user-images.githubusercontent.com/101488769/176994276-2ff7332f-40bb-4b92-ad6f-a5aa9768025c.png)
<br>


## Concluion 
there are few ways to install and set up ROS2 on Ubuntu which usually is a straight fowrward process. I chose to do this task using this method since it simplifies the process and prevent possiople errors.
