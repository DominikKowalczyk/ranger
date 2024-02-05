# Fusion  360 Add-On Project File Structure

This document outlines the file structure for the Fusion  360 add-on project and explains the reasoning behind each component. The file structure is designed to ensure that the project is organized, maintainable, and scalable, following best practices in modern C++ development and Fusion  360 add-in development guidelines.

## Root Directory
- `src/`: Contains the source code for the add-in.
- `include/`: Houses the header files for the add-in.
- `lib/`: Stores third-party libraries, if any.
- `res/`: Serves as the directory for resources such as images and icons.
- `test/`: Contains unit tests for the add-in.
- `doc/`: Includes documentation files.
- `.gitignore`: Specifies files and directories to be ignored by Git.
- `CMakeLists.txt`: Defines the build configuration for CMake.
- `manifest.json`: The manifest file for the Fusion  360 add-on, containing metadata.

## Source Code Directory (`src/`)
The `src/` directory is where the primary code for the add-in is stored. Each `.cpp` file corresponds to a specific part of the add-in's functionality, promoting modularity and separation of concerns.

## Header Files Directory (`include/`)
Header files are placed in the `include/` directory to keep the source code organized and to allow for easy inclusion in other parts of the project or in external projects that may depend on this add-on.

## Third-Party Libraries Directory (`lib/`)
If the add-on uses any third-party libraries, they are placed in the `lib/` directory. This separation helps to avoid cluttering the main codebase with external dependencies.

## Resources Directory (`res/`)
The `res/` directory holds all static resources, such as images, icons, and other assets, that are used by the add-in.

## Unit Tests Directory (`test/`)
Unit tests are stored in the `test/` directory to ensure that each part of the add-in behaves as expected. This practice promotes the development of reliable and maintainable code.

## Documentation Directory (`doc/`)
The `doc/` directory contains all documentation files for the project. This includes the README, API reference, and any other explanatory text that helps users and developers understand the project.

## .gitignore
The `.gitignore` file is used to tell Git which files or directories to ignore in the project. This is important for excluding build artifacts, temporary files, and personal IDE settings that should not be version controlled.

## CMakeLists.txt
The `CMakeLists.txt` file defines the build configuration for the project. It specifies the compiler, linker options, and other settings required to compile the add-in.

## manifest.json
The `manifest.json` file contains the metadata for the Fusion  360 add-on. It includes information such as the add-in ID, version, supported operating systems, and whether it runs on startup.

By following this file structure and explaining the rationale behind it, the project becomes easier to navigate and understand. It also aligns with industry standards for C++ projects and Fusion  360 add-in development, ensuring that the project is professional and maintainable [0].```
