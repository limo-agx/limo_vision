# Limo Vision

![Yolo](https://limo-agx.github.io/_images/yolo.png)

This package contains a basic example setup for using Yolo object recognition on a Limo robot

## Set Up

Clone this repo into your workspace, install dependencies, build and source

    git clone --recursive http://github.com/limo-agx/limo_vision.git
    cd ..
    rosdep install --from-paths src --ignore-src -y
    catkin_make
    source devel/setup.bash

## Usage

    roslaunch limo_vision darknet_ros.launch

## More Documentation

[Vision - Limo Docs](https://limo-agx.github.io/vision.html)