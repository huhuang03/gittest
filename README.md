just test git
gittest
=======

* 创建一个本地分支跟踪远程分支

git checkout -b fork origin/fork

or just convience for git 1.6.2 above:

git checkout --track origin/fork

* 推送本地分支到服务器

if has tracked, and push current branch:

git push

push the specialed branch
git push (远程仓库名) (本地分支名):[(远程分支名), 如果省略的话，则推送到于本地分支名一样的分支上]
