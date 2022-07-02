# tests

 All tests for c++ applications and libraries

 ## Google tests

 We will be using [GoogleTest], Google’s C++ testing and mocking framework to 
 test all c++ applications and libraries.

 ### Installing GoogleTest

Before you can use GoogleTest, you will need to install GoogleTest on your system, 
if you haven't already done that.

1. Clone the GoogleTest repository from github
    ```
    mkdir -p ~/repos
    cd ~/repos
    git clone git@github.com:google/googletest.git 
    ```
2. Build and install GoogleTest
    ```
    mkdir -p ~/repos/googletest/build
    cd ~/repos/googletest/build
    cmake ..
    sudo make install
     ```
3. Now you can start using GoogleTest.
   1. Follow the [Quickstart: Building with CMake] tutorial on how to create a test project.
   2. Further reading, see the [GoogleTest User's Guide] for documentation. 
   Recommend is starting with the [GoogleTest Primer].

More information about building GoogleTest can be found at [googletest/README.md].


[GoogleTest]: https://google.github.io/googletest/
[GoogleTest User's Guide]: https://google.github.io/googletest/
[GoogleTest Primer]: https://google.github.io/googletest/primer.html
[googletest/README.md]: https://github.com/google/googletest/blob/main/googletest/README.md
[Quickstart: Building with CMake]: https://github.com/google/googletest/blob/main/docs/quickstart-cmake.md