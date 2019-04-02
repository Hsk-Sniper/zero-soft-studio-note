### Git Operate
***
##### 1. 配置个人信息（用户名和邮箱)
>- git config:
   - `git config [--global] <user.name> "用户名"`
   - `git config [--global] <user.email> 邮箱`
##### 2. 克隆远程仓库
>- `git clone <url>`
##### 3. 显示状态信息
>- `git status`
##### 4. 添加修改文件到缓冲区
>- `git add [修改过的文件名] [-A]`
##### 5. 提交缓冲区文件到本地仓库
>- `git commit [-m <"修改的内容解释">]`
##### 6. 查看版本信息（历史提交信息）
>- `git log [--oneline]`
##### 7. 回滚到某一版本
>- `git reset [--hard] \<versioncode>`
   - hard:彻底回滚到某一版本
   - soft:回滚到某一版本，只回滚了commit的信息
##### 8. 查看操作记录
>- `git reflog`
##### 9. 初始化（在当前目录下生成一个隐藏的.git文件）
>- `git init`
##### 10. 添加远程仓库/
>- `git remote add <远程主机名,origin> <url>`
##### 11. 将本地分支推送到远程主机
>- `git push -u <远程主机名> <本地分支名> [:<远程分支名>]`
##### 12. 新建分支
>- `git branch <新建分支名>`
##### 13. 切换到某一分支
>- `git checkout <要切换的分支名>`
##### 14. 新建分支并切换到此分支
>- `git checkout -b <创建并切换的分支名>`
##### 15. 获得远程仓库副本
>- `git fetch <远程主机名> <远程分支名>`
##### 16. 分支的合并
>- `git merge <要合并的分支>`

  

  