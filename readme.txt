如何在github中获取项目权限？
1 配置git
git config --global user.name "XXX"
git config --global user.email "XXX@XXX"

2 生成密钥对
ssh-keygen -t rsa -C "上面的邮箱"
连续点击三次回车
cd ~/.ssh
pwd
进入上面指令返回的路径将id_rsa.pub中的字符给管理员开启权限


上传文件等至git hub
(1).git add .  //（将所有文件添加到仓库,如果在当前路径下,可不加路径直接将所有文件上传;不在当前路径下,加./url）
(2).git commit -m "更新内容" 
(3).git push origin master 
回退代码至为更改前的最近一版
git reset --hard Head

git log --列出所有更新的版本

git reset --hard +任意更新的版本名，即可回退至该版本



