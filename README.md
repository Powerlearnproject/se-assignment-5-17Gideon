[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/XoLGRbHq)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15269056&assignment_repo_type=AssignmentRepo)
# SE-Assignment-5
Installation and Navigation of Visual Studio Code (VS Code)
 Instructions:
Answer the following questions based on your understanding of the installation and navigation of Visual Studio Code (VS Code). Provide detailed explanations and examples where appropriate.

 Questions:

1. Installation of VS Code:
   - Describe the steps to download and install Visual Studio Code on Windows 11 operating system. Include any prerequisites that might be needed.
Open a Web Browser:(e.g., Microsoft Edge, Google Chrome).
Navigate to the Visual Studio Code Website:Go to the official Visual Studio Code download page by entering the URL: https://code.visualstudio.com/.
Download the Installer: On the Visual Studio Code homepage, click the "Download for Windows" button. This will download the installer for the stable version of Visual Studio Code.
The file will be named something like VSCodeSetup-x.x.x.exe (the version number will vary).
Run the Installer: Once the download is complete, locate the downloaded .exe file in your browser's downloads folder.
Double-click the VSCodeSetup-x.x.x.exe file to start the installation process.
Follow the Installation Wizard:
Welcome Screen: Click Next to proceed.
License Agreement: Read the license agreement, then select I accept the agreement and click Next.
Select Destination Location: Choose the installation directory or leave it as default, then click Next.
Select Start Menu Folder: You can choose to create a Start Menu folder or disable it, then click Next.
Select Additional Tasks: Here you can select additional tasks such as creating a desktop icon, adding Open with Code action to Windows Explorer context menu, etc.
Check the options as per your preference and click Next.
Ready to Install: Click Install to begin the installation process.
Complete the Installation:
Wait for the installation to complete.
Once done, you will see a completion screen. Ensure the Launch Visual Studio Code option is checked if you want to start Visual Studio Code immediately.
Click Finish to exit the installer.
Initial Setup: Upon first launch, you might be prompted to customize your setup, install recommended extensions, or sign in to sync settings. You can choose to set these up as needed.

2. First-time Setup:
   - After installing VS Code, what initial configurations and settings should be adjusted for an optimal coding environment? Mention any important settings or extensions.
 Initial Configurations and Settings
Theme and Appearance:
Color Theme: Change the color theme by going to File > Preferences > Color Theme or pressing Ctrl+K Ctrl+T. Popular themes include "Dark+ (default dark)" and "Light+ (default light)".
Icon Theme: Adjust the file icon theme from File > Preferences > File Icon Theme.
Font and Font Size:Adjust the font family and size by adding the following to your settings.json file (File > Preferences > Settings, then click the {} icon in the top-right corner to open the JSON file)
Editor Settings:Enable line numbers and adjust other editor settings
Auto-Save:Enable auto-save by setting
Terminal Integration: Configure the integrated terminal to your preferred shell (e.g., PowerShell, Command Prompt, Git Bash)
Important Extensions
Language Support:
Python: ms-python.python
JavaScript/TypeScript: esbenp.prettier-vscode, dbaeumer.vscode-eslint
HTML/CSS: ecmel.vscode-html-css
C/C++: ms-vscode.cpptools
Java: redhat.java
Version Control:
GitLens: eamodio.gitlens - Enhances the Git capabilities within VS Code.
GitHub Pull Requests and Issues: github.vscode-pull-request-github - Integrates GitHub directly into VS Code.
Code Formatting and Linting:
Prettier: esbenp.prettier-vscode - Code formatter that supports various languages.
ESLint: dbaeumer.vscode-eslint - Integrates ESLint into VS Code.
Productivity Enhancements:
Live Server: ritwickdey.liveserver - Launch a local development server with live reload.
Path Intellisense: christian-kohler.path-intellisense - Auto-completes file paths.
Bracket Pair Colorizer: CoenraadS.bracket-pair-colorizer - Colorizes matching brackets.
TODO Highlight: wayou.vscode-todo-highlight - Highlight TODOs and FIXMEs in your code.
Snippets:
JavaScript (ES6) code snippets: xabikos.javascriptsnippets
Python Snippets: ms-python.python

