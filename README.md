# quick-cpp
Simple template for C/C++ project. Made for developing in VS Code Dev Container Docker environment.

## Setup
| Area | Tool |
| --- | --- |
| Environment | Docker |
| Version control | Git |
| Compiler | GCC |
| Build system | CMake |
| Unit tests | GTest |
| Formatter* | clang-format |
| Scripting | Python |

*pre-commit hook configured to run `clang-format`

## Structure
| Folder/file | Purpose |
| --- | --- |
| `.devcontainer `| VS Code devcontainer config, dev env described here |
| `build` | build artifacts |
| `cmake` | place your CMake modules here |
| `examples` | application examples |
| `src` | application sources |
| `test` | all tests should be here |
| `test/mock` | here should be mocks for application modules |
| `.clang-format` | project-wide format config, feel free to adjust/extend |
| `.gitignore` | Git ignore config |
| `.pre-commit-config.yaml` | Pyton `pre-commit` tool config for Git pre-commit hooks |
| `CMakeLists.txt` | root CMake file, build starts here |
