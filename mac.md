## Research Questions 

Now that you are all set up, it's time to learn a little more about the tools of the trade. Edit this file and answer the following questions. You are going to need to start familiarizing yourself with the [GitHub docs](https://docs.github.com/en). Docs (short for documentation) are the instructions on how to use a languge or program. A large part of your job as a developer will be learning how to read and work with documentation. Please reference the GitHub docs when answering the questions below. If you cannot find what you are looking for in the docs, you can always start to practice your Google skills!

1. What is Git?
Git is used to tracking changes in the source code, enabling multiple developers to work together on non-linear development.
2. What is the difference between Git and GitHub?
if you have open-source projects that use Git, then GitHub is designed to help you better manage them.
3. Why do we create a branch? 
Git branches are effectively a pointer to a snapshot of your changes. 
4. What is the purpose of a Pull Request?
Once a pull request is opened, you can discuss and review the potential changes with collaborators and add follow-up commits before your changes are merged into the base branch.
5. What is the command you can use to switch between branches? For example you are working on FIRSTNAME-LASTNAME branch and you want to switch back to main.
git checkout 
6. Explain the difference between `git fetch`, `git merge` and `git pull`. What does each command do?
git fetch downloads commits files and refs from a remote repository into your local repo. git merge is a way of putting a fork history back together again. git pull fetch and download content from a remote repository and immediately update the local repository to match that content.
7. What is a merge conflict?
occur when competing changes are made to the same line of a file, or when one person edits a file and another person deletes the same file.
8. How do you resolve a merge conflict?
The easiest way to resolve a conflicted file is to open it and make any necessary changes. After editing the file, we can use the git add a command to stage the new merged content. The final step is to create a new commit with the help of the git commit command.

