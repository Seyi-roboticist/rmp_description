cmake_minimum_required(VERSION 3.8)
project(rmp_description)

if(CMAKE_COMPILER_IS_GNUCXX OR CMAKE_CXX_COMPILER_ID MATCHES "Clang")
  add_compile_options(-Wall -Wextra -Wpedantic)
endif()

# find dependencies
find_package(ament_cmake REQUIRED)
find_package(xacro REQUIRED)
find_package(ur_description REQUIRED)
find_package(robotiq_description REQUIRED)

ament_package()
