Varga Kristóf (B)
Magyar Viktor (A)

A: git init
A: git remote add origin 
A: git add .
A: git commit -m "A1"
A: git push origin master
B: git init
B: git remote add origin 
B: git fetch
B: git pull origin master
B: git add.
B: git commit -m "B2"
B: git push origin master
A: git fetch
A: git pull origin master
A: git branch fejlesztes
A: git checkout fejlesztes
A: git add .
A: git commit -m "A3"
A: git push origin fejlesztes
B: git fetch
B: git pull origin master
B: git add .
B: git commit -m "B4"
B: git push origin master
B: git fetch
B: git pull origin fejlesztes
B: git checkout fejlesztes
B: git add .
B: git commit -m "B5"
B: git push origin fejlesztes
A: git fetch
A: git pull origin master
A: git checkout master
A: git fetch
A: git add .
A: git commit -m "A6"
A: git push origin master
B: git fetch 
B: git pull origin master
B: git add.
B: git commit -m "B7"
B: git push origin master
B: git checkout fejlesztes
B: git merge master
A: git add .
A: git commit -m "A8"
A: git push origin master
