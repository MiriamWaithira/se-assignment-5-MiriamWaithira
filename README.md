[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/XoLGRbHq)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15349715&assignment_repo_type=AssignmentRepo)
# SE-Assignment-5
Installation and Navigation of Visual Studio Code (VS Code)
 Instructions:
Answer the following questions based on your understanding of the installation and navigation of Visual Studio Code (VS Code). Provide detailed explanations and examples where appropriate.

 Questions:

1. Installation of VS Code:
   - Describe the steps to download and install Visual Studio Code on Windows 11 operating system. Include any prerequisites that might be needed.

The prerequisites are a computer that has Windows 11 installed already and internet access.
i. To start the download, launch your preferred browser and navigate to the official VSCode website: https://code.visualstudio.com/
ii. Click 'Download for Windows' button to automatically start the download.
iii. Once the download is complete, navigate to the folder where your downloads are located and double-click on the downloaded file. When the installer opens, read the license agreement, select the 'agree the agreement' option, and click 'Next'.
iv. Choose the default installation location or select a different location of your choice and click 'Next' when you are ready.
v. Click 'Install' to begin the installation process. When the installation is complete, you can choose 'Launch' option to open VSCode and click 'Finish'.

2. First-time Setup:
   - After installing VS Code, what initial configurations and settings should be adjusted for an optimal coding environment? Mention any important settings or extensions.

Initial configurations, settings and configurations
i. ensure you have the latest version of VSCode- 'Help'>'Check for Updates'
ii. To choose a theme easy for your eyes, go to 'File'>'Preferences'>'Color theme' and select the theme you prefer.
iii. To adjust font size and family, go to 'File'>'Preferences'>'Settings' and search 'Font'. Change:'Editor Font Size' and 'Editor:Font Family'
iv. To enable auto-save, go to 'File'>'Autosave' and ensure it is checked all the time.
v. Extensions- click the Extensions icon on the sidebar or press 'Ctrl+Shift+X', search and install extensions such as:
>Prettier - Code formatter: Ensures your code is consistently formatted.
>Python: Adds support for Python programming, including IntelliSense, linting, and debugging.
>C/C++: Adds support for C and C++ programming.
>Live Server: Launches a local development server with live reload feature for static and dynamic pages.
>GitLens: Enhances the built-in Git capabilities.
>Bracket Pair Colorizer: Colorizes matching brackets for easier code navigation.

3. User Interface Overview:
   - Explain the main components of the VS Code user interface. Identify and describe the purpose of the Activity Bar, Side Bar, Editor Group, and Status Bar.

i. Activity bar- The vertical bar on the far left side of the window. It  provides access to different views and controls, such as the Explorer, Search, Source Control, Run and Debug, and Extensions.
ii. Side bar- To the right of the Activity Bar. It displays the content related to the view selected in the Activity Bar. For example, if you select the Extensions view, the Side Bar will show the istalled and recommended extensions.
iii. Editor Group- The central area of the interface where files are opened and edited. It is the primary area for writing and editing code.In this area each open file is represented by a tab at the top of the Editor Group.It also provides color-coded syntax for various programming languages.

iv. Status Bar- The horizontal bar at the bottom of the window. It displays information about the current state of the editor and the workspace. It has the following features:
>Language Mode: Shows the language of the currently open file and allows you to change it.
>Line and Column Number: Indicates the current cursor position in the file.
>Errors and Warnings: Displays the number of errors and warnings in the open file.
>Git Branch: Shows the active Git branch.
>Background Tasks: Indicates running tasks or processes, like build or deployment tasks.

4. Command Palette:
   - What is the Command Palette in VS Code, and how can it be accessed? Provide examples of common tasks that can be performed using the Command Palette.

The Command Palette is a tool that allows you to quickly access different settings and commands without having to go through menus. It enables users to carry out tasks, look up and run commands, and personalize the editor.

Making Use of the Command Palette
>Shortcut keystroke: Ctrl+Shift+P (or F1).
>Navigate the menu by selecting View > Command Palette.
Typical Tasks Completed with the Command Palette:
i.Accessing Documents:
To swiftly find and open files in your workspace, type >Open File.
ii. Sprinting Integrated Commands:
To navigate to a specific line in the current file, type >Go to Line.
To reveal or conceal the integrated terminal, type >Toggle Terminal.
iii. Using Extensions Commands: To format the open file, type >Format Document if the Prettier extension is installed.
iv. Looking for the Settings:
To use the settings editor, type >Preferences: Open Settings.
v. Git directives:
To commit modifications, type >Git: Commit.
To push commits to a remote repository, type >Git: Push.


5. Extensions in VS Code:
   - Discuss the role of extensions in VS Code. How can users find, install, and manage extensions? Provide examples of essential extensions for web development.

They allow users to add new features, support additional programming languages, and integrate with other tools and services.

Finding Extensions:
i. Click on the Extensions icon in the Activity Bar (or press Ctrl+Shift+X).
ii. Browse through the marketplace or use the search bar to find specific extensions.

Installing Extensions:
i. Once you find an extension you want to install, click the Install button.
ii. The extension will be downloaded and installed automatically. You might need to reload VS Code for the extension to be activated.

