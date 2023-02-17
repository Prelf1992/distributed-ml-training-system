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

# Simulated change for commit 12 on 2023-01-23 09:04:40

# Simulated change for commit 13 on 2023-01-23 09:41:47

# Simulated change for commit 15 on 2023-01-24 15:34:35

# Simulated change for commit 20 on 2023-01-30 15:06:47

# Simulated change for commit 24 on 2023-02-01 15:22:24

# Simulated change for commit 25 on 2023-02-02 11:01:40

# Simulated change for commit 26 on 2023-02-06 17:28:21

# Simulated change for commit 28 on 2023-02-06 13:32:19

# Simulated change for commit 29 on 2023-02-07 16:44:30

# Simulated change for commit 30 on 2023-02-07 15:27:02

# Simulated change for commit 31 on 2023-02-07 11:12:23

# Simulated change for commit 33 on 2023-02-13 17:01:54

# Simulated change for commit 34 on 2023-02-14 10:20:45

# Simulated change for commit 36 on 2023-02-15 09:00:40

# Simulated change for commit 38 on 2023-02-17 16:15:49
