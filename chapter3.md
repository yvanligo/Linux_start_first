# 第三章 文件
#### 查看文件
```
cat 文件名 正序
tac 文件名 倒序
-n 显示行号
more
enter 向下一行
space 向下一屏
h 帮助
q 退出
只看开头一行：head -n 1 文件 
只看结尾一行：tail -n 1 文件
```
#### 变更文件所有者
```
sudo chown 所有者 文件名
```
#### 修改文件权限
```
1.chmod 权限码 文件名
2.chmod go-rw 文件名 g、o、u代表group、others、user，+和-表示权限的加减
```
#### 文件写入
```
echo "内容">文件名
```
#### 文件删除
```
rm 文件名
rm 文件名 -f(删只读文件)
```
#### 文件移动
```
mv 文件名 目录名
```
#### 文件重命名
```
mv 旧文件名 新文件名
rename 's/\.txt/\.c/' *.txt （使用perl正则表达式批量替换文件后缀为.c）
```