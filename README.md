This repository contains the contents of Biocomputing project-1. 
data/ - contains all FASTA and PDB files retrieved 
scripts/ - all shell scripts
results/ - output files
In this project, Linux and Biopython has been used.

Process for GitHub uploading:
1. A local repository called Biocomputing_project1 was created
2. New folders - data,scripts,results were created using the 'mkdir' command
3. All FASTA and PDB files concerned with this project were added to data/
4. All shell scripts concerned with this project were added to scripts/
5. All output files produced as a part of this assignment were added to results/
6. All the files were added using the 'cp' function
8. The local directory was initialized using 'git init' command
9. The folders were staged, committed and pushed into newly created GitHub respository called Project-1-Biocomputing


Commands used and their meaning:
1. mkdir command: used for creating new folder
2. cd command: to change directory
3. cp command: Used for copying the files from one location to another
4. git init command:  used for initializing and create an empty git repository
5. git status command:  it shows the status of the working directory- in which branch we are present, if files are tracked or untracked, and if tracked, if are they committed and ready to be staged. 
6. git add command: used for tracking files. This stages the changes to be included in the next commit
7. git commit command:  after staging changes using git add command, this command is used to capture a snapshot of currently staged changes. These changes are recorded in the local repository.
8. git remote add origin command:  this establishes a connection between the local repository and the remote git repository. This enables us to use git pull and push commands further.
9. git branch -M command:  to rename a git branch locally. (A branch is a separate workspace which enables us to make changes, experiment with new ideas, develop new features without affecting the main project)
10. git push command:  to upload the local repository files to the remote git repository
