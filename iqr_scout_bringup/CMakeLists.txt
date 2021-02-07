cmake_minimum_required(VERSION 3.0.2)
project(iqr_scout_bringup)

find_package(catkin REQUIRED COMPONENTS
  iqr_scout_description
)

catkin_package(
#  INCLUDE_DIRS include
#  LIBRARIES iqr_scout_bringup
#  CATKIN_DEPENDS iqr_scout_description
#  DEPENDS system_lib
)

include_directories(
# include
  ${catkin_INCLUDE_DIRS}
)
