# ChatGPT Code Collector: Combine and Export Folder Code Files to PDF and TXT



## Overview
This is a React application that allows users to select a folder containing code files, combine the contents of the files, and export them to PDF and TXT formats. The application also provides an option to edit ignored patterns, which determines which files or folders to exclude from the selection.
## Features
* Select a folder containing code files
* Combine the contents of the selected files
* Export the combined contents to PDF and TXT formats
* Edit ignored patterns to exclude specific files or folders from the selection
## How to Use
1. Click the "Select Folder" button to select a folder containing code files.
2. The application will display a tree view of the selected folder, allowing you to select specific files or folders to include in the export.
3. Click the "Read Selected Files" button to combine the contents of the selected files.
4. Click the "Export to PDF" or "Export to TXT" button to export the combined contents to the desired format.
5. Click the "Edit Ignored Patterns" button to edit the ignored patterns, which determines which files or folders to exclude from the selection.
## Code Structure
* The application is built using React, with a single component (App) that handles the folder selection, file reading, and export functionality.
* The IgnoredPatternsEditor component is used to edit the ignored patterns.
* The application uses the jsPDF library to generate PDF files and the Blob API to generate TXT files.
## Dependencies
* jspdf: for generating PDF files
* primereact: for UI components
* react: for building the application