3. User Interface Overview:
   - Explain the main components of the VS Code user interface. Identify and describe the purpose of the Activity Bar, Side Bar, Editor Group, and Status Bar.
  Activity Bar
Location: The vertical bar on the far left of the window.
Purpose: The Activity Bar allows you to switch between different views and provides quick access to various tools and features. The default icons typically include:
Explorer: For browsing and managing your project's files.
Search: For searching text within your project.
Source Control: For version control features, like Git.
Run and Debug: For running and debugging your code.
Extensions: For managing VS Code extensions.
Users can add or remove icons based on their preferences and installed extensions.
Side Bar
Location: Adjacent to the Activity Bar, typically on the left side of the window.
Purpose: The Side Bar displays the contents of the selected view from the Activity Bar. Depending on which icon is selected, the Side Bar will show different panels, such as:
Explorer: Displays a tree view of your project's folders and files.
Search: Displays the search results.
Source Control: Shows version control information and options.
Run and Debug: Provides debugging controls and information.
Extensions: Lists installed extensions and provides recommendations.
Editor Group
Location: The central area of the window where you edit files.
Purpose: The Editor Group is where you write and edit your code. You can have multiple files open in tabs, and you can split the editor into multiple groups (columns or rows) to view and edit multiple files side by side. Features include:
Tabs: Each open file is represented by a tab.
Split Editor: You can split the editor into multiple panels for multi-file editing.
Minimap: A small overview of the entire file on the right side of the editor for quick navigation.
IntelliSense: Provides code suggestions and autocompletion.
Status Bar
Location: The horizontal bar at the bottom of the window.
Purpose: The Status Bar provides information about the current state of the editor and workspace. It shows:
Line and column number: Indicates the current cursor position in the file.
Encoding: Displays the character encoding of the current file.
Language Mode: Shows the programming language of the current file.
Git branch: Displays the current Git branch if you're using source control.
Errors and Warnings: Indicates the number of errors and warnings in your code.
Notifications: Displays various notifications, like build status or background tasks.
  

4. Command Palette:
   - What is the Command Palette in VS Code, and how can it be accessed? Provide examples of common tasks that can be performed using the Command Palette.
The Command Palette in Visual Studio Code (VS Code) is a powerful tool that allows users to access various commands and functionalities quickly and efficiently without navigating through menus or using mouse clicks. It provides a centralized place to run commands, manage extensions, configure settings, and more.
How to Access the Command Palette
You can access the Command Palette in two main ways:
Using Keyboard Shortcut: Press Ctrl+Shift+P (Windows/Linux) or Cmd+Shift+P (Mac).
Using the Menu: Go to the top menu and select View > Command Palette.
Examples of Common Tasks Performed Using the Command Palette
Opening Files
Command: File: Open File
Usage: Quickly open a file by name within your workspace.
Running a Task
Command: Tasks: Run Task
Usage: Run predefined tasks like build scripts, linting, or test commands.
Installing Extensions
Command: Extensions: Install Extensions
Usage: Browse and install extensions from the VS Code marketplace.
Changing Themes
Command: Preferences: Color Theme
Usage: Switch between different color themes for the editor.
Formatting Code
Command: Format Document
Usage: Automatically format your code according to your setup rules.
Git Commands
Command: Git: Commit
Usage: Stage and commit changes to the repository.
Search and Replace
Command: Search: Replace in Files
Usage: Perform search and replace operations across multiple files in the workspace.
Opening Settings
Command: Preferences: Open Settings (UI)
Usage: Open the settings UI to configure various aspects of VS Code.
Running Debug Configurations
Command: Debug: Start Debugging
Usage: Start a debugging session using predefined configurations.
Viewing Keyboard Shortcuts
Command: Preferences: Open Keyboard Shortcuts
Usage: View and modify the keyboard shortcuts.
Using the Command Palette
When you open the Command Palette, you can start typing the name of the command you want to execute. VS Code will show a list of matching commands, and you can select the desired one by clicking on it or by navigating with the arrow keys and pressing Enter.
For example, to format the current document:
Open the Command Palette (Ctrl+Shift+P or Cmd+Shift+P).
Type Format Document.Select the Format Document command from the list.

5. Extensions in VS Code:
   - Discuss the role of extensions in VS Code. How can users find, install, and manage extensions? Provide examples of essential extensions for web development.
