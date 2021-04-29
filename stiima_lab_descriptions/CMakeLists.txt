cmake_minimum_required(VERSION 2.8.3)
project(stiima_lab_descriptions)


find_package(catkin REQUIRED)

catkin_package(

)


include_directories(
)


install(FILES
 urdf/conveyor_system.urdf.xacro
 urdf/elmo_linear_guide.urdf.xacro
 urdf/kinect_description.urdf.xacro
 urdf/swiss_cameras.urdf.xacro
 urdf/wheeled_table.urdf.xacro
 meshes/conveyor_system.STL
 DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION}
)

