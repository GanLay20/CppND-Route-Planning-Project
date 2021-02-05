
README.md
Route Planning Project

This repo contains the starter code for the Route Planning project.

Cloning

When cloning this project, be sure to use the --recurse-submodules flag. Using HTTPS:

git clone https://github.com/udacity/CppND-Route-Planning-Project.git --recurse-submodules

or with SSH:

git clone git@github.com:udacity/CppND-Route-Planning-Project.git --recurse-submodules

Dependencies for Running Locally

    cmake >= 3.11.3
        All OSes: click here for installation instructions
    make >= 4.1 (Linux, Mac), 3.81 (Windows)
        Linux: make is installed by default on most Linux distros
        Mac: install Xcode command line tools to get make
        Windows: Click here for installation instructions
    gcc/g++ >= 7.4.0
        Linux: gcc / g++ is installed by default on most Linux distros
        Mac: same instructions as make - install Xcode command line tools
        Windows: recommend using MinGW
    IO2D
        Installation instructions for all operating systems can be found here
        This library must be built in a place where CMake find_package will be able to find it

Compiling and Running
Compiling

To compile the project, first, create a build directory and change to that directory:

mkdir build && cd build

From within the build directory, then run cmake and make as follows:

cmake ..
make

Running

The executable will be placed in the build directory. From within build, you can run the project as follows:

./OSM_A_star_search

Or to specify a map file:

./OSM_A_star_search -f ../<your_osm_file.osm>

Testing

The testing executable is also placed in the build directory. From within build, you can run the unit tests as follows:

./test
