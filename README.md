[![Build Status](https://travis-ci.org/berkeley-abc/abc-library-cmake.svg?branch=master)](https://travis-ci.org/berkeley-abc/abc-library-cmake)

# An example of using ABC as a Library using CMake

## Instructions

1. Clone this project.

```
git clone https://github.com/berkeley-abc/abc-library-cmake.git
```

2. Clone ABC inside this project directory.

```
cd abc-library-cmake
git clone https://github.com/berkeley-abc/abc.git
```

3. Create a build directory

```
mkdir build
cd build
```

4. Configure the CMake project

```
cmake ..
```

4. Build

```
make
```

5. Run the program. For convenience, it was added as a test:

```
make test
```
