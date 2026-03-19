
cmake_minimum_required(VERSION 3.10)
project(DistributedMLTrainingSystem CXX)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED TRUE)

find_package(MPI REQUIRED)
include_directories(${MPI_INCLUDE_PATH})

add_executable(distributed_ml_training src/main.cpp)
target_link_libraries(distributed_ml_training ${MPI_LIBRARIES})
