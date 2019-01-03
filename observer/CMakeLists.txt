cmake_minimum_required(VERSION 3.8)
##
## PROJECT
## name and version
##
project(csari_observer VERSION 1.1.0 LANGUAGES CXX)

##
## OPTIONS
##
## No options yet

##
## TARGET
## create target and add include path
##
add_library(${PROJECT_NAME} INTERFACE)
target_include_directories(${PROJECT_NAME} INTERFACE ./include)
