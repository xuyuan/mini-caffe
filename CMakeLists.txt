project(mini-caffe C CXX)
cmake_minimum_required(VERSION 2.8)

if(CMAKE_COMPILER_IS_GNUCXX)
  set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")
endif()

include(mini-caffe.cmake)
include(tests/tests.cmake)
include(tools/tools.cmake)
