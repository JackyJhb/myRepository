#!/bin/bash

echo "This's my first commit"

echo "It's so beautiful!"


ls -al ./

git stash save test.bak
git stash list
git stash pop
git stash applay

git status .
git add .
git commit -m "xdsdfafd"
git push origin master


git log  
git reset --hard commit-id
git push origin HEAD --force

git stash list
git stash save "ssasdfa"
git stash pop
