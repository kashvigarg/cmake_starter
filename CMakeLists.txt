cmake_minimum_required(VERSION 3.0.0)
project(cmake_starter VERSION 0.1.0)

include(CTest)
enable_testing()

add_executable(cmake_starter main.cpp)

set(CPACK_PROJECT_NAME ${PROJECT_NAME})
set(CPACK_PROJECT_VERSION ${PROJECT_VERSION})
include(CPack)
