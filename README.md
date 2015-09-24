# APUE with CMake

This repository contains example code in the book Advanced Programming in Unix Environment.

For ease of adaptation, I've reorganized examples into chapters so you can easily try out each of them.

I also use cmake instead of gnu autotools because cmake is more easily modified and integrated into Clion or Netbeans tools.

# Get Started.

```bash
# checkout the source
git clone https://github.com/zhaopuming/apue-cmake
cd apue-cmake

mkdir build
cd build

cmake ..
make
```

Note:
In each chapter's subdirectory, you can see a README.md, 
   there the code sample names are listed to help you find which code is which example.
