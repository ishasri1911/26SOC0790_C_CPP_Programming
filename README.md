# 26SOC0790 C/C++ Programming

Coursework and practice programs for C and C++ programming.

## Build

Requirements:

- CMake 3.20 or newer
- A C and C++ compiler

Configure and build from the repository root:

```text
cmake -S . -B build
cmake --build build
```

Run the sample program:

```text
build\\26soc0790
```

On Windows with a multi-configuration generator, the executable is usually under `build\\Debug\\26soc0790.exe`.

## Layout

- `src/` - application source files
- `include/` - project headers
- `tests/` - tests and test data
- `build/` - generated build files; ignored by Git
