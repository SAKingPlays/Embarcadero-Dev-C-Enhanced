Embarcadero Dev-C++ Enhanced
Overview
Embarcadero Dev-C++ Enhanced is an open-source project that extends the classic Dev-C++ IDE with modern features, improved performance, and enhanced support for C++ development. This repository provides a customized version of Dev-C++ with additional plugins, themes, and tools to streamline development workflows for C++ developers.
Features

Modernized UI: Updated interface with dark/light theme support for better usability.
Plugin Ecosystem: Support for new plugins, including code formatters, debuggers, and linters.
Cross-Platform Compilation: Enhanced support for cross-compiling applications for Windows, macOS, and Linux.
Integrated Tools: Built-in support for Git, CMake, and modern C++ standards (C++17, C++20, C++23).
Performance Optimizations: Faster compilation and reduced memory usage compared to the original Dev-C++.

Installation

Prerequisites:

Windows 10 or later (64-bit recommended).
MinGW or TDM-GCC compiler (included in the installer).
At least 4GB of RAM and 500MB of free disk space.


Steps:

Download the latest release from the Releases section.
Run the installer (DevCppEnhancedSetup.exe) and follow the on-screen instructions.
Optionally, configure your preferred compiler and plugins via the Settings menu.


Verify Installation:
devcpp-enhanced --version

This should display the installed version, e.g., Embarcadero Dev-C++ Enhanced v7.0.0.


Usage

Launch the IDE using the desktop shortcut or by running devcpp-enhanced.exe.
Create a new project: File > New > Project > C++ Project.
Example code to test the setup:#include <iostream>
int main() {
    std::cout << "Hello, Embarcadero Dev-C++ Enhanced!" << std::endl;
    return 0;
}


Compile and run using F9 or the Execute > Compile & Run menu.

Contributing
We welcome contributions! To contribute:

Fork this repository.
Create a new branch: git checkout -b feature/your-feature-name.
Make your changes and commit: git commit -m "Add your feature".
Push to your branch: git push origin feature/your-feature-name.
Open a pull request with a detailed description of your changes.

For more details, see CONTRIBUTING.md.
Releases
Check the Releases page for the latest version and release notes.
License
This project is licensed under the MIT License. See LICENSE.txt for details.
Contact

Issues: Report bugs or suggest features on the Issues page.
Email: devcpp-enhanced@embarcadero.com
Community: Join our Discord server for discussions and support.
