cmake_minimum_required(VERSION 3.22)

add_subdirectory(Lib)
message(STATUS "STATUS - Lib: Built as '${Library_LIB} with includes at '${Library_INCLUDE}'")

set(
    GLOBAL_LIB 
    ${Library_LIB}
)

set(
    GLOBAL_INC
    ${Library_INC}
)

add_subdirectory(Exec)

message(STATUS "STATUS - Exec: Built as '${Executable_BIN}'")
