# src/CMakeLists.txt

file(GLOB SOURCES "*.cpp")

add_library(math_functions STATIC ${SOURCES})
target_include_directories(math_functions PUBLIC ${CMAKE_CURRENT_SOURCE_DIR})
