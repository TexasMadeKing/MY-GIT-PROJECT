change from github josh branch


# Create New Project=

mkdir my-git-project

cd my-git-project

touch my_file.py

git init

ls

ls -la

git status

git add

get status

git commit -m "Initial commit"

get status

git remote add origin git@github.com:TexasMadeKing/MY-GIT-PROJECT.git
git push -u origin master

rmdir /s .git

//new branch
git checkout -b Josh
git branch
git checkout main
git checkout Josh

// rebase
git rebase master
git rebase master Josh






echo "# MY-GIT-PROJECT" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/TexasMadeKing/MY-GIT-PROJECT.git
git push -u origin main

…or push an existing repository from the command line

git remote add origin https://github.com/TexasMadeKing/MY-GIT-PROJECT.git
git branch -M main
git push -u origin main
