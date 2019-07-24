cmake_minimum_required(VERSION 2.8.3)
project(furniture_description)

find_package(catkin REQUIRED COMPONENTS
)

catkin_package(
#  INCLUDE_DIRS include
#  LIBRARIES mtc_demos
#  CATKIN_DEPENDS other_catkin_pkg
#  DEPENDS system_lib
)

include_directories(
  ${catkin_INCLUDE_DIRS}
)

