# FILE_MANAGEMENT_TOOL

Overview
This tool is a lightweight file management utility designed to simplify file operations within the Ubuntu system. Unlike traditional file managers, this tool provides an interactive way for users to create, delete, and rename files while displaying the directory structure in real-time.

Features
1. File Deletion
Displays the directory structure of the current working directory.
Prompts the user to enter the exact file name with its extension before deleting.
2. File Renaming
Provides three options for renaming files:
Rename a file in the current working directory.
Rename a file in the parent directory.
Rename a file in another directory.
When choosing the third option (other directory), the tool currently has an issue where it searches only in the previous (upper-level) directory. If the user is in the home directory, it does not search beyond it. This will be fixed to allow searching throughout the entire system.
3. File Creation
Asks the user whether they want to:
Create the file in the current working directory.
Place the file inside another directory within the current directory.
If the user chooses to create the file in another directory, they must select the target directory by providing its exact name (case-sensitive).
If the user chooses to create the file without specifying a directory, it will be saved directly in the current working directory.
Upcoming Fixes & Improvements
Fix the search limitation when renaming files in "other directories" so that it searches the entire system instead of only the upper-level directory.
Improve error handling for case-sensitive directory selection to prevent accidental misplacements.
This tool provides a simplified and user-friendly way to manage files while offering flexibility in directory selection. If you encounter any issues or have suggestions, feel free to contribute or report them in the repository.

