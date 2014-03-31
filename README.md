android-opencl-example
======================

NOTICE:

* Example of opencl on android. Edit from this bolg: http://developer.sonymobile.com/2013/10/29/boost-the-performance-of-your-android-app-with-opencl/

* In `bilateralKernel.cl` line:71, some device will crash when `fast_distance` is called. Therefore, I added some codes to replace this method.


COMPILE:

* Download Android NDK from: https://developer.android.com/tools/sdk/ndk/index.html

* Goto `..../OpenCL_code_example/openclexample1/`, type `$PATH_TO_NDK/ndk-build` in terminal.

* Compile android app, reference: https://developer.android.com/sdk/index.html?hl=sk


INSTALL:

* You can install this app via some IDE such as Eclipse.

* Or you can install via Android Develop Tools(adb), after download Android SDK, goto `$PATH_TO_SDK/platform-tools/`, type `./adb install ..../OpenCL_code_example/openclexample1.apk`