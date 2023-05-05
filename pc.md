## Research Questions 

Now that you are all set up, it's time to learn a little more about the tools of the trade. Edit this file and answer the following questions. You are going to need to start familiarizing yourself with the [GitHub docs](https://docs.github.com/en). Docs (short for documentation) are the instructions on how to use a languge or program. A large part of your job as a developer will be learning how to read and work with documentation. Please reference the GitHub docs when answering the questions below. If you cannot find what you are looking for in the docs, you can always start to practice your Google skills!

1. What is Git?
Git is an open source program for tracking changes in text files. It was written by the author of the Linux operating system, and is the core technology that GitHub, the social and user interface, is built on top of.
2. What is the difference between Git and GitHub?
Github is a cloud-based Git repository hosting service that can be interacted with by using Git.
3. Why do we create a branch?
We create a branch in order to make and track changes to our code without making changes to the master, or "live" version of the repository.
4. What is the purpose of a Pull Request?
A pull request allows the author of a repository to incorporate or reject the changes you have made to the code in a repository.
5. What is the command you can use to switch between branches? For example you are working on the FIRSTNAME-LASTNAME branch and you want to switch back to main.
git checkout master
6. Explain the difference between `git fetch`, `git merge` and `git pull`. What does each command do?
Git fetch will copy all of the changes from a remote branch into your local repository without making any changes to your working directory.
Git merge will copy all of the changes from your local repository to your working directory.
Git pull is used to copy all of the changes from a remote branch into your local repository and working directory. It is essentially a fetch command, followed by a merge command.
7. What is a merge conflict?
A merge conflict occurs when people make different changes to the same line of the same file, or when one person edits a file and another person deletes the same file. The merge conflict must be resolved before you can merge the branches. Branches can be used to avoid these conflicts.
8. How do you resolve a merge conflict?
Use the resolve conflicts button on the pull request of the commit that has a merge conflict. If the merge conflict isn't too complex, it can be solved this way. The resolver will take you through each conflict, allowing you to decide whether to keep your branch's changes, the other branch's changes, or create a new branch which may incorporate changes from both branches.