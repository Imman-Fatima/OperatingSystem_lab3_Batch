## Overview

This assignment demonstrates basic Windows system administration using
Windows keyboard shortcuts, Command Prompt (CMD), batch scripting, and
PowerShell. It covers file and directory management, system and network
investigation, routine task automation, and a comparison of CMD and
PowerShell.

## Assignment Tasks

### 1. Windows Keyboard Shortcuts

The report demonstrates these shortcuts and their purposes:

  -----------------------------------------------------------------------
  Shortcut                            Purpose
  ----------------------------------- -----------------------------------
  `Win + R`                           Opens the Run dialog.

  `Win + E`                           Opens File Explorer.

  `Win + X`                           Opens the Windows power-user menu.

  `Win + L`                           Locks the computer.

  `Win + D`                           Shows or hides the desktop.

  `Win + I`                           Opens Windows Settings.

  `Win + Tab`                         Opens Task View and virtual
                                      desktops.

  `Ctrl + Shift + Esc`                Opens Task Manager.

  `Alt + Tab`                         Switches between open windows.

  `Ctrl + Shift + Enter`              Runs a selected app as
                                      administrator from Start search or
                                      the Run workflow.

  `Win + Shift + S`                   Opens the screen-snipping tool.
  -----------------------------------------------------------------------

### 2. File and Directory Management Using CMD

The assignment creates this directory structure through Command Prompt:

``` text
OS_Lab_Assignment/
├── Students/
├── Reports/
│   ├── Weekly/
│   └── Final/
├── Backup/
└── Scripts/
```

The CMD activities include:

-   Displaying the current directory and directory structure.
-   Creating `student_info.txt` and writing student details to it.
-   Displaying the file contents.
-   Copying the file into `Backup` and renaming the copy to
    `student_info_backup.txt`.
-   Listing files and folders.

Useful commands demonstrated include `cd`, `mkdir`, `tree`, `echo`,
`type`, `copy`, `ren`, and `dir`.

### 3. CMD System Investigation

The following commands are used to inspect the computer and its network:

  -----------------------------------------------------------------------
  Command                             Purpose
  ----------------------------------- -----------------------------------
  `hostname`                          Displays the computer name.

  `whoami`                            Displays the currently logged-in
                                      user.

  `ver`                               Displays the Windows version.

  `ipconfig /all`                     Displays detailed network adapter
                                      configuration.

  `ipconfig`                          Displays the current IP
                                      configuration.

  `ping 8.8.8.8`                      Tests network connectivity to the
                                      specified address.

  `tasklist`                          Lists running processes.

  `date /t`                           Displays the system date.

  `time /t`                           Displays the system time.
  -----------------------------------------------------------------------

### 4. Batch Script Automation

The assignment requires a batch file named `system_check.bat` to
automate routine checks. It should:

1.  Display a welcome message.
2.  Display the current username and computer name.
3.  Display the current date and time.
4.  Show basic IP/network information.
5.  Create `Daily_Backup` if it does not already exist.
6.  Copy `student_info.txt` into the backup folder.
7.  Display a completion message and pause before closing.

### 5. PowerShell Administration

The PowerShell section performs these operations:

  ---------------------------------------------------------------------------------------------------
  Command                                                         Purpose
  --------------------------------------------------------------- -----------------------------------
  `Get-Location`                                                  Displays the current working
                                                                  directory.

  `Get-ChildItem`                                                 Lists files and folders.

  `New-Item -ItemType Directory -Name PowerShell_Task`            Creates the `PowerShell_Task`
                                                                  directory.

  `New-Item -ItemType File -Path .\PowerShell_Task\ps_info.txt`   Creates a text file.

  `Set-Content`                                                   Writes the first line of
                                                                  information to the file.

  `Add-Content`                                                   Appends another line without
                                                                  replacing existing content.

  `Get-Content .\PowerShell_Task\ps_info.txt`                     Displays the file contents.

  `Get-Process`                                                   Lists running processes.

  `Get-ComputerInfo`                                              Displays computer and Windows
                                                                  information.

  `Copy-Item .\PowerShell_Task\ps_info.txt .\Backup\`             Copies the file into the Backup
                                                                  folder.
  ---------------------------------------------------------------------------------------------------

### 6. CMD vs PowerShell

The report compares CMD and PowerShell in terms of command style, ease
of use, automation, and system-administration capabilities. CMD is
useful for quick, traditional command-line tasks and older batch
scripts. PowerShell provides more advanced scripting features and is
preferred in the report for advanced Windows administration.

## Tools and Technologies

-   Microsoft Windows
-   Command Prompt (CMD)
-   Windows Batch scripting (`.bat`)
-   Windows PowerShell

## Report Contents

The accompanying assignment report contains practical demonstrations and
screenshots for the tasks, followed by a CMD-versus-PowerShell
comparison and a conclusion.

## Conclusion

The assignment provides practical experience with Windows keyboard
shortcuts, command-line file management, system and network
investigation, batch automation, and PowerShell administration. It
highlights how command-line tools can make routine administrative work
faster and easier to repeat.

