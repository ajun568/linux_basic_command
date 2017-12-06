# linux基础命令
> 这是一篇关于Linux基础命令的文档 想系统学习Linux命令的出门左拐
* 创建文件夹
```
mkdir folder
```
* 展示列表信息
```
ls 列表文件名
ls -a 列表文件名 <包括隐藏文件>
ll 列表文件详情信息
stat file_name/folder 显示指定文件/文件夹详情信息
```
* 查看当前所在位置
```
pwd
```
* 进入文件夹
```
cd folder
cd .. <返回上一文件夹>
```
* 删除操作
```
rm -rf folder <删除文件夹>
rm file_name <删除文件>
```
* 拷贝
```
cp file_name1 file_name2 <拷贝file_name1并命名为file_name2>
```
* 重命名
```
mv file_name1 file_name2
```
* 移动
```
mv file_name folder/file_name <把file_name移动到folder文件夹下>
```
* 查看文件内容
```
cat file_name <全部信息>
head file_name <前一部分信息>
tail file_name <后一部分信息>
head -n 1 file_name <前一行>
tail -n 5 file_name <最后5行>
```
* 清屏
```
clear
```
* **echo讲解**
```
echo content <直接输出content>
echo *.jpg <找到所有该目录下以.jpg结尾的文件>
```
* 查看当前系统信息相关操作
```
who <当前登录用户信息>
whoami <当前操作用户>
uname <显示系统信息>
hostname <显示主机名>
top <显示当前耗费资源最多的信息>
ping 测试网络联通状态
netstat 显示网络状态信息
ifconfig 查看网络状态
du -h 显示目录大小及信息
df -h 显示磁盘大小及信息
```

```
