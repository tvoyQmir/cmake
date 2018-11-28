#
# This file was genared by D:\git123\proj2cmake\Debug\proj2cmake.exe and will be overwritten on it's next run!
# Please put all configurations in the cmake_conf/*.cmake files.
#
set (SOLUTION_DIR ${CMAKE_CURRENT_LIST_DIR})
cmake_minimum_required(VERSION 2.8)

ADD_EXECUTABLE(main "main.cpp")

set_property(TARGET main PROPERTY CXX_STANDARD 11) 

TARGET_LINK_LIBRARIES(main ${SOLUTION_DIR}/foo/libfoo.a)



