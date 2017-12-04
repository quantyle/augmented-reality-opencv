cmake_minimum_required(VERSION 2.8)
project( AR-CV )
find_package( OpenCV REQUIRED )
add_executable( AR-CV main.cpp)
target_link_libraries( AR-CV ${OpenCV_LIBS} )

find_package( SDL2 REQUIRED)
target_link_libraries( AR-CV ${SDL2})
