# Offline C++ Compiler

An **offline C++ compiler** that runs entirely in the browser using **WebAssembly (WASM)**. This project provides a lightweight and fast environment for writing, compiling, and running C++ code without requiring any additional installations.

## Features
- 📝 **Code Editor**: A syntax-highlighted editor similar to Visual Studio Code.
- ⚡ **Fast Compilation & Execution**: Uses WebAssembly to compile and run C++ locally.
- 🖥️ **Output Console**: Displays program output, including `std::cout` and `std::cin` interactions.
- 📂 **File Management**: Supports creating, saving, and opening C++ files.
- 🔄 **Command Terminal**: Allows user interaction with running code.
- 🎨 **Modern UI**: Responsive design with dark mode support.
- ⏳ **WASM Loading Simulation**: Displays a loading indicator when initializing the compiler.

## How It Works
1. Write your **C++ code** in the built-in editor.
2. Click **"Compile"** to check for errors.
3. Click **"Run"** to execute the program and view the output.
4. If the code uses `cin >>`, user input will be processed dynamically.
5. Use **"Stop"** to terminate execution and **"Clear Output"** to reset the console.

## Technologies Used
- **HTML, CSS, JavaScript** – Frontend UI and interactions.
- **WebAssembly (WASM)** – Enables C++ code execution within the browser.
- **Firebase** (Future feature) – Cloud storage for saving projects.

## Use Cases
- 👨‍💻 **Students & Beginners**: Practice C++ coding without setting up a local environment.
- 🚀 **Developers on the Go**: Quickly test and debug C++ code anywhere.
- 🎯 **Quick Prototyping**: Run small C++ programs instantly in the browser.

## Getting Started
1. Clone the repository:
   ```sh
   git clone https://github.com/georgmichelle/offline-c-compiler.git
