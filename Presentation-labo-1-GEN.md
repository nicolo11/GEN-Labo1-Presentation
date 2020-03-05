# Présentation du labo 1
## Les commandes github de base

### initialisation d'un git

1. création d'un repo sur github
2. crée un fichier en local sur son PC
3. Rajouter un README.md
4. git init
5. git add README.md
6. **git commit -m "git init"**
7. **git remote add origin** https://github.com/nicolo11/GEN-Labo1-Presentation.git
8. **git push -u origin master**

### Commande classique diff, rest, status, rm, log, show
1. rajout d'un fichier test1.md en local
2. git status
3. git show README.md
4. Rajouter une ligne dans README.md
5. git log
6. git add .
7. git commit -m "étape 2 master"
8. git push
9. git log
10. git reset <ssh commit init>
11. git log 
12. Rajouter une ligne dans README.md
13. git status
14. git add .
15. git commit -m "étape 3 master"
16. git status
17. git rm test1.md
18. git status
19. git add .
20. git commit -m "étape 3 master"
21. git push

### Branch
1. git checkout -b branch1
2. rajout branch1.md
3. git add branch1.md
4. git commit -m "étape 1 branch1"
4. git push origin -u branch1
5. git branch test
6. git branch --list
7. git branch -d test
8. git branch --list
9. git branch -v

### merge & cherry-pick
1. checkout master
2. git diff master..branch1
3. git merge branch1 -m "merge branch1 on master"  
4. git push
5. git diff master..branch1
6. git checkout -b branch2
7. rajout branch2.md
8. git add branch2.md
9. git commit -m "étape 1 branch2"
10. git push origin -u branch2
11. rajout de ligne branch2
12. git add branch2.md
13. git commit -m "étape 1 branch2"
14. git push
15. git checkout master
16. git cherry-pick id commit étape1 branch2
17. git diff master..branch2
18. git checkout branch1
19. git merge branch2 -m "recuperation d info"
20. git push
21. git diff master..branch1
22. git checkout master
23. git add .
24. git commit -m "recuperation info branch2"
25. git push