Extensions play a crucial role in extending the functionality of Visual Studio Code (VS Code), allowing users to tailor their coding environment to their specific needs and preferences. These extensions can add new features, language support, debugging tools, themes, and much more, enhancing productivity and improving the overall development experience.
Finding and Installing Extensions
Users can find and install extensions in several ways:
Using the Extensions View: Click on the Extensions icon in the Activity Bar on the side of the VS Code window. From there, you can search for extensions, view popular ones, and install them with just a few clicks.
Command Palette: Open the Command Palette (Ctrl+Shift+P or Cmd+Shift+P) and use commands like Extensions: Install Extensions to search for and install extensions.
VS Code Marketplace: Users can also explore the VS Code Marketplace website (marketplace.visualstudio.com) to discover extensions, read reviews, and install them directly from the web.
Managing Extensions
Once installed, extensions can be managed from the Extensions view in VS Code. Users can enable, disable, uninstall, update, and configure extensions according to their preferences. VS Code also provides options to automatically update extensions to their latest versions.
Essential Extensions for Web Development
For web development, several extensions are invaluable for enhancing productivity and providing essential features. Here are some examples:
ESLint/Prettier: Extensions like ESLint and Prettier help ensure code consistency and adhere to coding standards by providing linting and code formatting capabilities.
Debugger for Chrome: This extension allows developers to debug JavaScript code running in the Chrome browser directly from VS Code, enabling efficient debugging workflows for web applications.
Live Server: Live Server launches a local development server with live reload functionality, making it easy to preview and test web pages as you write code.
HTML CSS Support: This extension provides advanced autocompletion and IntelliSense for HTML and CSS, enhancing coding productivity and reducing errors.
Auto Rename Tag: Simplifies the process of renaming paired HTML/XML tags by automatically renaming the closing tag when the opening tag is renamed.
Bracket Pair Colorizer: This extension helps improve code readability by colorizing matching brackets with the same color, making it easier to identify code blocks.
GitLens: GitLens enhances the built-in Git capabilities of VS Code by providing additional insights into code history, blame information, and repository navigation.
Path Intellisense: Offers autocomplete suggestions for file paths and filenames, reducing the need to remember or type out long file paths manually.
6. Integrated Terminal:
   - Describe how to open and use the integrated terminal in VS Code. What are the advantages of using the integrated terminal compared to an external terminal?
To open and use the integrated terminal in Visual Studio Code (VS Code), follow these steps:
Opening the Integrated Terminal
Using the Menu:Go to the top menu bar.
Click on Terminal.Select New Terminal from the dropdown menu.
Using the Command Palette:Press Ctrl+Shift+P (or Cmd+Shift+P on macOS) to open the Command Palette.
Type > Terminal: Create New Integrated Terminal and select it.
Using Keyboard Shortcuts:Press Ctrl+ (backtick) (or Cmd+ on macOS) to toggle the terminal.
Using the Integrated Terminal
Once the terminal is open, you can use it just like any other terminal:
Execute Commands: Type and execute commands by pressing Enter.
Switch Between Terminals: If you have multiple terminals open, switch between them using the dropdown at the top of the terminal panel.
Split Terminals: You can split the terminal window by clicking the split terminal button (usually located at the top-right of the terminal panel).
Resize Terminals: Drag the separator between the terminal and the editor to resize it.
Change Terminal Type: Use the dropdown menu to select different shell types (e.g., Bash, PowerShell, Command Prompt).
Advantages of Using the Integrated Terminal
Convenience and Workflow Integration:Unified Environment: Work within the same window as your code, reducing context switching.
Quick Access: Easily toggle the terminal without leaving VS Code.
Synchronization with the Editor:
Path Synchronization: The terminal starts in the directory of the currently open project, making it easier to run project-specific commands.
Command Execution: Execute commands related to your code, such as running scripts, building projects, or managing version control directly from the terminal.
Customization and Configuration:
Customization Options: Customize the appearance, shell type, and behavior of the terminal through VS Code settings.
Profiles: Save and switch between different terminal profiles for different tasks or projects.
Integrated Tools:
Extensions: Use VS Code extensions that integrate with the terminal to enhance functionality, such as linters, debuggers, and task runners.
Tasks Integration: Define and run tasks directly from the terminal, integrating with the VS Code tasks feature.
Cross-Platform Consistency:
Uniform Interface: Use the same terminal interface across different operating systems, ensuring a consistent development experience.
Example Scenario
For instance, if you are working on a Node.js project, you can have your code editor and terminal in the same window. You can run npm install, start your server with npm start, and see any console output or errors immediately in the terminal without switching windows.
By using the integrated terminal, you streamline your development workflow, maintain focus on your tasks, and leverage the powerful features of VS Code to enhance productivity.

