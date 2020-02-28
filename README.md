# OpenCL-path-tracing-tutorial-1-Getting-started
Introductory tutorial for setting up the OpenCL environment for parallel computation
by Sam Lapere, 2016 

This is a kind of "Hello World!" program for OpenCL, demonstrating how to add two arrays of numbers in parallel.

Compiling instructions (for Visual Studio on Windows)

To compile this code, it's recommended to download and install the AMD App SDK (this works for systems with GPUs or CPUs from AMD, Nvidia and Intel, even if your system doesn't have an AMD CPU or GPU installed) since Nvidia's OpenCL implementation is no longer up-to-date.

- Start an empty Console project in Visual Studio (any recent version should work, including Express and Community) and set to Release mode 
- Add the SDK include path to the "Additional Include Directories" (e.g. "C:\Program Files (x86)\AMD APP SDK\2.9-1\include") 
- In Linker > Input, add "opencl.lib" to "Additional Dependencies" and add the OpenCL lib path to "Additional Library Directories"  (e.g. "C:\Program Files (x86)\AMD APP SDK\2.9-1\lib\x86")
- Add the main.cpp file (or create a new file and paste the code) and build the project


More details on this tutorial can be found at 

http://raytracey.blogspot.co.nz/2016/11/opencl-path-tracing-tutorial-1-firing.html


