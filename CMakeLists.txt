cmake_minimum_required(VERSION 4.3)
project(QUEUE)

set(CMAKE_CXX_STANDARD 26)

add_library(QUEUE STATIC
        Library/QueueFiles/MAIN/Queue.h
        Library/QueueFiles/Errors/IsEmptyQueueError.h
        Library/QueueFiles/Errors/IsEmptyQueueError.cpp
)