7. File and Folder Management:
   - Explain how to create, open, and manage files and folders in VS Code. How can users navigate between different files and directories efficiently?
In Visual Studio Code (VS Code), creating, opening, and managing files and folders is intuitive and efficient. Here's a detailed guide on how to perform these actions and navigate between different files and directories efficiently.

Creating, Opening, and Managing Files and Folders
Creating Files and Folders
Using the Explorer Sidebar:

Open the Explorer sidebar by clicking the file icon at the top-left corner or pressing Ctrl+Shift+E.
To create a new file, click the New File icon (a document with a plus sign) or right-click in the Explorer and select New File. Name the file and press Enter.
To create a new folder, click the New Folder icon (a folder with a plus sign) or right-click in the Explorer and select New Folder. Name the folder and press Enter.
Using the Command Palette:
Press Ctrl+Shift+P (or Cmd+Shift+P on macOS) to open the Command Palette.
Type > File: New File to create a new file or > Explorer: New Folder to create a new folder.
Opening Files and Folders
Using the Explorer Sidebar:
Navigate to the desired file or folder in the Explorer sidebar and click to open it.
Double-click to open the file in a new tab.
Using the File Menu:
Click on File in the top menu bar.
Select Open File... to open a specific file or Open Folder... to open an entire directory.
Using the Command Palette:
Press Ctrl+Shift+P (or Cmd+Shift+P on macOS).
Type > Open File or > Open Folder and select the appropriate option.
Drag and Drop:
Drag files or folders from your file explorer (e.g., Windows Explorer or Finder on macOS) directly into the VS Code window.
Managing Files and Folders
Rename:
Right-click the file or folder in the Explorer sidebar and select Rename, or select the file/folder and press F2.
Delete:
Right-click the file or folder in the Explorer sidebar and select Delete, or select the file/folder and press Delete.
Move:
Drag the file or folder to a new location within the Explorer sidebar.
Navigating Between Files and Directories Efficiently
Quick Open:
Press Ctrl+P (or Cmd+P on macOS) to open the Quick Open dialog.
Start typing the name of the file you want to open, and select it from the list.
Explorer Sidebar:
Use the Explorer sidebar to browse and navigate through your project's file structure.
Expand and collapse folders to manage the view.
Breadcrumbs:
Enable breadcrumbs by clicking on the view options in the Explorer sidebar or by going to View > Appearance > Breadcrumbs.
Use breadcrumbs at the top of the editor to navigate through the folder hierarchy.
File Tabs:
Open files are displayed in tabs at the top of the editor.
Use Ctrl+Tab (or Cmd+Tab on macOS) to cycle through open tabs.
Go to Definition and References:
Use F12 to go to the definition of a symbol (e.g., function, variable) and Shift+F12 to find all references.
Command Palette:
Press Ctrl+Shift+P (or Cmd+Shift+P on macOS) to open the Command Palette and access various navigation commands like > Go to File, > Go to Symbol, etc.
Terminal Navigation:
Use the integrated terminal to navigate the file system with commands like cd, ls, dir, etc.
Example Scenario
Suppose you are working on a JavaScript project and need to quickly switch between editing app.js and index.html. You can:
Use Ctrl+P to quickly open app.js by typing its name.
Navigate to index.html using the Explorer sidebar.
Use Ctrl+Tab to switch between these open files efficiently.
Use breadcrumbs to navigate up the directory structure if you need to edit a configuration file in the root directory.

8. Settings and Preferences:
   - Where can users find and customize settings in VS Code? Provide examples of how to change the theme, font size, and keybindings.
