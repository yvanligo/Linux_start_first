# 第二章 用户
#### 查看用户
who
```
-a 打印能打印的全部
-d 死掉的进程
-m 同 am i 
-q 当前用户数及用户名
-u 当前用户登录信息
-r 运行等级
```
##### 新建用户
```
sudo adduser xxx 'uersadd'只创建用户，需要用passwd 用户名设置密码
切换用户
su -l xxx
退出用户
ctrl+d
```
#### 添加用户到sudo组
|命令|说明|
|--|--|
|sudo 当前用户||
|输入密码||
|groups 新用户|查看用户的分组|
|sudo usermod -G sudo 新用户| 添加新用户到组|
|sudo deluser 新用户 --remove -home| 删除用户|