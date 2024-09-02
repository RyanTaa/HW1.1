# Title - Homework 1 - Open Source Data Engineering Tools

# Project Description

This project is used as practice for utilizing VSCode and quarto. Students are given the scaffold of this project and are tasked with completing a report and testing quarto by rendering the sample files.

This homework serves two purposes:

1. provide the student an opportunity to learn more about data engineering tools of their interest,

2. introduce the student to the workflow used to submit assignments in this class.

[Here is a link](https://virginiacommonwealth.instructure.com/courses/105097/assignments/966515) to the homework assignment in Canvas.

Your report should be stored in the ``./report`` folder.  Any assets (PNG, JPG, etc.) should be stored underneath in ``./report/assets``.

FURTHER, you must modify this README to make it your own:

* GITHUB provides [good explanations of README.md'(https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-readmes) files,

* Here is a list of example *awesome* README files: <https://github.com/matiassingers/awesome-readme>

Part of your score for this assignment is how well you update/modify this README.

## Files and Folders

*./src* - contains the scaffold QMD file homework 1. Your job is to modify this document and render it to *html*.  The *html* file will
be created in the same *./src* folder.

*./samples* - contains several QMD files. Your job is to render these files and exam the output.  Output for these files will be in the *./docs* folder.

*./docs* - contains resulting files from quarto render operations.  *You should NEVER directly store files in ./docs.* Rather, you should let Quarto maintain the contents of the *./docs* folder using settings in the quarto project file, *_quarto.yml*.

# How to Run/Build This Project

1. The first step is to access the github which provides the skeleton of this project and to download it into a project folder. 

2. Next, you also have to install and setup VSCode, git, and quarto.

# How to Use This Project

1. First, you have to read through all the README files to understand the directions and purpose. 

2. After that, you follow the instructions in the README file in the samples folder to render the qmd files.

3. Next, you can preview the html output files that were created from the qmd files by putting "preview" instead of "render" in the render command.

4. You can then modify the html files to see how it adjusts the rendered graphs.
