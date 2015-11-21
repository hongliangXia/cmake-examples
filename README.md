# cmake-examples
This includes some example cmake configurations which I have picked up when exploring it's usage for various projects.

These examples have been tested on Ubuntu 14.04 but should work under any Linux system that supports cmake.

## Requirements

The basic requirements for most examples are:

  * CMake
  * A c++ compiler (defaults to gcc)
  * make

The easiest way to install the above on Ubuntu is as follows

```
$ sudo apt-get install cmake
$ sudo apt-get install build-essential
```

Some specific examples may require other tools including:

  * boost
    ```
    $ sudo apt-get libboost-all-dev
    ```
  * protobuf
    ```
    $ sudo apt-get install libprotobuf-dev
    ```
  * cppcheck
    ```
    $ sudo apt-get install cppcheck
    ```
