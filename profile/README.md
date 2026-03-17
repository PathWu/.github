## Fetching commits from HIPA repos
1. For ongoing updates from the original, add the original as an “upstream” remote in a normal clone:
```
git clone git@github.com:PathWu/PathWu-BE.git
cd PathWu-BE
git remote add upstream git@github.com:FIIT-HIPA/HIPA-BE.git
git fetch upstream
```
2. Now you can merge upstream branches into yours:
```
git checkout main
git merge upstream/main
git push
```
