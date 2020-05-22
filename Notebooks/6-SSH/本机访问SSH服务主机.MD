# 本机访问SSH服务器

### 1、简介



### 2、操作

```bash
# ssh远程登录:ssh NANE@IP
ssh ubuntu@192.168.1.20

# 文件传输
scp -r ubuntu@192.168.3.20:/DIR /DIR
scp ubuntu@192.168.3.20:/PATH /PATH

scp /PATH ubuntu@192.168.3.20:/PATH
```

