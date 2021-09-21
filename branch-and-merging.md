1. git clean removes untracked files from the working tree, files that are not under version control starting from the current directory
2. -d makes git clean recurses into untracked directories as well, -f makes git clean refuse to delete files/directories unless given -f or -i
3. git branch <branchn ame>
4. fast-forward merge  occur when there is a linear path from the current branch tip to the target branch, meanwhile recursive merge happens when more than one valid ancestor is found, creating new virtual ancestor.
5. git checkout <branch name>
6. git checkout <file name> if it yet stagged/commited or git reset <file name> if stagged but yet commited
7. git branch -d <branch name>
8. git diff 
The git diff command displays the differences between files in two commits or between a commit and your current repository. 
10. merge conflict happens when two branches both modify the same region of a file and are subsequently merged. 