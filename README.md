libopencl-stub
==============

A stub OpenCL library that dynamically dlopen/dlsyms OpenCL implementations at runtime, based on environment variables. This is useful when OpenCL implementations are installed in non-standard paths (for example, POCL on Android).


Environment Variables
--------------

* LIBOPENCL_SO_PATH      -- Path to OpenCL that will be searched first
* LIBOPENCL_SO_PATH_2    -- Searched second
* LIBOPENCL_SO_PATH_3    -- Searched third
* LIBOPENCL_SO_PATH_4    -- Searched fourth

Default paths will be searched otherwise.