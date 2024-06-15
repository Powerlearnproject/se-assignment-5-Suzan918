[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/XoLGRbHq)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15269510&assignment_repo_type=AssignmentRepo)
# SE-Assignment-5
Installation and Navigation of Visual Studio Code (VS Code)
 Instructions:
Answer the following questions based on your understanding of the installation and navigation of Visual Studio Code (VS Code). Provide detailed explanations and examples where appropriate.

 Questions:

1. Installation of VS Code:
   - Describe the steps to download and install Visual Studio Code on Windows 11 operating system. Include any prerequisites that might be needed

   Download Visual Studio Code:

     .Open your web browser and go to the official Visual Studio Code download page:
     download page:
     http://code.visualstudio.com/.

     Run the installer:

      .Once the download is complete, navigate to your downloads.
      .Double-click the `VSCodeUserSetup-x64-x.x.x.exe`(the exact filename may  vary based on the version).

     Begin Installation:

      .A user Account Control(UAC) prompt may appear asking if you want to allow this app to make changes to your device. Click ''Yes''.
      .The VSCode Setup Wizard will open. Click  ''Next'' to continue.

     Accept the Licence Agreements:

       .Read through the license agreement. If you agree, select ''I accept the agreement'' and click ''Next''.

     Select Installation Location:

      .Choose the destination folder where you want to install VScode. The dafault location is usually fine for most users. Click ''Next''.

     Select Additional Tasks:

     .Choose the additional tasks you want the installer to perform.

     Complete the installation:

      . The installation process will begin and may take a few minutes.
      . Once the installation is complete, you can choose to launch VSCode immediately by checking the ''Launch Visual Studio Code ''option.
      . Click ''Finish'' to exit the Setup Wizard.


2. First-time Setup:
   - After installing VS Code, what initial configurations and settings should be adjusted for an optimal coding environment? Mention any important settings or extensions.

   Initial Configurations 

   Theme and Appearance:

   . Go to `File`>` Preferences`>`Color Theme` and choose a theme that suits your preference (e.g Dark+,Light+).
   . Adjust the font size.
   
   Editor Settings:

    . Auto Save: Enable automatic formatting on save by searching for `Format On Save` in the settings and checking the box.
    .Tab Size and Indentation:
     Customize the tab size and identation style to match your ooding standards.
       
   Essential Extensions:

    .Language Support:

     .Python: `ms-python.python`
     .Java Script
     .HTML/CSS


3. User Interface Overview:
   - Explain the main components of the VS Code user interface. Identify and describe the purpose of the Activity Bar, Side Bar, Editor Group, and Status Bar.

   Activity Bar: Located on the left side ofthe window, it provides quick access to various aspects of the application, such as:
    .Opening a new file or folder
    .Switching between editors 
    .Accessing version control systems 
    .Viewing extensions and settings 

   Side Bar: ALSO on the left side, it displays different views depending on the active icon in the Activity Bar.
   Common views include:
    .File Explorer: shows the file structure 
    .Debug: shows variables and call stack  during debuggling

   Editor Group:This is the main area where your code is displayed. You can open multiple files, and they will be displayed in separate tabs within the Editor Group.
   
   Status Bar: located at the bottom of the window, it displays information about the current file, such as:
    .File name and path
    .Language and encoding
    .Line and column numbers 
    .Errors and warnings 


4. Command Palette:
   - What is the Command Palette in VS Code, and how can it be accessed? Provide examples of common tasks that can be performed using the Command Palette.

 The command Palette in VS Code is a versatile tool that allows you to access and execute various commands, features, and settings within the editor. It can be accessed in several ways:

   .Keyboard shortcut: Press Ctrl + Shift + P (Windows/Linux)
   .Menu: Go to View > Command Palette.
   .Icon: Click the Command Palette icon in the Activity Bar.
   The command Palette allows you to perform a wide range of tasks, including:

     .Switching themes 
     .Opening files
     .Running commands
     .Formating code
     .Searching
     .settings
     .Extensions
     .Git operations
     .Code actions
     .Debugging


