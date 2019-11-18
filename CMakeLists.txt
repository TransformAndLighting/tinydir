cmake_minimum_required(VERSION 3.12)

project(tinydir)
add_library(tinydir INTERFACE)

install(FILES ${PROJECT_SOURCE_DIR}/tinydir.h DESTINATION include/tinydir)
