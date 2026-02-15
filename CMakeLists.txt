cmake_minimum_required(VERSION 3.29)
project(HFT_Engine)

set(CMAKE_CXX_STANDARD 20)

add_executable(HFT_Engine main.cpp
        order_book/order_book.cpp
        order_book/matching_engine.cpp
        order_book/types.h
        execution_engine/execution_manager.cpp
        execution_engine/latency_profiler.cpp)
