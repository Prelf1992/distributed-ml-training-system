cmake_minimum_required(VERSION 3.10)
project(DistributedMLTrainingSystem CXX)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

# Find MPI
find_package(MPI REQUIRED)
include(${MPI_USE_FILE})

# Add executable
add_executable(distributed_ml_trainer src/main.cpp)

# Link MPI libraries
target_link_libraries(distributed_ml_trainer PRIVATE ${MPI_LIBRARIES})

# Optional: Find CUDA if you plan to integrate GPU acceleration
# find_package(CUDA REQUIRED)
# if (CUDA_FOUND)
#    message(STATUS "CUDA found: ${CUDA_TOOLKIT_ROOT_DIR}")
#    # Add CUDA specific compilation flags and link libraries
#    # CUDA_ADD_EXECUTABLE(distributed_ml_trainer_cuda src/main_cuda.cu)
#    # TARGET_LINK_LIBRARIES(distributed_ml_trainer_cuda PRIVATE ${CUDA_LIBRARIES})
# else()
#    message(STATUS "CUDA not found. Building without GPU support.")
# endif()

# Simulated change for commit 1 on 2023-01-04 17:48:33

# Simulated change for commit 3 on 2023-01-05 09:24:10

# Simulated change for commit 6 on 2023-01-11 17:46:09

# Simulated change for commit 9 on 2023-01-16 12:31:48

# Simulated change for commit 10 on 2023-01-17 17:21:54