In Visual Studio Code (VS Code), users can find and customize settings through the user interface and by editing JSON configuration files directly. Here are the steps to customize the theme, font size, and keybindings:
Accessing and Customizing Settings
Accessing Settings
Using the Settings UI:Open the Settings UI by clicking on the gear icon in the lower-left corner of the window and selecting Settings, or by pressing Ctrl+, (or Cmd+, on macOS).
Using the Command Palette:Press Ctrl+Shift+P (or Cmd+Shift+P on macOS) to open the Command Palette.
Type > Preferences: Open Settings (UI) and select it.
Editing Settings JSON
Open Settings JSON:In the Settings UI, click on the icon with the document and a small arrow in the top right corner to open the settings.json file directly.
Alternatively, you can use the Command Palette and type > Preferences: Open Settings (JSON).
Changing the Theme Using the Settings UI:Go to the Settings UI (Ctrl+, or Cmd+,).
In the search bar, type theme. Under Color Theme, click on the dropdown menu and select your preferred theme from the list.
Using the Command Palette: Press Ctrl+Shift+P (or Cmd+Shift+P on macOS).
Type > Preferences: Color Theme and select it.
Choose your desired theme from the list.
Changing the Font Size
Using the Settings UI:
Open the Settings UI (Ctrl+, or Cmd+,).
In the search bar, type font size.
Adjust the Editor: Font Size setting by entering your desired font size (e.g., 16).
Editing Settings JSON:
Open the settings.json file.
Add or modify the following line:
Changing Keybindings
Using the Keybindings UI:Open the Keybindings UI by clicking on the gear icon in the lower-left corner and selecting Keyboard Shortcuts, or by pressing Ctrl+K Ctrl+S (or Cmd+K Cmd+S on macOS).
Use the search bar to find the command you want to rebind.
Click on the pencil icon next to the command and press the new key combination you want to assign.
Editing Keybindings JSON:
In the Keybindings UI, click on the icon with the document and a small arrow in the top right corner to open the keybindings.json file directly.
Add or modify keybindings in the JSON format. For example, to change the keybinding for opening a new terminal to Ctrl+T:
json
Example: Customizing Settings
Change the Theme to "Solarized Dark":
Open the Command Palette (Ctrl+Shift+P or Cmd+Shift+P).
Type > Preferences: Color Theme and select Solarized Dark.
Set the Font Size to 14:
Open the Settings UI (Ctrl+, or Cmd+,).
Search for font size.
Set Editor: Font Size to 14.
Change the Keybinding for Cut to Ctrl+X:
Open the Keybindings UI (Ctrl+K Ctrl+S or Cmd+K Cmd+S).
Search for Cut.
Click the pencil icon next to the command and press Ctrl+X.

9. Debugging in VS Code:
   - Outline the steps to set up and start debugging a simple program in VS Code. What are some key debugging features available in VS Code?
Setting up and starting debugging in Visual Studio Code (VS Code) involves a few steps to configure the debugger and understand its features. Here's a guide to get you started with debugging a simple program, such as a JavaScript or Python script, in VS Code.
Steps to Set Up and Start Debugging
1. Install Necessary Extensions
JavaScript/Node.js: No additional extensions are required as JavaScript debugging is built-in.
Python: Install the Python extension. Go to the Extensions view (Ctrl+Shift+X), search for "Python", and install it.
2. Open Your Project
Open the folder containing your project files by selecting File > Open Folder and navigating to your project directory.
3. Write a Simple Program
Create a file with your code. For example, app.js for JavaScript or app.py for Python.
4. Configure the Debugger
Open the Debug View:
Click on the debug icon in the Activity Bar on the side of the window or press Ctrl+Shift+D.
Create a Launch Configuration:
Click on the gear icon to open launch.json or select create a launch.json file.
Choose the environment (e.g., Node.js for JavaScript or Python).
5. Set Breakpoints
Open the file with your code (e.g., app.js or app.py).
Click in the gutter next to the line numbers where you want to set breakpoints, or press F9.
6. Start Debugging
In the Debug view, click the green play button or press F5 to start debugging.
The debugger will start and stop at the breakpoints you've set.
Key Debugging Features in VS Code
Breakpoints:Set breakpoints to pause execution at specific lines. You can also set conditional breakpoints and log points.
Step Through Code:Use F10 to step over, F11 to step into, and Shift+F11 to step out of functions.
Variable Inspection:Hover over variables to see their values, or use the VARIABLES pane in the Debug view to inspect and modify variables.
Watch Expressions:Add expressions to the WATCH pane to monitor their values over time.
Call Stack:View the call stack to understand the execution flow and navigate through the stack frames.
Debug Console:Use the Debug Console to evaluate expressions and execute commands in the context of the paused program.
Inline Values:View variable values inline within the code editor during debugging sessions.
Exception Handling:Configure the debugger to break on exceptions by setting the appropriate options in launch.json.
Example Debugging Session
Set a Breakpoint:Set a breakpoint on the line where greet(name) is called in app.js or app.py.
Start Debugging:Press F5 to start debugging. The debugger will stop at the breakpoint.
Inspect Variables:
Hover over name to see its value.
Check the VARIABLES pane to inspect all local variables.
Step Through Code:
Press F10 to step over the console.log or print statement.
Observe the output in the integrated terminal.
10. Using Source Control:
    - How can users integrate Git with VS Code for version control? Describe the process of initializing a repository, making commits, and pushing changes to GitHub.
