保存到APP查看
下载印象笔记
git
本地部署
1、整理文件结构
2、创建仓库
登录后，点击右上角 + → New repository
仓库名随意，比如 zonnet-website
Public（公开）
Initialize with README 勾选也可以，不勾选也行
创建仓库
3、上传代码（用gitbash）
cd "C:\Users\ylq\Desktop\ZONNET_Website" 定位文件路径
git init 初始化Git仓库
git remote add origin https://github.com/你的用户名/zonnet-website.git 关联远程仓库
git add .  添加文件
git commit -m "首次上传网站文件" （""里随便，为注释）
git push -u origin master 推送到github







gitkraken

push 上传到远程仓库
pull 拉回到本地仓库
merge 可以用最基本的pull



提交改写 Amend
对已提交的文件或者提交信息进行修改  修改后勾选amend即可 这个操作并不会创建新的提交而是修改已经存在的提交
最好对本地提交使用 如果提交已经被推送到远程服务器以后 别人可能拉取到你的提交 这时候再去修改提交历史 可能让每个人的提交历史不一致

分支 Branch
将发布版本和实验版本区分开

合并分支Merge Branches

暂存 Stash
恢复暂存 pop


变基Rebase（类似merge） 类似嫁接 不会出现分叉 更加简洁
pull(rebase)通过使用变基拉取



快进 Fast Forward 让master指针指向最新的这个提交

签出 Check out 回退之前版本查看源代码或者改bug
checkout-rebase-fast forward

撤销操作Undoing
操作都被记录在reflog引用日志  undo和redo只能修改本地代码仓库

撤销已提交代码 revert  没有直接修改历史而是做了一个反向的操作





