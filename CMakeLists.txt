cmake_minimum_required(VERSION 3.10)

project(Server_Practice)

set(server_project_files
    source/main.c
)

include_directories(
    source/include
)

add_executable(Server_Practice ${server_project_files})
