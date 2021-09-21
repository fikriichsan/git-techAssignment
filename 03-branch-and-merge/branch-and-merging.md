# Branch and Merge

1. What does git clean do?
    > git clean a convenience method for deleting untracked files in a repo's working directory.
2. What do the -d and -f flags for git clean do?
    > -f or --force is option initiates the actual deletion of untracked files from the current directory. -d is option tells git clean that you also want to remove any untracked directories
3. What git command creates a branch?
    > git branch [branch-name]
4. What is the difference between a fast-forward and recursive merge?
    > fast forward merge : In this most commonly used merge strategy, history is just one straight line.
    > Recursive Merge : In Recursive merge, after you branch and make some commits, there are some new original commits on the ‘master‘. So, when it’s time to merge, git recurses over the branch and creates a new merge commit.
5. What git command changes to another branch?
    > git checkout [branch-name]
6. How do you remove modified or deleted files from the working directory?
    > we can use this commands "git rm [file-name] and "git commit -m "[message]"
7. What git command deletes a branch?
    > git branch -d [branch-name]
8. What does the git diff command do?
    > Diff command is used in git to track the difference between the changes made on a file.
9. How do you remove files from the staging area?
    >  we can remove file frome the staging area with this command "git reset [file-name]"
10. How do merge conflicts happen?
    > Merge conflicts can happen when merging a branch, rebasing a branch, or cherry picking a commit.