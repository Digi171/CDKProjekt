cmake_minimum_required(VERSION 3.21)
project(CDKProjekt C)

set(CMAKE_C_STANDARD 99)

add_executable(CDKProjekt main.c Cmorej/cmorej.c Kandrac/kandrac.c Darak/darak.c)
