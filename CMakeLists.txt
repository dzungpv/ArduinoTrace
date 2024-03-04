cmake_minimum_required(VERSION 3.5)
#project(ArduinoTrace)
#enable_testing()

#include_directories(.)

#add_subdirectory(extras/test)

set(COMPONENT_ADD_INCLUDEDIRS
    "."
)

set(COMPONENT_REQUIRES
    "arduino-esp32"
)

register_component()
