**设定git全局设定—用户名、邮箱、认证方式**
git config --global user.name "<name>"
git config --global user.email "<email>"
git config --global user.password "<password>"

**查看git设置<按q退出>**
git config --global --list

**创建ssh key**
ssh-keygen -t rsa -C "<email address>"

**验证是否ssh对接成功**
ssh -T git@github.com

**将本地仓库与远程仓库关联**
git remote add origin <git address>

**查看仓库远程url地址**
git remote -v

**切换为SSH**
git remote set-url origin <ssh git address>

**新建仓库/初始化仓库**
git init

**提交本地仓库更改**
git add .

**提交本地仓库commit**
git commit -m "<commit desc>"

**推送到远程仓库**
git push <origin> <branchname>

**与远程仓库建立链接**
git remote add origin <git address>

**拉取远程分支到本地**
git fetch origin <remote branchname>

**在本地建立分支并切换到该分支与远程建立连接**
git checkout -b <local branchname> origin/<remote branchname>

**拉取分支内容到本地**
git pull origin <remote branchname>