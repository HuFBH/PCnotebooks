# 使用SSH挂载远程文件夹

### 1、简介

​	使用ssh连接两台主机后，可以使用ssh的文件系统工具sshfss实现远程挂载。



### 2、操作

```bash
# 安装sshfs
udo apt-get install sshfs

# 挂载远程
sshfs Username@IPaddress:Path mount_path

# 卸载远程
umount -v mount_path
```

