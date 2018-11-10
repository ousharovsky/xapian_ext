cmake_minimum_required(VERSION 3.12)
project(xapian_ext)

set(CMAKE_CXX_STANDARD 17)

add_library(xapian_ext SHARED library.cpp library.h)