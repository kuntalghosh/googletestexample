## googletestexample

This repository contains the basic usage of ([Google Test](https://github.com/google/googletest)), Google's c++ testing framework. To build this project, you need CMake installed in your system. You can download it for free from here <http://www.cmake.org/>.


As per the Google Test ([documentation](https://github.com/google/googletest/blob/master/googletest/README.md)), a more robust and flexible way to build the gtest project as part of the build. This reduces the effort by a significant amount. It is always recommended to build the project in a different directory from the source. Followings are the instructions to build the project.

    mkdir build       # Create a directory to hold the build output.
    cd build
    cmake ..
	make all

Please note that the above build folder should be added in .gitignore file so that we don't accidentally add the contents of this folder in the git commit.

After building the tests, you can run the tests by using the following commands:

	make test

You can also perform the tests by executing the following command:

	make check
