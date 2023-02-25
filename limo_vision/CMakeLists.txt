cmake_minimum_required(VERSION 3.0.2)
project(limo_vision)

find_package(catkin REQUIRED COMPONENTS)

catkin_package(
#  INCLUDE_DIRS include
#  LIBRARIES limo_vision
#  CATKIN_DEPENDS darknet_ros
#  DEPENDS system_lib
)

include_directories(
# include
  ${catkin_INCLUDE_DIRS}
)
