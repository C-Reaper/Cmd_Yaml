## Project README

### Overview
This project is a simple C program that reads and processes configuration data from a YAML file. The program demonstrates how to parse a complex nested structure, access specific elements, and modify values in the parsed data.

### Features
- Reading a YAML configuration file.
- Parsing nested structures.
- Accessing and modifying specific elements within the YAML data.

### Project Structure
```
<Project>/
├── build/              # .exe files produced by Main.c
├── src/                # Source code directory
│   ├── Main.c          # Entry point of the program
│   └── utils.h         # Header file containing utility functions for YAML parsing
├── Makefile.linux      # Linux Build configuration
├── Makefile.windows    # Windows Build configuration
├── README.md           # This file
└── LICENCE
```

### Prerequisites
- C/C++ Compiler and Debugger (GCC, Clang)
- Make utility
- Standard development tools

## Build & Run
### Building the Project
1. Navigate to the project directory.
2. Build the project using the appropriate Makefile for your operating system.

**For Linux:**
```sh
make -f Makefile.linux all
```

**For Windows:**
```sh
make -f Makefile.windows all
```

### Executing the Program
After building the project, you can execute it using the `exe` target:
```sh
make -f Makefile.(os) exe
```

This will compile and run the program, demonstrating how to parse a YAML configuration file and access specific elements within it.