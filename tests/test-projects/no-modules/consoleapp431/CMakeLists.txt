# This file was generated by FRUT's Jucer2CMake from "consoleapp431.jucer"

cmake_minimum_required(VERSION 3.4)

project("consoleapp431")


list(APPEND CMAKE_MODULE_PATH "${CMAKE_CURRENT_LIST_DIR}/../../../../cmake")
include(Reprojucer)


set(consoleapp431_jucer_FILE
  "${CMAKE_CURRENT_LIST_DIR}/consoleapp431.jucer"
)


jucer_project_begin(
  JUCER_VERSION "4.3.1"
  PROJECT_FILE "${consoleapp431_jucer_FILE}"
  PROJECT_ID "wlNiAx"
)

jucer_project_settings(
  PROJECT_NAME "consoleapp431"
  PROJECT_VERSION "1.0.0"
  PROJECT_TYPE "Console Application"
  BUNDLE_IDENTIFIER "com.yourcompany.consoleapp431"
  INCLUDE_BINARYDATA ON
)

jucer_project_files("consoleapp431/Source"
# Compile   Xcode     Binary    File
#           Resource  Resource
  x         .         .         "Source/foo.cpp"
)

jucer_export_target(
  "Xcode (MacOSX)"
)

jucer_export_target_configuration(
  "Xcode (MacOSX)"
  NAME "Debug"
  DEBUG_MODE ON
  BINARY_NAME "consoleapp431"
  OPTIMISATION "-O0 (no optimisation)"
)

jucer_export_target_configuration(
  "Xcode (MacOSX)"
  NAME "Release"
  DEBUG_MODE OFF
  BINARY_NAME "consoleapp431"
  OPTIMISATION "-O3 (fastest with safe optimisations)"
)

jucer_export_target(
  "Visual Studio 2015"
)

jucer_export_target_configuration(
  "Visual Studio 2015"
  NAME "Debug"
  DEBUG_MODE ON
  BINARY_NAME "consoleapp431"
  OPTIMISATION "No optimisation"
  WARNING_LEVEL "High"
  GENERATE_MANIFEST ON
  # ARCHITECTURE "32-bit"
)

jucer_export_target_configuration(
  "Visual Studio 2015"
  NAME "Release"
  DEBUG_MODE OFF
  BINARY_NAME "consoleapp431"
  OPTIMISATION "Maximise speed"
  WARNING_LEVEL "High"
  GENERATE_MANIFEST ON
  # ARCHITECTURE "32-bit"
)

jucer_export_target(
  "Visual Studio 2013"
)

jucer_export_target_configuration(
  "Visual Studio 2013"
  NAME "Debug"
  DEBUG_MODE ON
  BINARY_NAME "consoleapp431"
  OPTIMISATION "No optimisation"
  WARNING_LEVEL "High"
  GENERATE_MANIFEST ON
  # ARCHITECTURE "32-bit"
)

jucer_export_target_configuration(
  "Visual Studio 2013"
  NAME "Release"
  DEBUG_MODE OFF
  BINARY_NAME "consoleapp431"
  OPTIMISATION "Maximise speed"
  WARNING_LEVEL "High"
  GENERATE_MANIFEST ON
  # ARCHITECTURE "32-bit"
)

jucer_export_target(
  "Linux Makefile"
)

jucer_export_target_configuration(
  "Linux Makefile"
  NAME "Debug"
  DEBUG_MODE ON
  BINARY_NAME "consoleapp431"
  OPTIMISATION "-O0 (no optimisation)"
)

jucer_export_target_configuration(
  "Linux Makefile"
  NAME "Release"
  DEBUG_MODE OFF
  BINARY_NAME "consoleapp431"
  OPTIMISATION "-O3 (fastest with safe optimisations)"
)

jucer_export_target(
  "Code::Blocks (Windows)"
)

jucer_export_target_configuration(
  "Code::Blocks (Windows)"
  NAME "Debug"
  DEBUG_MODE ON
  BINARY_NAME "consoleapp431"
  OPTIMISATION "-O0 (no optimisation)"
)

jucer_export_target_configuration(
  "Code::Blocks (Windows)"
  NAME "Release"
  DEBUG_MODE OFF
  BINARY_NAME "consoleapp431"
  OPTIMISATION "-O3 (fastest with safe optimisations)"
)

jucer_export_target(
  "Code::Blocks (Linux)"
)

jucer_export_target_configuration(
  "Code::Blocks (Linux)"
  NAME "Debug"
  DEBUG_MODE ON
  BINARY_NAME "consoleapp431"
  OPTIMISATION "-O0 (no optimisation)"
)

jucer_export_target_configuration(
  "Code::Blocks (Linux)"
  NAME "Release"
  DEBUG_MODE OFF
  BINARY_NAME "consoleapp431"
  OPTIMISATION "-O3 (fastest with safe optimisations)"
)

jucer_project_end()
