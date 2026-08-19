cmake_minimum_required(VERSION 3.10.0)
project(earth-sim VERSION 0.1.0 LANGUAGES C CXX)

add_executable(earth-sim src/main.cpp)

set(CPACK_PROJECT_NAME ${PROJECT_NAME})
set(CPACK_PROJECT_VERSION ${PROJECT_VERSION})
include(CPack)
