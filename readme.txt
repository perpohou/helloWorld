如何在github中获取项目权限？
1 配置git
git config -–global user.name "XXX"
git config –-global user.email "XXX@XXX"

2 生成密钥对
ssh-keygen -t rsa -C “上面的邮箱”
连续点击三次回车
cd ~/.ssh
pwd
进入上面指令返回的路径将id_rsa.pub中的字符给管理员开启权限
