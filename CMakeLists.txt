cmake_minimum_required(VERSION 2.8.3)
project(camera_info_manager_node)

find_package(catkin REQUIRED COMPONENTS
  rospy
  sensor_msgs
)

catkin_package(
  CATKIN_DEPENDS sensor_msgs
)


