## Research Questions 

Now that you are all set up, it's time to learn a little more about the tools of the trade. Edit this file and answer the following questions. You are going to need to start familiarizing yourself with the [GitHub docs](https://docs.github.com/en). Docs (short for documentation) are the instructions on how to use a languge or program. A large part of your job as a developer will be learning how to read and work with documentation. Please reference the GitHub docs when answering the questions below. If you cannot find what you are looking for in the docs, you can always start to practice your Google skills!

1. What is Git? A version control system for handling coding projects in terms of controlling the version to update and share the project between programmers.

2. What is the difference between Git and GitHub? Git is the version control system while Github is the cloud-based host that handles the management of Git repositories online.

3. Why do we create a branch? To make a separate version of the main repo to allow for changes and updates to be made that don't affect the main repo. It's a way of controlling updates to the code 
without losing track of the original version.
 
4. What is the purpose of a Pull Request? It's a request to the manager of the main repo to review your branch's changes and merge the changes with the main repo.


5. What is the command you can use to switch between branches? For example you are working on FIRSTNAME-LASTNAME branch and you want to switch back to main. git checkout

6. Explain the difference between `git fetch`, `git merge` and `git pull`. What does each command do? git fetch downloads all branches and tags from one or multiple repos. git merge joins two 
branches and its changes to the project together. git pull starts with a 'git fetch' to download changes on a branch and 'git merge' to merge the changes on the local repo.

7. What is a merge conflict? It's an event where Git is unable to automatically resolve differences in the code between two commits, which typically happens when two people make changes to the same 
line of code.

8. How do you resolve a merge conflict? By navigating to "Pull requests" on github and click on "Resolve conflicts". Delete conflict markers and select which version of the line(s) in conflict 
remain. Once complete for all conflicts, click "Mark as Resoled" and then "Commit Merge" to the master repo.
