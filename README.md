# Automated-File-Sorted-System
Developed an automated file sorting system in Python to organize files by extension within a specified directory. The script lists files, extracts extensions, creates necessary subfolders, and moves files accordingly. Utilizes os for directory operations and shutil for file movement, with comprehensive error handling.

**Key Features:**

1) **Directory Listing:** The script begins by listing all files in the specified source directory.
2) **File Extension Extraction:** For each file, it extracts the file extension to determine the appropriate subfolder.
3) **Folder Creation:** It checks if a subfolder for the file extension already exists. If not, it creates the necessary subfolder.
4) **File Movement:** The script moves each file from the source directory to the corresponding subfolder based on its extension.
5) **Error Handling:** Comprehensive error handling ensures that any issues encountered during the process are caught and reported.
   
**Technologies Used:**

**Python:** The core programming language used to develop the script.
**os module:** Utilized for directory and file path operations.
**shutil module:** Used for moving files between directories.

**Example Workflow:**

**Initial State:** The source directory contains various files with different extensions (e.g., .txt, .jpg, .xlsx).
**Processing:** The script runs, identifying each file's extension and creating corresponding subfolders if they don't exist.
**Final State:** Files are moved into their respective subfolders, such as 'txt', 'jpg', and 'xlsx', providing a well-organized directory structure.

This automated file sorting system can be particularly useful for managing downloads, organizing project files, and maintaining a tidy workspace, ensuring quick and easy access to files based on their types.
