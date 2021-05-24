# exercice bash setup

```
# create project directory
cd ~/dev/workspace # ~ is user's home
mkdir exercice
ll (list)
cd exercice

# setup npm and vite
npm init # create a package.json
npm install -D tailwind postcss autoprefixer vite # download dependencies
vim index.html # create & edit new index.html file 
vim package.json # view, edit the file, add dev vite script
nmp run dev (dev server running) - checking if it works

# initiliase git
git init
git status
vim .gitignore # create and edit .gitignore file, add node_modules/ directory to new line
git add . # add all files to git local repository
git commit -m "initial commit"
git remote add origin https://github.com/marchris93/exercice.git
git push
```