5. Extensions in VS Code:
   - Discuss the role of extensions in VS Code. How can users find, install, and manage extensions? Provide examples of essential extensions for web development.

   Role of Extensions:

    .Extensions can add new features, languages , and tools to VS Code.
    .They can enhance existing features and improve overall productivity.
    .Extensions can integrate VS Code with other services and tools, making it a central hub for development tasks.

  Finding Extensions:

   .Users can find extensions in the VS Code Extensions Marketplace.
   .The marketplace can be accessed directly from VS Code by clicking the Extensions icon in the Activity Bar.

   Installing Extensions:

    .Once a user finds an extension, they can click the ''install'' button to add it to VS Code.
    .VS Code will automatically download and install the extensions.

   Managing Extensions:

    .Users can be view and manage installed extensions in the Extensions Panel.
    .They can be enable or disable extensions, check for updates, and uninstall them.

   Examples of essential extensions for web development include:

    .Web Development Essentials Extension Park
    .JavaScript Booster
    .Intellisense for CSS class names in HTML

    
6. Integrated Terminal:
   - Describe how to open and use the integrated terminal in VS Code. What are the advantages of using the integrated terminal compared to an external terminal?

   To open the intergrated terminal in VS Code:

    .Press Ctrl +
    .Alternatively, use the menu: View > Terminal > New Terminal
    .The terminal will appear in the bottom panel of the VS Code Window.

   Advantages of using the intergrated terminal:

    .Convenience
    .Context
    .Integration
    .Multi-terminal
    .Better perfomance

    
7. File and Folder Management:
   - Explain how to create, open, and manage files and folders in VS Code. How can users navigate between different files and directories efficiently?

   Creating Files and Folders:


    .Open the File Explorer by clicking the File Explorer icon in the Activity Bar.
    .Right-Click in the File Explorer and select ''New File''.
    .Alternatively, you can use the command palette by pressing Ctrl + Shift + P.

    Opening Files and Folders:

     .To open a file, double-click on it in the File Explorer.
     .To open a folder , double-click on it in the ''Open Folder ''command from the command palette.

   Managing Files and Folders:

     .To rename a file or folder , right-click on it and select ''Rename''.
     .To delete a file or folder, right-click on it and select ''Delete''
     .To move a file or folder, drag and drop it to the desired locatin.

   Navigating between Files and Directories:

    .Use the File Explorer to navigate through your project's files and folders.
    .Use the breadcrumb navigation at the top of the File Explorer to quickly navigate to parent directions.
    .Use the ''Go to Folder'' command from the command palette to quickly open a folder by name.

     
8. Settings and Preferences:
   - Where can users find and customize settings in VS Code? Provide examples of how to change the theme, font size, and keybindings.

   Settings Editor: open the Settings Editor by pressing Ctrl + Shift + P.
   
   Settings File: Open the settings file by clicking the ''Open Settings'' button in the Settings Editor.

   Examples of customizing settings:

    .Change the theme: In the Settings Editor, search for'' theme''and select a theme from the dropdown list.

    .Change the font size: In the Settings Editor, search for ''font size'' and adjust the slider.
    
    .Change Keybindings: In the Settings Editor, search for ''keybindings''and click on the ''keyboard Shortcuts'' button.


9. Debugging in VS Code:
   - Outline the steps to set up and start debugging a simple program in VS Code. What are some key debugging features available in VS Code?

   Create a launch configuration:

    .Open the Run view by clicking the Run icon in the Activity Bar
    .Click the ''create a launch.json file''link.
    .Click in the gutter next to the line number where you want to set a break point.

    Set breakpoints:
     .Open the file you want to debug.
     .Click in the gutter next to the line number where you want to set a breakpoint.
    
    Start debbuging:

     .Press F5
     .vS Code will launch the debugger and run your program.

     Step through code:

      .Use the debugging controls to navigate through your code.
      .Use the ''Call Stack''view to see the current function call stack.

     Inspect variables:

      .Hover variables to see their values.
      .Use the ''Variables''view to see all variables.

   Debuggling features in VS Code.

     .Breakpoints
     .Step debuggling
     .Variable inspection
     .Call Stack
     .Debug extensions


10. Using Source Control:
    - How can users integrate Git with VS Code for version control? Describe the process of initializing a repository, making commits, and pushing changes to GitHub.

   Install Git and initialize a Repository

    .Open the Source Control view.
    .Select the initialize Repository button.
    .Use the Publish to Github command button in the Source Control view.
    .Choose a name and description for the repository, and wether to make it public or private.

    Clone a Repository from Github

     .Run the Git: Clone command in the Command Pallette or select the clone Repository, and wether to make it public or private.
    

    Make Commits:

    .In the Source Control view, select the +(plus) icon next to the file to stage a file.
    .Type a commit message in the upper text box.
    .Select the commit button.

   Push changes to Github

   .Select the Sync Changes button to downlaod (pull) any new remote commits and upload (push) new local commits to remote repository.


 Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide screenshots or step-by-step instructions where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by 1st July 

