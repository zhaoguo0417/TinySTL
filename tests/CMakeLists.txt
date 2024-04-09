include_directories(${PROJECT_SOURCE_DIR}/include/TinySTL)

set(SRC test.cpp)
set(EXECUTABLE_OUTPUT_PATH ${PROJECT_SOURCE_DIR}/bin)
add_executable(stltest ${SRC})