# Git Cheat Sheet

Git Commamds:
1. git init                                     //in root folder
2. rm -rf .git                                  //undo git init
3. git remote add origin <HTTPS/SSH>            //add the repo link on github
4. git clone <HTTPS/SSH>                        //for clone 
5 => git checkout -b <branch-name>              //create a new branch & switch to it at same time
  => git switch -c <branch-name>               //create a new branch & switch to it at same time 
6 =>git checkout <branch-name>                  //simply switch to an existing branch
  =>git switch <branch-name>                   //simply switch to an existing branch
7. git checkout <old-branch-name>               //Checkout to the branch you need to rename
8. git branch -m <new-branch-name>              //Rename branch name locally
9. git push origin :<old-name> <new-branch-name>  //Delete old branch from remote
10. git branch --list                           //to check all branches
11. git rm fileName                             //to remove specific file
12. git log                                     //to knowing all commits
13. git config --global user.name "name"        // for enter username on git
14. git config --global user.email "email"      // for enter email on git -->
<!-- 15. git rm --cached(file name) // for cached file............