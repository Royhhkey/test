```shell
git remote add origin <name> # 添加远程仓库
git remote rm origin   # 删除远程仓库
git push -u origin master   # 推送本地仓库到远程仓库
git pull origin master   # 从远程仓库拉取最新代码
git pull origin master --allow-unrelated-histories   # 解决合并冲突
git remote update  # 更新远程仓库信息
git checkout -b <name>    # 创建并切换到新分支
git branch -D <name>    # 删除分支
git merge feature-branch   # 合并分支  将名为 feature-branch 的本地分支合并到当前所在的本地分支
git rebase master   # 变基  将当前分支变基到 master 分支
git stash   # 暂存当前工作区的修改
git stash pop   # 恢复暂存区的修改 
git log --oneline   # 查看提交历史
git log --oneline --graph   # 查看提交历史的图形化展示
git diff <file>   # 查看文件修改详情
git branch -a   # 查看所有分支
git branch   # 查看当前分支
git branch -r   # 查看远程分支
git commit -a -m "commit message"   # 提交所有修改

git reset --hard <commit-id>   # 回退到指定提交
git reset --soft HEAD^   # 回退到上一个版本
git reset --hard HEAD^   # 回退到上一个版本
git reset --hard origin/master   # 回退到远程仓库的最新版本


git cherry-pick <commit-id>   # 合并指定提交到当前分支
git rebase -i <commit-id>   # 编辑提交历史
git rebase -i HEAD~3   # 编辑最近 3 次提交
git rebase --abort   # 放弃变基操作
git rebase --continue   # 继续变基操作
git rebase --skip   # 跳过当前提交
git rebase --edit-todo   # 编辑变基 todo
git rebase --autosquash   # 自动合并提交
git rebase --onto <newbase> <commit> <commit>   # 变基到指定提交
```


##### 黄色为 commit-id
![alt text](image.png)