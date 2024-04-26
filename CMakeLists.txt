add_library(keypad INTERFACE)

target_sources(keypad INTERFACE
 ${CMAKE_CURRENT_LIST_DIR}/keypad.c
)

target_include_directories(keypad INTERFACE ${CMAKE_CURRENT_LIST_DIR})