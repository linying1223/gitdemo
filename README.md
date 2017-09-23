# gitdemo
# git 初级使用步骤
1 登录github 注册用户账号

2 本地安装git <a href="http://www.bootcss.com/p/git-guide/"> git简易教程</a>

3 运行git clone命令。  如： git clone https://github.com/linying1223/gitdemo.git

git status 查看版本变动

4 使用git add 选择添加需要版本控制的文件，如 git add *

5 git commit -m "本次提交说明"

git log 查看历史提交日志

6 git push


-- 以后每次更新前使用 git pull 更新远程代码，然后使用步骤 4,5,6

# 分支使用
-- 查看所有分支
 git branch

-- 创建从远程仓库获取新的分支
 git checkout -b 要创建的本地分支名 origin/远程分支名

--本地分支切换
 git checkout 分支名

--删除本地分支
 git branch -D 分支

--分支合并
 git merge 分支
