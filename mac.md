## Research Questions 

Now that you are all set up, it's time to learn a little more about the tools of the trade. Edit this file and answer the following questions. You are going to need to start familiarizing yourself with the [GitHub docs](https://docs.github.com/en). Docs (short for documentation) are the instructions on how to use a languge or program. A large part of your job as a developer will be learning how to read and work with documentation. Please reference the GitHub docs when answering the questions below. If you cannot find what you are looking for in the docs, you can always start to practice your Google skills!

1. What is Git?
Git is a tool used to manage mutliple versions of source code edits that are transferred to files in a Git repository.
2. What is the difference between Git and GitHub?
Git is used to manage changes to the code, while GitHub serves as a location to upload and track the trail of all changes made to the code.
3. Why do we create a branch? 
Branches are like a snapshot of the changes made by the programmer. It allows for each change to be isolated from the master branch so that the changes can either be merged or discarded without affecting the source code.
4. What is the purpose of a Pull Request?
Pull requests let others know about code changes made by the programmer.
5. What is the command you can use to switch between branches? For example you are working on FIRSTNAME-LASTNAME branch and you want to switch back to main.
cd ..
6. Explain the difference between `git fetch`, `git merge` and `git pull`. What does each command do?
git fetch shows updates that were made without merging the updates; git pull shows the updates and merges them; git merge combines the isolated branch used to make changes with the main branch.
7. What is a merge conflict?
Merge conflicts happen when braches with competing commits are merged, causing confusion over which changes should be incorporated in the final merge. This can happen when mnultiple, differing changes are made to the same line in the same file within a repository. This can also happen if one person edits a file and another person deltes the file.
8. How do you resolve a merge conflict?
Merge conflicts can be resolved with a new commit before merging the branches that are conflicting.
