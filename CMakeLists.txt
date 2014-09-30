cmake_minimum_required(VERSION 2.8.3)
project(list_pcap_devices)

set(CMAKE_MODULE_PATH "${PROJECT_SOURCE_DIR}/cmake")
find_package(WinPcap REQUIRED)

include_directories(${WINPCAP_INCLUDE_DIRS})

add_executable(list_pcap_devices src/main.cpp)
target_link_libraries(list_pcap_devices ${WINPCAP_LIBRARIES})