

git config --global --unset https.proxy

本地git clone 项目链接，将远程仓库克隆到本地

新建本地dev分支git checkout -b dev

根据需求作出相应代码的更改

git add .，git commit -m "描述"

因为master分支是保护分支，小组成员没有推送到master的权限，所以git push origin dev推送到远程仓库dev分支

通知管理员进行分支合并
————————————————


