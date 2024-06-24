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

# Simulated change for commit 126 on 2023-07-05 09:21:09

# Simulated change for commit 129 on 2023-07-10 14:55:56

# Simulated change for commit 133 on 2023-07-19 12:24:05

# Simulated change for commit 134 on 2023-07-19 12:15:12

# Simulated change for commit 137 on 2023-07-25 12:11:12

# Simulated change for commit 146 on 2023-08-02 17:35:18

# Simulated change for commit 148 on 2023-08-04 09:19:12

# Simulated change for commit 151 on 2023-08-09 12:35:45

# Simulated change for commit 155 on 2023-08-14 13:20:51

# Simulated change for commit 156 on 2023-08-15 14:58:59

# Simulated change for commit 157 on 2023-08-15 10:42:16

# Simulated change for commit 159 on 2023-08-21 12:13:28

# Simulated change for commit 162 on 2023-08-25 10:13:36

# Simulated change for commit 163 on 2023-08-28 10:25:03

# Simulated change for commit 165 on 2023-09-01 17:57:48

# Simulated change for commit 166 on 2023-09-04 09:06:56

# Simulated change for commit 167 on 2023-09-05 10:14:20

# Simulated change for commit 171 on 2023-09-11 15:22:04

# Simulated change for commit 174 on 2023-09-18 15:06:01

# Simulated change for commit 175 on 2023-09-18 16:08:32

# Simulated change for commit 176 on 2023-09-20 09:40:19

# Simulated change for commit 178 on 2023-09-21 12:10:09

# Simulated change for commit 180 on 2023-09-22 15:11:29

# Simulated change for commit 181 on 2023-09-28 10:09:52

# Simulated change for commit 182 on 2023-09-28 17:18:38

# Simulated change for commit 184 on 2023-10-02 16:34:35

# Simulated change for commit 187 on 2023-10-11 12:06:02

# Simulated change for commit 189 on 2023-10-12 13:33:49

# Simulated change for commit 190 on 2023-10-13 14:16:06

# Simulated change for commit 191 on 2023-10-16 12:17:05

# Simulated change for commit 194 on 2023-10-18 14:12:58

# Simulated change for commit 195 on 2023-10-18 09:51:54

# Simulated change for commit 197 on 2023-10-20 14:05:45

# Simulated change for commit 199 on 2023-10-20 12:42:57

# Simulated change for commit 202 on 2023-10-23 14:35:16

# Simulated change for commit 208 on 2023-10-30 16:05:14

# Simulated change for commit 209 on 2023-10-30 12:36:59

# Simulated change for commit 211 on 2023-10-31 15:54:35

# Simulated change for commit 212 on 2023-11-01 12:02:09

# Simulated change for commit 214 on 2023-11-03 15:59:35

# Simulated change for commit 215 on 2023-11-06 10:04:35

# Simulated change for commit 218 on 2023-11-08 13:56:01

# Simulated change for commit 220 on 2023-11-09 16:05:00

# Simulated change for commit 221 on 2023-11-09 16:42:51

# Simulated change for commit 222 on 2023-11-09 11:40:07

# Simulated change for commit 223 on 2023-11-10 09:34:17

# Simulated change for commit 224 on 2023-11-14 14:42:58

# Simulated change for commit 225 on 2023-11-16 14:54:47

# Simulated change for commit 228 on 2023-11-22 17:14:14

# Simulated change for commit 230 on 2023-11-23 09:22:43

# Simulated change for commit 234 on 2023-11-27 12:13:27

# Simulated change for commit 235 on 2023-11-28 09:02:36

# Simulated change for commit 244 on 2023-12-14 11:54:55

# Simulated change for commit 245 on 2023-12-15 11:07:39

# Simulated change for commit 250 on 2023-12-28 17:52:47

# Simulated change for commit 1 on 2024-01-01 10:01:57

# Simulated change for commit 2 on 2024-01-02 17:46:22

