# FligthSQL ODBC Driver

## Overview 

ODBC driver for Apache Arrow

## Pre-requisites 
1. Visual Studio 2022 needs to be installed.
2. Install VCPKG and set `VCPKG_ROOT`.
3. CMAKE version 3.25.1

## Driver Building

Open Visual Studio Developer PowerShell or Powershell and run `./build_win32.bat` or `./build_win64.bat` to build the 32-bit and 64-bit driver correspondingly. The .bat file will build and install the dependencies and the driver.
