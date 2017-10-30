# [FeijaoUK.github.io](https://feijaouk.github.io)

## github 101

---

![Harder Better Faster Stronger](https://feijaouk.github.io/harder_better_faster_stronger.jpg)

---

## How to change repository name or folder

> thanks to [developius](https://gist.github.com/developius/c81f021eb5c5916013dc)

```shell
git remote set-url origin git@github.com:feijaouk/feijaouk.github.io
```

--- 

## How to build your [github.io](https://github.com) page

> thanks to [github.com](https://pages.github.com/)

* 1 -  Create a repository
```shell
username.github.io
```

* 2a - Clone repository using **https**
```shell
git clone https://github.com/username/feijaouk.github.io
```

* 2b - or Clone a repository using **ssh**

```shell
git clone git@github.com:feijaouk/feijaouk.github.io.git
```

* 3 - Create index file

```shell
index.html or index.md

cd username.github.io
$echo "Hello World" > index.html
```

* 4 - **Add** it, **Commit** it, and **Push** it!

```shell

# after changing or updating your files

git add --all

git commit -m "index v2"


git push -u origin master

```
