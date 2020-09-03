# Coding Pack for Python

This repository is for providing feedback and documentation on the Coding Pack for Python installer. You can use this repository to report issues encountered with our installer.

If you encounter an issue with any of the components that we install, please report an issue on their respective repositories:

- [Visual Studio Code](https://github.com/microsoft/vscode)
- [Python extension for Visual Studio Code](https://github.com/microsoft/vscode-python)
- [Pylance extension for Visual Studio Code](https://github.com/microsoft/pylance-release)
- [Gather extension for Visual Studio Code](https://github.com/microsoft/vscode-gather)

## Getting started

With the Coding Pack for Python it’s easy to get started. 

1.	[Download](https://aka.ms/coding-pack-for-python-win) and run the Coding Pack for Python installer.

    <b>Note</b>: The installer only supports installation on 64-bit Windows.


1. Once the installer launches, review and accept the License Agreement. Then select <b>Install</b>.

1.	After installation completes, select <b>Next</b>.

    <b>Note</b>: If you select Cancel before installation completes, you will need to manually remove and uninstall any components that have already been installed.

1. Launch Visual Studio Code and start coding!

This project is intended to be used for educational scenarios, and 
is currently in **public preview**. If you try it out, please let us know what you think using our [survey](https://aka.ms/coding-pack-for-python-survey)!

## What’s installed by the Coding Pack for Python

The Coding Pack for Python installs the key components you need to use Visual Studio Code for Python development. Specifically, it installs:

- Visual Studio Code
- 	The Python, Pylance, and Gather VS Code extensions
- 	The Python runtime (CPython 3.8.5)
- 	Useful Python packages
    - 	jupyter
    - 	numpy
    - 	sklearn
    - 	pandas
    - 	Matplotlib

Along with the tools and packages necessary for Python development, the Coding Pack also configures common user settings and PowerShell. This includes Python extension settings, such as the default interpreter and language server, as well as execution policies to allow for virtual environment activation in the terminal.

<b>Note</b>: If there was an existing version of Visual Studio Code installed on your machine, your settings.json will not be overwritten and you’ll need to configure Python settings yourself.
