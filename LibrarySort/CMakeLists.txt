
project(librarySort)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")


SET(SOURCES
        Main.cpp
        Source.cpp
        BiggerSource.cpp
        BiggerSource.h
        Main.h
        Source.h
        )

add_executable(librarySort ${SOURCES})

