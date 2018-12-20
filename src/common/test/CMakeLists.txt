cmake_minimum_required(VERSION 3.10)

# creates the executable    
add_executable(common.unit.test
    error_code.test.cpp)

add_test(common.unit.test common.unit.test)