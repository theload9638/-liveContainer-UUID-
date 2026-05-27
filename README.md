解决近期 liveContainer 突然发生的UUID报错和无法刷新的问题

sideStore 配对文件问题解决

使用前提：手机和电脑使用数据线连接
可选：sidestore先退出登录

1.安装 https://github.com/jkcoxson/idevice 最新版本<br/><br/>
2.命令行调用 idevice-tools.exe 选择pair<br/><br/>
3.复制生成的内容到一个文本文件中并重命名为pair.plist 传输到手机里<br/><br/>
4.liveContainer->选择进入sideStore->点击Reset Pair File重置配对文件后退出重进<br/><br/>
5.退出后重新进入liveContainer->进入sideStore提示你选择配对文件->导入pair.plist<br/><br/>
6.退出后重新进入liveContainer->刷新证书->应用正常运行<br/>

linux和macos系统
1. chmod +x idevice-tools <br/><br/>
2. ./idevice-tools -> pair  或者 ./idevice-tools pair -> pair.plist (如果可行的话) 
