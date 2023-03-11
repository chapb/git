# git
About Git and GitHub



## Update Git

[Link](https://www.howtogeek.com/759319/how-to-check-and-update-your-git-version/)

`git update-git-for-windows`



## Wipe GitHub History

### No Submodules

Wipe local history: `rm -rf .git`.

Recreate the repo from the current contents:

```
git init
git add .
git commit -m "Initial commit"


?? git gc --aggressive --prune=all
```

Push to remote:

```
git remote add origin git@github.com:<YOUR ACCOUNT>/<YOUR REPOS>.git
git push git push --mirror --force
```


### Submodules