# Simulated change for commit 4 on 2024-01-04 17:20:11

# Simulated change for commit 11 on 2024-01-16 10:59:38

# Simulated change for commit 15 on 2024-01-23 16:51:05

# Simulated change for commit 16 on 2024-01-23 09:52:05

# Simulated change for commit 24 on 2024-02-08 10:55:03

# Simulated change for commit 25 on 2024-02-08 10:19:23

# Simulated change for commit 27 on 2024-02-15 09:49:38

# Simulated change for commit 28 on 2024-02-16 16:19:35

# Simulated change for commit 30 on 2024-02-23 12:08:07

# Simulated change for commit 31 on 2024-02-26 12:11:34

# Simulated change for commit 33 on 2024-02-27 15:30:20

# Simulated change for commit 36 on 2024-02-29 15:35:37

# Simulated change for commit 37 on 2024-02-29 16:26:59

# Simulated change for commit 38 on 2024-03-01 10:14:17

# Simulated change for commit 42 on 2024-03-08 17:46:47

# Simulated change for commit 43 on 2024-03-08 11:45:37

# Simulated change for commit 44 on 2024-03-11 13:06:50

# Simulated change for commit 46 on 2024-03-13 10:01:53

# Simulated change for commit 47 on 2024-03-15 10:43:31

# Simulated change for commit 48 on 2024-03-15 09:33:57

# Simulated change for commit 50 on 2024-03-22 10:59:02

# Simulated change for commit 51 on 2024-03-25 11:11:47

# Simulated change for commit 54 on 2024-03-28 14:50:22

# Simulated change for commit 57 on 2024-03-29 14:42:20

# Simulated change for commit 58 on 2024-04-03 12:17:55

# Simulated change for commit 59 on 2024-04-03 13:44:07

# Simulated change for commit 61 on 2024-04-08 09:39:49

# Simulated change for commit 63 on 2024-04-11 15:39:39

# Simulated change for commit 66 on 2024-04-15 15:04:45

# Simulated change for commit 72 on 2024-04-18 16:08:18

# Simulated change for commit 73 on 2024-04-24 14:54:03

# Simulated change for commit 76 on 2024-05-01 15:28:57

# Simulated change for commit 77 on 2024-05-03 10:13:13

# Simulated change for commit 79 on 2024-05-07 15:18:33

# Simulated change for commit 80 on 2024-05-08 12:13:09

# Simulated change for commit 81 on 2024-05-08 17:17:52

# Simulated change for commit 83 on 2024-05-09 09:07:52

# Simulated change for commit 84 on 2024-05-09 16:19:05

# Simulated change for commit 85 on 2024-05-10 15:40:30

# Simulated change for commit 89 on 2024-05-17 14:07:41

# Simulated change for commit 90 on 2024-05-21 14:56:04

# Simulated change for commit 94 on 2024-05-31 16:09:31

# Simulated change for commit 95 on 2024-06-04 17:14:26

# Simulated change for commit 96 on 2024-06-06 10:36:13

# Simulated change for commit 97 on 2024-06-06 14:31:47

# Simulated change for commit 99 on 2024-06-10 17:15:01

# Simulated change for commit 100 on 2024-06-10 13:54:42

# Simulated change for commit 103 on 2024-06-11 11:27:44

# Simulated change for commit 104 on 2024-06-11 15:23:42

# Simulated change for commit 105 on 2024-06-12 11:27:16

# Simulated change for commit 106 on 2024-06-13 15:46:23

# Simulated change for commit 107 on 2024-06-13 17:26:04

# Simulated change for commit 109 on 2024-06-14 12:58:53

# Simulated change for commit 111 on 2024-06-19 16:11:45

# Simulated change for commit 112 on 2024-06-20 17:41:51

# Simulated change for commit 115 on 2024-06-24 13:12:29

# Simulated change for commit 117 on 2024-06-24 15:49:29
