# gitsync1/2

foo

sync between two git repos with different flavor.

## v1

```shell
git clone (--bare) https://github.com/s7nio/gitsync1 
cd gitsync1
git remote add upstream https://github.com/s7nio/gitsync2 # fetch & push
git [pull|push] upstream master
```

## v2

```shell
git clone --mirror https://github.com/s7nio/gitsync1 
cd gitsync1.git
git remote update
git push --mirror https://github.com/s7nio/gitsync2
```
