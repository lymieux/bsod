cmake_minimum_required(VERSION 3.23)

project(bsod)

add_executable(${PROJECT_NAME} ${PROJECT_SOURCE_DIR}/src/main.cpp)
target_link_libraries(${PROJECT_NAME} ${CMAKE_DL_LIBS})
