## Usage Instructions

Compile the project using the compiler of your choice, using the included build and run scripts for your operating system.
You'll find the build files in the default CMake folder, PROJECT_ROOT/build/x64-*/

You'll need CMake 3.1, make and if you're on Linux, the X11 libraries (and pthread, but that should be fine).
Make sure CMake and make are in your PATH, if not, add them, or change the scripts.
If you're using Microsoft's Visual Studio and building a project for that, you may encounter issues launching the application. Make sure
your startup project is set correctly if this is the case, and not accidentally set to one of the projects CMake creates.

To adjust the size of the image, or the scale on the y and x axes, edit the constants in main.cpp and recompile.
