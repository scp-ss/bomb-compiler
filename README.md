# BOMB Compiler

## Overview
[BOMB](https://github.com/scp-ss/bomb-compiler) is a custom language compiler written in C++. This project aims to provide cross-platform support for both Linux and Windows, including WSL.

## Getting Started

### Prerequisites
- **Linux/WSL**: CMake, GCC/G++
- **Windows**: CMake, Visual Studio or MinGW

### Installation

#### Linux/WSL

1. Clone the repository:
``` 
git clone https://github.com/scp-ss/bomb-compiler.git 
cd BOMB
```

3. Create a build directory and navigate into it:

``` mkdir build cd build Configure the project with ```

4. CMake:

``` cmake .. ```

5. Build the project:

``` cmake --build```

6. Run the compiler:

``` ./BOMB```


#### Windows 

1. Clone the repository:

``` git clone https://github.com/yourusername/BOMB.git```<br>
``` cd BOMB```

2. Create a build directory and navigate into it:

``` mkdir build cd build ```

3. Configure the project with CMake:


For Visual Studio:

```cmake -G "Visual Studio 16 2019" ..```
<br>

For MinGW:

``` cmake -G "MinGW Makefiles" . ```

4. Build the project:

```cmake --build ```

5. Run the compiler:

 ```.\Debug\BOMB.exe Contributing```
 
