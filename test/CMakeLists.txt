CMAKE_MINIMUM_REQUIRED(VERSION 3.0)
PROJECT(jsoncpp_test)

SET(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

add_definitions("-Dprivate=public")
ADD_EXECUTABLE(jsoncpp_test unit.cpp)
INCLUDE_DIRECTORIES(../src)
