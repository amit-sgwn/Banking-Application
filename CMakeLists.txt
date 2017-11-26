cmake_minimum_required(VERSION 3.8)
project(Banking_Application)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES main.cpp Model/Account/Account.cpp Model/Account/Account.h)
add_executable(Banking_Application ${SOURCE_FILES})