CMAKE_MINIMUM_REQUIRED(VERSION 2.8)
PROJECT(orchid)
IF(APPLE)
    SET(CMAKE_CXX_COMPILER clang++)
ENDIF(APPLE)
ADD_SUBDIRECTORY(unit_test)