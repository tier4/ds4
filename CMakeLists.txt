cmake_minimum_required(VERSION 2.8.3)
project(ds4_driver)

add_compile_options(-std=c++11)

find_package(catkin REQUIRED)

# add_message_files(
#   FILES
#   Message1.msg
#   Message2.msg
# )

# generate_messages(
#   DEPENDENCIES
#   std_msgs  # Or other packages containing msgs
# )

catkin_package(
#  INCLUDE_DIRS include
#  LIBRARIES ds4_driver
#  CATKIN_DEPENDS other_catkin_pkg
#  DEPENDS system_lib
)

include_directories(
  ${catkin_INCLUDE_DIRS}
)

# add_library(${PROJECT_NAME}
#   src/${PROJECT_NAME}/ds4_driver.cpp
# )

# add_dependencies(${PROJECT_NAME} ${${PROJECT_NAME}_EXPORTED_TARGETS} ${catkin_EXPORTED_TARGETS})

# add_executable(${PROJECT_NAME}_node src/ds4_driver_node.cpp)

# add_dependencies(${PROJECT_NAME}_node ${${PROJECT_NAME}_EXPORTED_TARGETS} ${catkin_EXPORTED_TARGETS})

# target_link_libraries(${PROJECT_NAME}_node
#   ${catkin_LIBRARIES}
# )