Managing Extensions:
i. Enabling/Disabling: Right-click on an installed extension in the Extensions view to enable or disable it.
ii. Uninstalling: Click the Uninstall button to remove an extension.
iii. Configuring: Some extensions have settings that can be configured. Click on the gear icon next to the extension to access its settings.

Examples of Essential Extensions for Web Development:
i. Prettier - Code Formatter:
Automatically formats code to ensure a consistent style across your project.
ii. Live Server:
Launches a local development server with live reload feature for static and dynamic pages.
iii. HTML CSS Support:
Provides IntelliSense and validation for HTML and CSS files.
iv. JavaScript (ES6) Code Snippets:
Offers a collection of code snippets for JavaScript ES6, enhancing productivity by reducing repetitive code typing.
v. Path Intellisense:
Autocompletes filenames in your project, making it easier to manage file paths.
vi. GitLens:
Enhances the built-in Git capabilities with features like blame annotations, history
vii. Debugger for Chrome:
Enables debugging of JavaScript code in the Google Chrome browser directly from VS Code.


6. Integrated Terminal:
   - Describe how to open and use the integrated terminal in VS Code. What are the advantages of using the integrated terminal compared to an external terminal?

>The easiest way to access the terminal is by using the menu: go to 'View'>'Terminal'. The Terminal panel opens at the Status Bar at the bottom of the user interface.

>Click the '+' icon in the terminal panel to open anew terminal of your choice. You can open multiple terminals and switch between them using the dropdown icon or by clicking on the terminal tabs e.g. Git Bash Terminal and Windows PowerShell Terminal.

>You can run commands as you would in any terminal window and press 'Enter' to execute.

>You can change the shell used by the terminal e.g. Powershell, Git Bash or Command Prompt by going to 'Click the dropdown icon'>'Select default profile'> and select your preferred shell.

Advantages:
i. Contextual relevance- The integrated terminal operates within the context of your workspace, making it easy to run commands and scripts relative to your project directory without needing to navigate directories manually.

ii. Convenience- The integrated terminal is accessible within the same window as your code editor, reducing the need to switch between multiple applications. This can speed up your workflow and improve focus.

iii. Efficiency- You can quickly switch between the editor and the terminal using keyboard shortcuts, enhancing productivity.

iv. Visibility and integration- Errors and output from commands are displayed in the terminal without obstructing your view of the code, and you can easily reference code while running commands.
Integrated terminal outputs can be combined with other VS Code features, such as problems and tasks, for better error tracking and automation.

v. Multiple instances- The ability to open and manage multiple terminal instances within the same window allows for efficient multitasking, such as running a development server in one terminal while running build tasks in another.


7. File and Folder Management:
   - Explain how to create, open, and manage files and folders in VS Code. How can users navigate between different files and directories efficiently?


Creating Files and Folders:
i Using the Explorer:
1. Create a File:
Open the Explorer view by clicking the Explorer icon in the Activity Bar or pressing Ctrl+Shift+E.
Right-click on the folder where you want to create a new file and select New File.
Enter the name for the new file and press Enter.
2. Create a Folder:
Right-click on the parent directory in the Explorer and select New Folder.
Enter the name for the new folder and press Enter.

ii. Using the Command Palette:
Press Ctrl+Shift+P to open the Command Palette.
Type >File: New File or >File: New Folder and follow the 
prompts.

Opening Files and Folders:
i. Double-click on a file in the Explorer to open it in the editor.
ii. To open a folder, click on the folder icon in the Explorer and navigate to the desired folder.

Managing Files and Folders:
i. Renaming:Right-click on a file or folder in the Explorer and select Rename. Enter the new name and press Enter.
ii.  deleting- Right-click on a file or folder in the Explorer and select Delete. Confirm the deletion when prompted.
iii. Moving: Drag and drop files or folders within the Explorer to move them to a different location. You can also use cut (Ctrl+X) and paste (Ctrl+V) commands to move files or folders.

Navigating Between Files and Directories Efficiently:
i. Quick Open:
Press Ctrl+P to open the Quick Open dialog.
Start typing the name of the file you want to open, and VS Code will show a list of matching files. Select the desired file and press Enter.

ii. Go to File:
Use Ctrl+T (or Ctrl+P) to quickly open a file by name.
This is especially useful in large projects where navigating through the file tree can be time-consuming.

iii. Breadcrumbs:
Enable breadcrumbs by clicking on the breadcrumb icon in the upper left corner of the editor or pressing Ctrl+Shift+..
Breadcrumbs show the file path and allow you to navigate to parent folders or sibling files easily.

iv. Tabs and Split View:
Open multiple files in tabs for easy switching.
Split the editor to view and edit multiple files side by side by right-clicking on a tab and selecting Split Right or Split Down.

v. Go to Definition/Reference:
Use F12 to go to the definition of a symbol.
Use Shift+F12 to find all references to a symbol.
These features help navigate code bases quickly, especially in larger projects.

vi. Peek Definition:
Use Alt+F12 to peek at the definition of a symbol without leaving the current file.

