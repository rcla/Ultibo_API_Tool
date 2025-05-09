<h1 align="center">
    <img align="center" src="img/Extens.png" width="auto" alt="UltiboAPI">
  <br>
	<br>
	Ultibo API Tool for VSCode
</h1>
<p align="center"><strong>New and Build Project for Ultibo API.</strong></p>



## Installation
[The complete installation guide]([https://en.wikipedia.org/wiki/De_Stijl](https://github.com/rcla/Ultibo_API_Tool/blob/master/INSTALLATION.md))


## Usage

Open the `Command Palette` use the  `Ctrl+Shift+P` keyboard shortcut. 
And type `Ultibo API Tool`

<p align="center">
    <img align="center" src="img/Command-palette.png" width="auto" alt="Type Ultibo API Tool">
</p>

Or directly select the icon in the Activity Bar
<p align="center">
    <img align="center" src="img/OpenTool.png" width="auto" alt="Open Ultibo API Tool">
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
|8.    | Go to the `.code-workspace` file and click `Open Workspace` to open your new project.|

<p align="center">
    <img align="center" src="img/OpenWorkspaceButton.png" width="auto" alt="Open Workspace">
</p>

> Note: If the folder already contains files, these will be overwriters!.  
Also if `Main file name` is empty or `path` is undefined, no files are generated and warning messages will be displayed.

## Files generated
<p align="center">
    <img align="center" src="img/samplen3.gif" width="auto" alt="Sample">
</p>

For example, if `Main file name` is `"test1"`, then the following files will be generated:

|  File           | Description|
|:--------------------|:-------------|
| initunit.pas    | This unit is included first in the project file it can be used to update default settings used during boot.|
| Makefile |The `make` utility requires this file to define the build rules for a project, primarily for compiling and linking source code.  |
| test1.c    | Contains the main program in C or C++ language.|
| test1.code-workspace | File that automatically restores all workspace settings used by VScode.|
| test1project.lpi     | Lazarus Project Information file (contains project-specific settings) .|
| test1project.lpr | Lazarus Program file, contains Pascal source of main program.|


## Additional information

- Official forum and solution to doubts from [Forum Ultibo](https://ultibo.org/forum/index.php).
- Ultibo API examples and information [Ultibo API](https://github.com/ultibohub/API).
