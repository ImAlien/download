##Clash for windows
### mac 常见问题
* 打开应用提示文件已损坏
  > 网络下载应用被 Apple 添加隔离标识，终端输入命令解除即可：
  
  `sudo xattr -r -d com.apple.quarantine /Applications/Clash\ for\ Windows.app`
* 端口为0
  > 查看端口是否被占用，将进程杀死即可
 
  `sudo lsof -i tcp:7890`
  
  `sudo kill -9 pid`
## typora

typora收费了，离线下载地址：https://typora.io/releases/all

深色主题：[路径](./dark.css)
## 坚果云
用于同步typora笔记
https://www.jianguoyun.com/s/downloads

## Easy Connect
下载地址： https://sslvpn.zjweu.edu.cn/com/installClient.html



