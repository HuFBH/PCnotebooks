# 本地搭建SSH服务

### 1、简介



### 2、操作

```bash
# 本机查询SSH服务
sudo ps -e | grep ssh

# 开启SSH服务（尝试）
sudo /etc/init.d/ssh start

# 安装SSH服务，默认启动
sudo apt-get  install openssh-server

# 再次查看SSH服务，或开启服务；
# 查看服务状态
sudo service ssh status

# 其他操作：关闭服务、重启服务
sudo service ssh stop
sudo service ssh restart
```

