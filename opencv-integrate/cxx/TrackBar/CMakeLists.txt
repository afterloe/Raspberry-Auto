cmake_minimum_required(VERSION 2.8)
project( LearnOpencv )
find_package( OpenCV REQUIRED )
include_directories( ${OpenCV_INCLUDE_DIRS} )
add_executable( TrackBar.out src/TrackBar.cpp )
target_link_libraries( TrackBar.out ${OpenCV_LIBS} )
