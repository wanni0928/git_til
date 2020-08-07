# Day01

## Index
1. vim base
2. git config
3. github pages

## Details
##### develope enviroment
- mac : use default terminal
- windows : [use git bash(https://gitforwindows.org/)](https://gitforwindows.org/)
##### vim base
- $         : a sign suggesting that you are ready
- $ ls      : list segment
- $ ls -l   : list segment with authority
- $ mkdir   : create new directory
- $ rm [filename] : delete file(cannot delete directory)
- $ rm -r dir : delete directory
- $ sudo rm -rf : don't use this if you're not going to destroy your computer.
- $ vim filename : enter vim
##### git config
- $ git config --global user.name `"your_github_username"`
- $ git config --global user.email `"your_github_email"`
- $ git config --gloval core.editor
- $ git config --global core.pager "cat"
- $ git config --global core.editor "vim"

##### git command
- $ git remote add origin `your_https_github_repository_url`
- $ git remote get-url origin
- $ git remote -v
- $ git status
- $ git push -u origin master : -u means upsteam your local repository to git service
- $ git clone `https_github_repository_url`

##### git commit terms
- feat :          feature
- docs :
- conf :
- fix :
- deploy :
- refactor :

Hexo blog

https://www.toptal.com/developers/gitignore
https://wayhome25.github.io/

npm install -g hexo-cli
(sudo npm install -g hexo-cli)