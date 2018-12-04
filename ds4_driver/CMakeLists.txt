cmake_minimum_required(VERSION 2.8.3)
project(ds4_driver)

find_package(catkin REQUIRED COMPONENTS
  sensor_msgs
)

catkin_package(
  CATKIN_DEPENDS
  sensor_msgs
)
