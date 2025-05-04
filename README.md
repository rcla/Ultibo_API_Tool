<h1 align="center">
    <img align="center" src="img/main.png" width="auto" alt="UltiboAPI">
  <br>
	<br>
	Ultibo API Tool for VSCode
</h1>
<p align="center"><strong>Generating files for an Ultibo API project.</strong></p>



## Installation

Open the Extensions view by selecting the Extensions icon in the Activity Bar, or use the `Ctrl+Shift+X` keyboard shortcut.

Select the "three dots" button in the top right corner. And choose the `Install from VSIX...` option.

<p align="center">
    <img align="center" src="img/Install-from-VSIX.png" width="auto" alt="Install from VSIX">
</p>

If you try to install this extension in restricted mode, you will be prompted to trust the workspace or simply install the extension.

<p align="center">
    <img align="center" src="img/workspace-trust-install-extension.png" width="auto" alt="Install Trust">
</p>

> Note: You must select `Trus Workspace & Install`, otherwise the extension will not work.

## Usage

Open the `Command Palette` use the  `Ctrl+Shift+P` keyboard shortcut. 
And type `Ultibo API Tool`

<p align="center">
    <img align="center" src="img/Command-palette.png" width="auto" alt="Type Ultibo API Tool">
</p>

These are the steps you must follow to generate the files.

|            | STEP |
|:--------------------|:-------------|
|1.    | Close any workspaces or folders.|
|2.    | Create an empty folder and open it.|
|3.    | Verify that the `path` is from the created folder.|
|4.    | Enter the `Main file name`.|
|5.    | Click `Generate files`.|
|6.    | Edit each file to your needs.|
|7.    | Go to the Files Menu and `Save All`.|

> Note: If the folder already contains files, these will be overwriters!.  
Also if `Main file name` is empty or `path` is undefined, no files are generated and warning messages will be displayed.

## Files generated

For example, if `Main file name` is `"test1"`, then the following files will be generated:

|  File           | Description|
|:--------------------|:-------------|
| Makefile |The `make` utility requires this file to define the build rules for a project, primarily for compiling and linking source code.  |
| test1.c    | Contains the main program in C or C++ language.|
| test1.code-workspace | File that automatically restores all workspace settings used by VScode.|
| test1project.lpi     | Lazarus Project Information file (contains project-specific settings) .|
| test1project.lpr | Lazarus Program file, contains Pascal source of main program.|

<p align="center">
    <img align="center" src="img/sample.gif" width="auto" alt="Sample">
</p>



## Additional information

- Official forum and solution to doubts from [Forum Ultibo](https://ultibo.org/forum/index.php).
- Ultibo API examples and information [Ultibo API](https://github.com/ultibohub/API).
