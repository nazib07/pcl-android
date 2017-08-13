CMake build scripts for cross compiling PCL 1.8.1 and its dependencies for Android.

## Requirements

* Android NDK, Revision 15b
* Android SDK (unsure about specific version)

# Building for Android

    $ mkdir build && cd build
    $ cmake -DBUILD_IOS_DEVICE:BOOL="OFF" ../
    $ export ANDROID_NDK=${PATH_TO_ANDROID_NDK_R15b}
    $ make
    
    replace pcl and boost
    $make
pre-compiled library: https://sourceforge.net/projects/pcl-android/
