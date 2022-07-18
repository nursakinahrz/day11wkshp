# Workshop 11 Instruction


### Maven commands

1. mvn
2. mvn compile
3. mvn package
4. mvn clean package
5. mvn clean
6. mvn clean package spring-boot:run
7. mvn spring-boot:run

## Git commands
1. git init
2. git remote add origin _______ (insert your link)
3. git add . (to add the files)
4. git status (make a habit to check)   
5. git commit -m "commit message details"
6. git push -u origin master (then you will be prompted password)

7. git pull <remote> <local>
8. git branch (see all branches in the machine)
9. git branch -a (to see everything and locally)
10. git branch -delete <branch name>

the master is the main branch. 

11. git checkout -b develop master (it will create a reference)
12. so when typing git add . (you add to develop branch)

13. git push -u origin develop (push to remote git develop branch)

14. git checkout master 
15. git merge develop (merge changes done in develop branch into master branch)

16. git push -u origin master

// make changes in master, and need to syn this change to develop branch
// assume changes has already been checked into master branch

git checkout develop
git merge master (merge changes done in master branch into develop branch)
git push -u origin develop