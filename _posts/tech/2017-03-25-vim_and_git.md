---
layout: default
title: vim and git
categories: tech
---
# vim and git#

## Delete empty line ##
:g/^$/d

## Find previous git commit ##
git reflog

## git remote related ##
git remote add origin git@github.com:username/xxxx.git

git push -u origin master

## git log with graph##
git log --graph --pretty=oneline --abbrev-commit

## git stash ##
git stash

git stash list

git stash apply

git stash drop

git stash pop

git stash list

git stash apply stash@\{0\}

<br>
<br>
<br>
<p>{{ page.date | date_to_string }}</p>
