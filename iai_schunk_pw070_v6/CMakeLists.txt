cmake_minimum_required(VERSION 3.5)
project(iai_schunk_pw070_v6)

find_package(ament_cmake REQUIRED)

install(DIRECTORY launch
  DESTINATION share/${PROJECT_NAME})

install(DIRECTORY meshes
DESTINATION share/${PROJECT_NAME})

install(DIRECTORY robots
  DESTINATION share/${PROJECT_NAME})

ament_package()
