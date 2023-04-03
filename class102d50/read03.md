# Read:03-Revisions and the Cloud

## Version Control

*Version* control is a tool that helps you keep track of different versions of a file or group of files by recording any changes made. It lets you go back to an older version of a file or project, see what changes have been made and who made them, and compare the differences. With a version control system, fixing mistakes in your files becomes much easier.

### Cloning in Git

Imagine you have a digital notebook filled with all your notes, drawings, and ideas. Git is a tool that helps you organize and keep track of changes in your notebook. Now, let's say your friend wants a copy of your notebook so they can add their own ideas or make some changes.

"Cloning" in Git is like making an exact copy of your notebook for your friend. They get their own notebook with all the pages and notes you've made so far. This way, they can work on it separately without affecting your original notebook. Later on, you can combine your notebooks, keeping track of what each person has added or changed. That's how Git helps people collaborate and work together on projects.

## Commands to track:

### To track and stage files in Git, use the following command:

* csharp
* C-opy code
* git add <file_name>
* Replace <file_name> with the specific file you want to track and stage. To stage all files, use git add ..

To take a snapshot of your changed files (create a commit), use the following command:

* sql
* Copy code
* git commit -m "Your commit message here"
* Replace "Your commit message here" with a brief description of the changes you made in the files.

To send your changed files to GitHub, use the following commands:

* First, connect your local repository to the remote GitHub repository with:
* csharp
* Copy code
* git remote add origin <repository_URL>
* Replace <repository_URL> with the URL of your GitHub repository.

Then, push your changes to the GitHub repository using:

* perl
* Copy code
* git push -u origin <branch_name>
* Replace <branch_name> with the name of the branch you want to push your changes to, usually main or master.