vii. Explorer Context Menu:
Right-click on a file or folder in the Explorer to access various actions, such as opening in a new tab, revealing in the file explorer, copying the path, etc.


8. Settings and Preferences:
   - Where can users find and customize settings in VS Code? Provide examples of how to change the theme, font size, and keybindings.

Changing the theme:
To choose a theme easy for your eyes, go to 'File'>'Preferences'>'Color theme' and select the theme you prefer (e.g., "Dark+ (default dark)").

Changing the font size:
Open the Settings UI (Ctrl+,). Type Font Size in the search bar. Set the Editor: Font Size to e.g. 16 (or your preferred size).

Changing the keybindings:
Open the Keybindings UI (Ctrl+K Ctrl+S). Search for the command you want to change, e.g., workbench.action.files.newUntitledFile. Click the pencil icon next to it, press Ctrl+Alt+N, and confirm.


9. Debugging in VS Code:
   - Outline the steps to set up and start debugging a simple program in VS Code. What are some key debugging features available in VS Code?

Steps to debug:
i. Install Necessary Extensions- depends on the programming language you are using.
ii. Open or Create Your Project- Open VS Code. Open your project folder by going to File > Open Folder and selecting your project directory.
iii. Create a new file in your project directory.
iv. Configure the debugger- Open the Run and Debug view by clicking on the Run icon in the Activity Bar (or press Ctrl+Shift+D). Click on create a launch.json file to create a new debug configuration. Select the appropriate environment (e.g., Python, Node.js) from the list of options. For a Python program, select Python File.
v. Start debugging- Set breakpoints by clicking in the gutter next to the line numbers in your source code. Click the green play button in the Run and Debug view or press F5 to start debugging. The debugger will start, and the program will run until it hits the breakpoint you set.

Key debugging Features:
>Breakpoints
Set and Remove Breakpoints: Click in the gutter next to a line number to toggle breakpoints.
Conditional Breakpoints: Right-click on a breakpoint and select Edit Breakpoint to set conditions under which the breakpoint will be hit.
>Watch Expressions
Add Watch Expressions: In the Run and Debug view, add variables to the Watch section to monitor their values during debugging.
Evaluate Expressions: Hover over variables or use the Debug Console to evaluate expressions.
>Variables View
Inspect Variables: In the Variables section of the Run and Debug view, inspect the values of local, global, and closure variables.
>Call Stack
View Call Stack: The Call Stack section shows the current call stack, allowing you to navigate between different frames and understand the sequence of function calls leading up to the current point.
>Step Controls
Step Over (F10): Execute the next line of code but do not step into functions.
Step Into (F11): Step into the function calls on the current line.
Step Out (Shift+F11): Step out of the current function and return to the caller.
Continue (F5): Continue running the program until the next breakpoint or the end of the program.
>Debug Console
Interactive Debugging: Use the Debug Console to execute arbitrary expressions in the context of the currently paused execution.
>Logpoints
Logpoints: Similar to breakpoints, but instead of pausing execution, they log a message to the console. Useful for adding debug output without stopping the program.


10. Using Source Control:
    - How can users integrate Git with VS Code for version control? Describe the process of initializing a repository, making commits, and pushing changes to GitHub.

i.  Download and install git from git-scm.com if you don't have it yet
ii. Open the integrated terminal in VS Code (Ctrl+). Type git --version to verify the installation.
iii. Open VS Code. Go to File > Preferences > Settings. Search for Git Path and ensure that the path to your Git executable is set correctly (usually detected automatically).

Process of initializing a repository, making commits, and pushing changes to GitHub:

i. Initializing a Repository
>Open Your Project Folder:
Open VS Code and navigate to your project folder (File > Open Folder).
>Initialize a Git Repository:
Open the integrated terminal (Ctrl+).
Type git init to initialize a new Git repository in the current folder.
Alternatively, click the Source Control icon in the Activity Bar and click Initialize Repository.

ii. Making Commits
>Stage Changes:
Open the Source Control view by clicking the Source Control icon in the Activity Bar or pressing Ctrl+Shift+G.
You will see a list of changed files.
To stage specific changes, click the + icon next to each file.
To stage all changes, click the + icon at the top of the list.
>Commit Changes:
After staging the changes, enter a commit message in the text box at the top of the Source Control view.
Click the checkmark icon or press Ctrl+Enter to commit the changes.

iii. Pushing Changes to GitHub
>Create a Repository on GitHub:
Go to GitHub and create a new repository by clicking the + icon in the top right corner and selecting New repository.
Fill in the repository details and click Create repository.
>Add Remote Repository:
Copy the URL of your GitHub repository (HTTPS or SSH).
In the integrated terminal, navigate to your project directory and type: git remote add origin <repository-url>
Replace <repository-url> with the URL of your GitHub repository.
>Push Changes to GitHub:
In the integrated terminal, type:git push -u origin master
This will push your commits to the master branch on GitHub.
For subsequent pushes, you can simply use git push.

References:
i. https://www.youtube.com/
ii. https://chatgpt.com/
iii. Class recordings


 Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide screenshots or step-by-step instructions where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by 1st July 

