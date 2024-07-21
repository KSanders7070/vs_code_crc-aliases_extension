# vs_code_crc-aliases_extension
# CRC-Aliases VSCode Extension

Welcome to the CRC-Aliases Visual Studio Code extension! This extension is designed to help you work with alias files by providing syntax highlighting and other useful features.

[Extension URL](https://marketplace.visualstudio.com/items?itemName=KyleSanders.crc-aliases)  
[Hub URL](https://marketplace.visualstudio.com/manage/publishers/KyleSanders/extensions/crc-aliases/hub)

## Features

- **Custom Dot Commands**: Highlighted in **Green**.
- **Native Dot Commands**: Highlighted in **Red**.
- **Variables**: Highlighted in **Purple**.
- **Variable Arguments**: Highlighted in **Yellow**.
- **Alias Functions**: Highlighted in **Blue**.

## For Developers

### Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/KSanders7070/vs_code_crc-aliases_extension.git
2. Install the dependencies:
    ```sh
    npm install
    ```
3. Open the project in Visual Studio Code:
    ```sh
    code crc-aliases
    ```
    or... Navigate to crc-aliases directory and double click the LAUNCH_VScodeExt.bat file.
    
4. Press `F5` to open a new VSCode window with the extension loaded.
    
5. Open the test.alias file.

### Syntax Highlighting

This extension uses specific scopes to highlight various components of alias files:

- **Custom Dot Commands** (`keyword.other.alias-command`)
- **Native Dot Commands** (`keyword.control.native-dot-command`)
- **Variables** (`variable.parameter.alias-variable`)
- **Variable Arguments** (`variable.parameter.alias-argument-variable`)
- **Alias Functions** (`variable.parameter.alias-function`)

You can find these settings in the `alias.tmLanguage.json` and `Alias Color Theme.json` files.

## For Non-Coders

### Getting Started

1. Download and install [Visual Studio Code](https://code.visualstudio.com/).
2. Install the CRC-Aliases extension from the VSCode Marketplace.

### Using the Extension

- Open your alias files in Visual Studio Code.
- The extension will automatically apply color coding:
  - **Green** for custom dot commands.
  - **Red** for native dot commands.
  - **Purple** for variables.
  - **Yellow** for variable arguments.
  - **Blue** for alias functions.

This color coding helps you easily identify different parts of your alias files, making it easier to read and edit them.
