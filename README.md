# git_learning
## Something you should **KNOW FIRST**
**This is a example for git usage with GitHub, you need learn how to use, and *build your own branch* with your git learning notes from this master. And if there are something new about git and GitHub, you `SHARE IT` by commit and push your branch**

**Recommend to Use [Atom](https://atom.io/) eiditor , it has a good git&github plugin and well supoort markdown and program languages**

**Before do this you need generate you 'ssh key' and add to your github account**
>[Github help](https://help.github.com/articles/connecting-to-github-with-ssh/)
> After set the SSH Key, You can clone this repository
`git clone git@github.com:HITSZ-LeggedRobotics/git_learning.git`
**For something about markdown writing**
> [Shunyao Wang's Markdown notes](https://github.com/ShunyaoWang/general_notes/tree/master/Markdowns)


> **If you have some notes SHARE IT!**
# Using Git in a Terminal
## 1. Build a Git repository(Locally)
`cd path to you git repository`
### Init you repository
`git init`
**if you want to connect to a repository on github**
`git remote add origin git＠github.com:your_repositry.git`
`origin` is the default name of your remote connection

### Add something in your repository
`git add <filename> or *(all file in the derictory)`
this is add new file or add file which you have changed the content
and the change didn't apply/commit
### Add a commit
`git commit` ||`git commit - m “your description about the commit”`
### push to github
`git push -u origin master`
**add `-u` for the fisrt push**

## Some other git command
- Add a branch
`git checkout -u <branch name>`
-Switch to a branch
`git checkout <branch name>`
**YOU should push the correspond branch name to github
so that you can push to the right branch**
- Fetch
fetch remote repository
`git fetch origin`
- Merge
merge to current repository
`git merge origin/<branch name>`
- Pull
Fetch and merge
`git pull origin <branch name>:<branch name>`

# Using Git and GitHub With Atom
TODO(Shunyao)

# different member cooperated on a repository

![branchs cooperation](pic/branchs.png)

# Reference
1. [廖雪峰Git教程](https://www.liaoxuefeng.com/wiki/0013739516305929606dd18361248578c67b8067c8c017b000)
2. [Git指令](https://www.yiibai.com/git)
