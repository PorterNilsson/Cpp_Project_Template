# C++ Project Template
---

Welcome to a basic C++ template for your projects! 

This template has several features including isolating the build files from the source files, placing miscellaneous files pertaining to configuring and preparing the project in the root directory, and providing a simple CMake template for building on different platforms.

Here's an overview of the file structure:

```
Cpp_Project_Template/
├── source/
│   └── main.cpp
├── build/
├── .gitignore
├── CMakeLists.txt
├── README.md
└── LICENSE.txt
```

To use this repository, GitHub has a feature which allows creating a new repository directly based on this project's file structure. Simply follow their documentation [here](https://docs.github.com/en/repositories/creating-and-managing-repositories/creating-a-repository-from-a-template#creating-a-repository-from-a-template).

In Visual Studio Code, first pull the repository down to your machine after creating a new repository on GitHub. Make sure to use the URL associated with your repository.

```bash
# EXAMPLE URL ONLY
git clone https://github.com/your-username/new-repository.git
```

Next, modify the project name on line two of `CMakeLists.txt` to reflect your project name.

```cmake
project("YOUR PROJECT NAME HERE" VERSION 0.1.0 LANGUAGES C CXX)
```

Finally, make sure you have the CMake extension installed in Visual Studio Code and on your machine. If those are set up, use the build, run, and debug options on the bottom status bar to develop your project!
