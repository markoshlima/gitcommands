# gitcommands

**[ADD]**

git submodule add https://github.com/[user]/[project]

**[LIST]**

git submodule--helper list

**[PULL FROM MAIN]**

{ALL REPO}

git pull --recurse-submodules 

git submodule update --remote --merge

{ONE REPO}

git pull

git submodule update --remote --merge

**[PUSH FROM MAIN]**

{INSIDE EACH REPO CHANGED}

git add|commit|push

{INSIDE MAIN}

git add|commit|push