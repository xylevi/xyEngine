#cmake_minimum_required (VERSION 3.19.3)
set (CMAKE_C_STANDARD 11)
set (CMAKE_CXX_STANDARD 11)
project (xyEngine)
include_directories("${PROJECT_SOURCE_DIR}/Framework/Common")
include_directories("${PROJECT_SOURCE_DIR}/Framework/Interface")
add_subdirectory(Framework)
add_subdirectory(Dummy)