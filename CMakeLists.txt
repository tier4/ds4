cmake_minimum_required(VERSION 2.8.3)
project(ds4)

add_compile_options(-std=c++11)

find_package(catkin REQUIRED COMPONENTS
  message_generation
  std_msgs
  sensor_msgs
)

add_message_files(
  DIRECTORY msg
  FILES
  DS4.msg
)

generate_messages(
  DEPENDENCIES
  std_msgs
)

catkin_package(
#  INCLUDE_DIRS include
#  LIBRARIES ds4_driver
#  CATKIN_DEPENDS other_catkin_pkg
#  DEPENDS system_lib
)
