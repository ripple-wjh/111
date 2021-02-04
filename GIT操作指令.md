## GIT操作指令

   1.git add 111.txt----提交到暂存区

2. git commit -m '注释'   ----提交到仓库
3. git status -----显示当前暂存区的状态
4. git log -----显示提交记录
5. git diff HEAD -- 111.txt ---对比区别
6. git reset HEAD 111.txt ----从暂存区中移除
7. git commit -a -m '注释' ----一条命令实现提交到仓库
8. git reset --hard HEAD^ -----回到上一次提交的版本（回退几个版本加几个^）
9. git reset --hard HEAD~1 -----回退几个版本写数字几
10. git reflog ----显示所有提交信息，包括回退
11. git reset --hard 序列号 ----回到哪个版本写那个版本的序列号
12. git log --pretty=oneline ----逐行显示log信息
13. git --help ---显示git指令（英文）
14. git restore 111.txt ----撤销删除
15. git checkout 111.txt ---从版本库中拉取被删除的文件
16. 直接在本地删除后再次提交会在版本库中删除文件
17. git ls-files ---显示仓库中的文件