Integrating Git with Visual Studio Code (VS Code) provides a powerful environment for version control. Here’s how you can set up and use Git in VS Code, including initializing a repository, making commits, and pushing changes to GitHub.
Integrating Git with VS Code
1. Install Git
Ensure that Git is installed on your system. You can download it from the official Git website.
2. Install Git Extension for VS Code
The Git extension is built-in with VS Code. If you need additional features, you can install the GitHub Pull Requests and Issues extension from the Extensions view (Ctrl+Shift+X).
Initializing a Repository
Open Your Project Folder:
Open the folder containing your project in VS Code (File > Open Folder).
Initialize Git Repository:
Open the Source Control view by clicking the Source Control icon in the Activity Bar on the side of the window or by pressing Ctrl+Shift+G.
Click Initialize Repository in the Source Control view. This will create a new Git repository in your project folder.
Making Commits
Stage Changes:
After making changes to your files, go to the Source Control view.
You’ll see the list of changed files. Click the + icon next to each file to stage it, or click the + icon at the top to stage all changes.
Commit Changes:
After staging changes, enter a commit message in the message box at the top of the Source Control view.
Click the checkmark icon or press Ctrl+Enter to commit the changes.
Pushing Changes to GitHub
Sign In to GitHub:
Open the Command Palette (Ctrl+Shift+P or Cmd+Shift+P on macOS).
Type > Git: Sign In to GitHub and follow the prompts to authenticate.
Add a Remote Repository:
Open the Command Palette and type > Git: Add Remote.
Enter the name of the remote (usually origin).
Enter the URL of your GitHub repository. You can find this URL on the main page of your repository on GitHub, under the green Code button.
Push Changes:To push your commits to GitHub, go to the Source Control view.
Click on the ellipsis (...) at the top of the view and select Push.
Alternatively, you can use the Command Palette and type > Git: Push.
Example Workflow
Initialize a Repository:
Open your project folder in VS Code.
Initialize the repository in the Source Control view.
Make Changes:
Edit your files as needed.
Stage and Commit:
Go to the Source Control view.
Stage the changed files.
Enter a commit message and commit the changes.
Push to GitHub:
Ensure you’re signed in to GitHub.
Add the remote repository URL.
Push the commits to the remote repository.
Key Git Features in VS Code
Source Control View:
Access and manage your repository, stage changes, and commit files.
Branch Management:
Create, switch, and manage branches directly from the Source Control view.
Built-in Terminal:
Use the integrated terminal (Ctrl+ or Cmd+) for advanced Git commands.
GitLens Extension:
Enhance your Git experience with additional features like blame annotations, detailed history, and more.
GitHub Integration:
Use the GitHub Pull Requests and Issues extension to manage pull requests and issues directly from VS Code.
Example Commands
Initialize Repository: Ctrl+Shift+G > Initialize Repository
Stage All Changes: Click the + icon in the Source Control view
Commit Changes: Enter a commit message and click the checkmark or press Ctrl+Enter
Add Remote: Ctrl+Shift+P > Git: Add Remote
Push Changes: Ctrl+Shift+P > Git: Push
 Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide screenshots or step-by-step instructions where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by 1st July 

