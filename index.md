# github 101

## How to change repository name or folder
> thanks to [developius](https://gist.github.com/developius/c81f021eb5c5916013dc)

```git remote set-url origin git@github.com:feijaouk/feijaouk.github.io```



## How to build your [github.io](https://github.com) page
> thanks to [github.com](https://pages.github.com/)

1  - Create a repository - ```username.github.io```

2a - Clone repository (https) - ```git clone https://github.com/username/feijaouk.github.io```
2b - Clone a repository (ssh) - ```git clone git@github.com:feijaouk/feijaouk.github.io.git```

3  - Create ```index.html``` or ```index.md```

  cd username.github.io
  $echo "Hello World" > index.html

4  - Push it - Add, commit, and push your changes:

```git
# after changing or updating your files

git add --all

git commit -m "index v2"


git push -u origin master

```
