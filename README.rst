OpenCV-CUDA-Xcode-Template
=====================

Note: Original credit for the OpenCV-Xcode-Template work to @FlorianDenis

A Xcode template for a CLI project using OpenCV with CUDA on OS X

Before installing OpenCV, install the CUDA runtime.
The prefered method for installing OpenCV is [homebrew](http://brew.sh)
Simply `brew install opencv --with-cuda`. You might need to `brew tap homebrew/science` beforehand.
As of 5-2014, the most recent version of cmake creates a malformed libopencv_highgui.dylib.

Simply copy the `.xctemplate` into (create any non-existent sub folder)

- `~/Library/Developer/Xcode/Templates/Application/Project Templates/OpenCV/` for Xcode 5
- `~/Library/Developer/Xcode/Templates/Project Templates/OpenCV/` for Xcode 4

Working installation configuration
==================================

- CUDA runtime 6.0.x
- cmake 2.8.11.2 (not 2.8.12.2)
- opencv 2.8.4 via `brew install opencv --with-cuda`
