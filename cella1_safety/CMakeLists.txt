cmake_minimum_required(VERSION 3.0.2)
project(cella1_safety)

find_package(catkin REQUIRED COMPONENTS
  cella1_descriptions
  velocity_scaling_iso15066
)

catkin_package(
)

# install(FILES
#   # myfile1
#   # myfile2
#   DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION}
# )
