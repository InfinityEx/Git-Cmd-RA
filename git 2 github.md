**Create SSH Keys and bind**

**�趨gitȫ���趨���û��������䡢��֤��ʽ**

git config --global user.name "<name>"

git config --global user.email "<email>"

git config --global user.password "<password>"



**�鿴git����<��q�˳�>**

git config --global --list



**����ssh key**

ssh-keygen -t rsa -C "<email address>"

**���ô�4096bit���ܵĹ�Կ����Կ**

ssh-keygen -t rsa -b 4096 -C "your_email@example.com"



**��֤�Ƿ�ssh�Խӳɹ�**

ssh -T git@github.com