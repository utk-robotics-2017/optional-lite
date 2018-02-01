# Copyright 2016 by Martin Moene
#
# https://github.com/martinmoene/optional-lite
#
# This code is licensed under the MIT License (MIT).

cmake_minimum_required(VERSION 3.0)

# define the project
project(optional)

# create and configure the library target
add_library(optional INTERFACE)
SET(CMAKE_CXX_STANDARD 11)
target_include_directories(optional INTERFACE include/nonstd)

