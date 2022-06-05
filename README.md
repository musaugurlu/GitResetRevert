# GitResetRevert

Sample repository to play with git reset and revert

## Git Commands

### Git Add/Remove Files to Tracking

-   `git add <file name> <another file> <the other file>` --> Add single or multiple files
-   `git add -A` --> Add All files

-   `git rm --cached <file name> <another file> <the other file>` --> Remove single or multiple files from tracking

### Git Commit

-   `git commit -a -m "<Commit Message>"` --> Add files to tracking AND commit
-   `git commit -m "<Commit Message>"` --> Commit tracking changes (in the files being tracked)

### Git Push

-   `git push --set-upstream origin <branch name>` --> set upstream(remote) branch for the local branch and push the changes to remote (synch)
-   `git push origin` --> push changes to the upsteam that is set with the --set-upstream (-u) flag
-   `git push origin HEAD` --> push changes to the remote HEAD.

### Git Reset

-   `git reset --soft <branch name or commit SHA id>`
-   `git reset --mixed <branch name or commit SHA id>`
-   `git reset --hard <branch name or commit SHA id>`
