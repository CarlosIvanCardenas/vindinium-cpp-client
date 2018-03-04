vindinium-cpp-sdk
=================

A C++ starter kit for the great Vindinium AI challenge. Dependencies: boost and libcurl.

Build with CMake:

    mkdir build
    cd build
    ccmake .. #optionally config stuff
    make
    
    TO-RUN-CLIENT:
    ./client_random -k <YOUR-KEY>

If you got errors while building install the following dependencies with:

    sudo apt install libcurl4-openssl-dev libboost-all-dev
