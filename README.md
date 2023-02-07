# Git Repository Analyzer

A Program to analyze a Git Repository and collect Information about its commits, test classes and test methods.

## Requirements
* Python 3.x
* Git
* Grep

## Usage
* python software_repository.py [repo_path]
* git clone https://github.com/username/repository.git

Where **'[repo_path]'** is the file path to the Git repository you want to analyze. Replace **'username'** with the username of the repository owner, and **'repository'** with the name of repository you want to clone. 
First you need to clone Git Repository to your computer

##Output
The Program will produce a file named **'output,json'** in the same directory as the program, containing the following information:

*Location of the repository
*Total number of commits
*Information about each commits:
    *Number of test classes
    *Number of test methods
    *List of test classes
    *List of test methods

#Notes

    * The program assumes that the Git repository is valid and that required softwares **(Python, Git, Grep)** is installed on your system
    * Make sure that a file path to the repository is correctly specified. If path is incorrect or the repository does not exist, program will produce an error
