# Building

## Reporting issues


[Getting Help](https://drake.mit.edu/getting_help.html)

The following information will be useful when reporting:

    - Operating system (Ubuntu 18.04, macOS Catalina)
    - Language (C++, Python)
        - C++ compiler (GCC 7.5.0, GCC 9.3.0, Clang 6.0.0)
        - Python version (Python 3.6.7)
        - Python distribution (apt, homebrew)
    - If building from source:
        - Build system (Bazel, CMake)
            - Bazel version (`which bazel; bazel version`)
            - Bazel C++ compiler (`bazel run @drake//common:print_host_settings`)
            - CMake version (`which cmake; cmake --version`)
            - CMake C++ compiler (`cmake -LA <path_to_source_dir> | grep 'CMAKE_.*_COMPILER'`)
        - Git revision (git rev-parse --short HEAD)
        - Building Drake vs. downstream project (like drake_bazel_external, drake_cmake_external)

