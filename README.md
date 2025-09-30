# DevOps with [Stanley](https://github.com/mwizerwa77)

## Add a submodule (JEST/Todo-deployed-app)

```sh
cd F:\GIT-Push\DevOps

# remove the nested repo manually from git index (it was added prev Dumbly)
git rm -r --cached JEST/Todo-deployed-app

# add it back as a submodule
git submodule add https://github.com/Mchiir/Todo-deployed-app.git JEST/Todo-deployed-app

git commit -m "Add Todo-deployed-app as a submodule"
git push upstream main
```
