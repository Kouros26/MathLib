# MathLib
C++ header-only math library made for GameDev

## Setup (using CMake)

* ```FetchContent_Declare(LibMaths GIT_REPOSITORY https://github.com/Kouros26/MathLib.git)```
* ```FetchContent_MakeAvailable(LibMaths)```
* ```target_include_directories(${your target} PRIVATE ${LIBMATHS_INCLUDE_DIR})```
