# OpenGL C++ development using VS Code and GCC

In this repository, I share some of my knowledge regarding a completely IDE-free C++ software development environment, as well as useful libraries and tools regarding OpenGL C++ applications.

This "guide" (wouldn't actually call it a guide) was elaborated focusing on Microsoft Windows ecosystem, but one wouldn't expect many differences when setting the environment on both macOS or Linux-based OSes. Should even be easier.

## Software you'll need

### Visual Studio Code
First things first. To edit code you need a... well, editor. And Visual Studio Code is THE ONE.

You can get it right [here](https://code.visualstudio.com/).

### C/C++ Extension
Visual Studio Code has a lot of useful extensions to suit your code needs. The one that'll be particularly important for us is the C/C++ one.

The C/C++ VS Code extension brings IntelliSense capabilities to your C or C++ code, meaning you'll get nice autocomplete insights based on already written code AND also will allow you to communicate the current C and C++ files to your installed compiler.

You can grab the extension by going to [this link](https://marketplace.visualstudio.com/items?itemName=ms-vscode.cpptools) and selecting "Install" (duh).

### GNU Compiler Collection
The GCC - or as the above title states, GNU Compiler Collection - is a set of compilers for a variety of languages that I will not list here. What matters for us is that among these languages are C and C++.

Using my beloved [Scoop command-line installer](https://scoop.sh), you can just type:
    
    scoop install gcc

Same goes if, as mentioned on this document's introduction, you're on a different OS than Windows, such as macOS, with it's awesome homebrew.

If you're just needing an installer, head over to [GCC Project's official website](https://www.gnu.org/software/gcc/) and download the latest MSI.