cmake_minimum_required(VERSION 3.13)  # CMake version check
project(dbus-client-server)           # Create project "simple_example"
set(CMAKE_CXX_STANDARD 14)            # Enable c++14 standard


set(CLIENT_SOURCE_FILES add-client.c)
set(SERVER_SOURCE_FILES add-server.c)

# Add executable target with source files listed in SOURCE_FILES variable
add_executable(add-client ${CLIENT_SOURCE_FILES})
add_executable(add-server ${SERVER_SOURCE_FILES})
