cmake_minimum_required(VERSION 2.8.10)
project(LBP_SVM-Linear)

include(CTest)
include(CheckFunctionExists)

if (CMAKE_COMPILER_IS_GNUCXX)
    set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wall")
endif (CMAKE_COMPILER_IS_GNUCXX)

set(LINKLIBS)

add_subdirectory(src)



