# gitcommands

**[ADD]** <br />
git submodule add https://github.com/[user]/[project]

**[LIST]** <br />
git submodule--helper list

**[PULL FROM MAIN]** <br />
{ALL REPO} <br />
git pull --recurse-submodules <br />
git submodule update --remote --merge <br />
{ONE REPO} <br />
git pull <br />
git submodule update --remote --merge

**[PUSH FROM MAIN]** <br />
{INSIDE EACH REPO CHANGED} <br />
git add|commit|push <br />
{INSIDE MAIN} <br />
git add|commit|push 

**[CLONE]** <br />
git clone --recurse-submodules https://github.com/[user]/[project]
