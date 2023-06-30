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

# Simulated change for commit 39 on 2023-02-17 16:01:59

# Simulated change for commit 41 on 2023-02-22 16:01:46

# Simulated change for commit 42 on 2023-02-23 16:18:43

# Simulated change for commit 50 on 2023-03-06 17:58:32

# Simulated change for commit 51 on 2023-03-06 10:05:26

# Simulated change for commit 53 on 2023-03-10 13:51:27

# Simulated change for commit 54 on 2023-03-13 10:26:24

# Simulated change for commit 56 on 2023-03-14 15:21:59

# Simulated change for commit 58 on 2023-03-16 12:16:17

# Simulated change for commit 59 on 2023-03-16 10:10:25

# Simulated change for commit 60 on 2023-03-24 15:48:23

# Simulated change for commit 61 on 2023-03-27 15:40:40

# Simulated change for commit 62 on 2023-03-28 13:37:07

# Simulated change for commit 63 on 2023-03-29 14:12:12

# Simulated change for commit 67 on 2023-03-31 17:32:36

# Simulated change for commit 71 on 2023-04-11 11:38:02

# Simulated change for commit 74 on 2023-04-13 13:26:52

# Simulated change for commit 75 on 2023-04-17 12:35:29

# Simulated change for commit 76 on 2023-04-17 10:48:28

# Simulated change for commit 77 on 2023-04-18 12:09:13

# Simulated change for commit 78 on 2023-04-18 09:13:37

# Simulated change for commit 82 on 2023-04-24 17:25:24

# Simulated change for commit 83 on 2023-04-25 10:30:54

# Simulated change for commit 86 on 2023-04-28 14:25:29

# Simulated change for commit 89 on 2023-05-02 14:21:11

# Simulated change for commit 90 on 2023-05-03 17:58:48

# Simulated change for commit 91 on 2023-05-04 09:23:46

# Simulated change for commit 93 on 2023-05-05 10:07:12

# Simulated change for commit 94 on 2023-05-08 10:26:12

# Simulated change for commit 95 on 2023-05-09 14:42:17

# Simulated change for commit 97 on 2023-05-10 17:26:24

# Simulated change for commit 99 on 2023-05-15 13:15:15

# Simulated change for commit 100 on 2023-05-15 13:35:35

# Simulated change for commit 102 on 2023-05-17 16:25:57

# Simulated change for commit 105 on 2023-05-22 15:05:49

# Simulated change for commit 106 on 2023-05-23 13:13:05

# Simulated change for commit 108 on 2023-05-26 14:03:41

# Simulated change for commit 115 on 2023-06-02 09:20:29

# Simulated change for commit 118 on 2023-06-08 17:01:16

# Simulated change for commit 122 on 2023-06-22 17:34:19

# Simulated change for commit 123 on 2023-06-27 09:37:26

# Simulated change for commit 124 on 2023-06-30 10:17:03
