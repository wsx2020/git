# git

## 查看状态

`git status`　检查已经修改的文件，或者在`oh-my-zsh`下的小叉叉

## 查看日志

`git log` 每一次修改都有相应的记录被记录在案

## 常用添加

1. `git init`　初始化，让文件变为`已修改`状态

2. `git add test.md`　添加到`已暂存`状态

3. `git commit -m "creat a file "`　每一次提交必须要有个注

## 撤回

对于 `git add`:　使用下面的命令，可以从暂存去中删除
`git rm -- cached test.md`

对于 `git commit`: 使用下面的命令，可以将已经提交的状态中撤出
`git checkout --text.md`

`git rest HEAD test.md`｀

