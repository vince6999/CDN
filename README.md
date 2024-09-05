vi /etc/hosts


#添加以下内容，记得替换为你自己搭建的授权IP 
127.0.0.1 auth.cdnfly.cn monitor.cdnfly.cn



然后ping 授权服务器域名查看是否正确
ping auth.cdnfly.cn



1.搭建授权端

2.修改master机器hosts文件，然后安装主控

3.修改slave机器hosts文件，然后安装被控
