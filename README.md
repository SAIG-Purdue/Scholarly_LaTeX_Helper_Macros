# Scholarly LaTeX Helper Macros

Collection of clean and helpful custom LaTex macros for simplifying scholarly publication generation. 

It is intended to be used as Git submodule or subfolder in LaTex projects.

### Usage Requirements
These macros assume the following LaTeX Project structure:

- __main LaTeX document file__: This is the main file for the LaTeX project. This file should be focused on macro structure and formatting for the document and must include the desired macro files.
- __"Sections"__: Directory that contains all of the files that contain the actual document content for the document (*This is needed for the section loading macros*)
- __"Figures"__:  Directory that contains all of the files used as figures (*This is needed for the figure add/insertion macros*)
- __"Tables"__:   Directory that contains all of the tabular sections that define each full table in the document. 
                  *Each table's main tabular region must be saved as a separate file*, in order for the Table add macros to be able to pull in the content and apply the proper formatting for it.
            
