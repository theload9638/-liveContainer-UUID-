解决liveContainer的UUID报错问题

sideStore 配对文件问题解决

使用前提：手机和电脑使用数据线连接
  

1.安装 https://github.com/jkcoxson/idevice 最新版本
2.命令行调用 idevice-tools.exe 选择pair
3.复制生成的内容到一个文本文件中并重命名为pair.plist 传输到手机里
4.liveContainer->选择进入sideStore->Reset Pair File
5.退出后重新进入liveContainer->进入sideStore提示你选择配对文件->pair.plist
6.退出后重新进入liveContainer->刷新证书->应用正常运行


