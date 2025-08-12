cmake_minimum_required( VERSION 3.31 )
project ( webp-imageio )

set(CMAKE_POSITION_INDEPENDENT_CODE ON)

add_subdirectory( "libwebp" )
add_subdirectory( "src/main/c" )
