1. sudo apt install git

2. create directory ---> git init

3. do something ---> git add . ---> git commit -m "message" // git commit -a

4. git log 

5. git reset --hard reflog // git reset --hard HEAD^ ---> the last version

6. git status

7. git checkout -- <file> ---> drop modify

8. git reset HEAD <file> ---> drop staged.

9. git diff HEAD -- <file> // git diff HEAD^ HEAD

10. rm <file> ---> delete file // git rm <file> ---> delete & stage file

11. git log --pretty=oneline // show fully

12. git branch // show all branches

13. git checkout -b dev // create a new branch

14. git checkout <branch name> // switch to other branch

15. git merge <branch name> // fast merge

16. git log --graph --pretty=oneline

17. git merge --no-ff -m "no fast-forward merge" dev

18. git stash // save branch temperally

19. git stash list // stash list
 
20. git stash pop // pop up stash context

21. eval "$(ssh-agent -s)" ---> ssh-add
