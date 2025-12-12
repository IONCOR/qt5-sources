# Qt 5.12.12 sources for IONCOR DiagTool
## Requirements
* git
* cmake
* C++ compiler that supports at least C++11
* Python (2.7+)
## Steps for building the sources
### Step 1: Clone or download the repository
```
git clone https://github.com/IONCOR/qt5-sources.git
```
### Step 2: Extract the compressed files into target folder
### Step 3: Build

In the folder where the files were extracted, build the sources. E.g.:
```
configure -prefix %CD%\qtbase
mingw32-make
```