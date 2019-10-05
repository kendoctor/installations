# Questions and answers 

## Block command line pushes that expose my email

Since “Keep my email address private”, it will “Block command line pushes that expose my email”. Uncheck it.

## How to remove file or directory in git

> remove local file or directory
```shell script
git rm file 
git add .
git commit -m "file removed"

git rm -r dir 
git add .
git commit -m "dir removed"
```

>r remove remote file or directory
```shell script
git rm file --cached
...
git rm -r --cached dir 
```