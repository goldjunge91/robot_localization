cmake_minimum_required(VERSION 3.11)
project(robot_localization_tool)

find_package(ament_cmake REQUIRED)

install(DIRECTORY config launch DESTINATION share/${PROJECT_NAME})

ament_package()
