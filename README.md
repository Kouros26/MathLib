# MathLib
C++ header-only math library made for GameDev

## Setup (using CMake)

* ```FetchContent_Declare(LibMaths GIT_REPOSITORY https://github.com/Angel-2180/LibMaths.git)```
* ```FetchContent_MakeAvailable(LibMaths)```
* ```target_include_directories(${your target} PRIVATE ${LIBMATHS_INCLUDE_DIR})```
