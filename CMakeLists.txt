cmake_minimum_required(VERSION 3.5)

project(Examples_10)

SET(CMAKE_CXX_COMPILER /usr/local/Cellar/gcc/HEAD-f2787da/bin/c++-HEAD)


add_executable(array array.cpp)
set_target_properties(array PROPERTIES
        CXX_STANDARD 14
        CXX_STANDARD_REQUIRED ON
        )

add_executable(deque deque.cpp)
set_target_properties(deque PROPERTIES
        CXX_STANDARD 14
        CXX_STANDARD_REQUIRED ON
        )

add_executable(stack stack.cpp)
set_target_properties(stack PROPERTIES
        CXX_STANDARD 14
        CXX_STANDARD_REQUIRED ON
        )

add_executable(queue queue.cpp)
set_target_properties(queue PROPERTIES
        CXX_STANDARD 14
        CXX_STANDARD_REQUIRED ON
        )

add_executable(forward_list forward_list.cpp)
set_target_properties(forward_list PROPERTIES
        CXX_STANDARD 14
        CXX_STANDARD_REQUIRED ON
        )

add_executable(list list.cpp)
set_target_properties(list PROPERTIES
        CXX_STANDARD 14
        CXX_STANDARD_REQUIRED ON
        )

add_executable(set set.cpp)
set_target_properties(set PROPERTIES
        CXX_STANDARD 14
        CXX_STANDARD_REQUIRED ON
        )

add_executable(map map.cpp)
set_target_properties(map PROPERTIES
        CXX_STANDARD 14
        CXX_STANDARD_REQUIRED ON
        )

add_executable(multiset multiset.cpp)
set_target_properties(multiset PROPERTIES
        CXX_STANDARD 14
        CXX_STANDARD_REQUIRED ON
        )

add_executable(unordered_set unordered_set.cpp)
set_target_properties(unordered_set PROPERTIES
        CXX_STANDARD 14
        CXX_STANDARD_REQUIRED ON
        )

add_executable(operator_new operator_new.cpp)
set_target_properties(operator_new PROPERTIES
        CXX_STANDARD 14
        CXX_STANDARD_REQUIRED ON
        )

add_executable(allocator allocator.cpp)
set_target_properties(allocator PROPERTIES
        CXX_STANDARD 14
        CXX_STANDARD_REQUIRED ON
        )

add_executable(simple_allocator simple_allocator.cpp)
set_target_properties(simple_allocator PROPERTIES
        CXX_STANDARD 14
        CXX_STANDARD_REQUIRED ON
        )