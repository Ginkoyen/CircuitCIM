cmake_minimum_required (VERSION 2.6)
project (circuitSimulationCore)

# Package configuration
find_package(PkgConfig REQUIRED)

# Targets
add_executable(circuitSimulator core.cpp)
