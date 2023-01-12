**Create SSH Keys and bind**

**设定git全局设定—用户名、邮箱、认证方式**

git config --global user.name "<name>"

git config --global user.email "<email>"

git config --global user.password "<password>"



**查看git设置<按q退出>**

git config --global --list



**创建ssh key**

ssh-keygen -t rsa -C "<email address>"

**设置带4096bit加密的公钥和秘钥**

ssh-keygen -t rsa -b 4096 -C "your_email@example.com"



**验证是否ssh对接成功**

ssh -T git@github.com