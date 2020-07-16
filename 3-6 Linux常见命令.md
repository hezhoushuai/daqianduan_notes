# Linux常见命令

1. 链接服务器

   ssh -p 27822 username@ip

2. 查看操作系统版本

   lsb_release -a

3. 查看linux内核命令

   uname -a

4. 查看磁盘空间的占用情况

   df -Th

5. echo '123123' >> test.text

   添加到最后一行

6. exho '123123' > test.txt

   覆盖文件内容

7. rm -r testdir/

   删除testdir目录

8. 下载

   ​	wget 链接

   

9. 解压

   tar zxvf z x解压  v 显示所有解压过程  f 同等归档文件

10. 压缩文件

    tar zcvf  要压缩成的文件名  要压缩的文件  c 压缩

11. 查看进程

    ps -ef | grep docker

12. 查杀进程

    kill -9 进程号 强制杀出进程

13. service ssh status 查看状态 service sshd restart 重启ssh

14. systemctl status firewall.service

    

