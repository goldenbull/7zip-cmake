# 7zip-cmake

build 7zip with cmake

- `7z-src` folder contains original 7z2501-src
- `CMakeLists.txt` is created based on `7z-src/CPP/7zip/Bundles/Format7zF/makefile.gcc`, which contains the full functionality of 7z
- additional `custom.cpp/h/def` is provided to contain custom logics, for example, expose the 7z functions without COM
