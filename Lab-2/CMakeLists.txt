cmake_minimum_required(VERSION 3.5)
project(Spherical)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES main.cpp Vector3D.cpp Vector3D.h RealWorld.cpp RealWorld.h Spherical.cpp Spherical.h)
add_executable(Spherical ${SOURCE_FILES})
