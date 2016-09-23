cmake_minimum_required(VERSION 3.6)
project(CurrencyExchange2)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wall -Wextra -std=c++14")

set(SOURCE_FILES main.cpp)
add_executable(CurrencyExchange2 ${SOURCE_FILES})