cmake_minimum_required(VERSION 3.29)
project(hoe4)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)
include_directories(.idea)

add_executable(hoe4
    .idea/.gitignore
    .idea/editor.xml
    .idea/hoe4.iml
    .idea/misc.xml
    .idea/modules.xml
    .idea/vcs.xml
    .idea/workspace.xml
    main.cpp
    problems.h)
