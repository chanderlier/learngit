配置
```sh
git config --global user.name "chanderlier"
```
```sh
git config --global user.email "dieser@163.com"
```

初始化当前目录
```sh
git init
```
将当前目录下的所有文件提交到暂存区
```sh
git add .
```
改名并提交到暂存区
```sh
git mv [file-original] [file-renamed]
```
提交到仓库区
```sh
git commit -m 'message'
```
直接提交到仓库区
```sh
git commit -a
```
下载
```sh
git clone  git@github.com:chanderlier/studypython.git
```
```sh
git remote add (alias) git@github.com:chanderlier/studypython.git
```
列出所有分支
```sh
git branch -a 
```
列出远程分支
```sh
git branch -r 
```
创建分支
```sh
git branch [branch-name]
```
切换到某个分支
```sh
git checkout [branch-name]
```
切换回上个分支
```sh
git checkout -
```
删除分支
```sh
git branch -d [branch-name]
```
下载远程仓库的所有变动
```sh
git fetch [remote]
```
显示所有远程仓库
```sh
git remote -v
```
取回远程仓库的变化，并与本地分支合并
```sh
git pull [remote] [branch]
```
推送所有分支到远程仓库
```sh
git push [remote] --all
```
恢复暂存区的指定文件到工作区
```sh
git checkout [file]
```
```sh
git checkout .
```
