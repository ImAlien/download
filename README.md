## Clash for windows
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

## Java开发环境
JDK1.8 下载 ：https://www.oracle.com/java/technologies/downloads/#java8
#### 环境变量配置
* 变量名：JAVA_HOME
* 变量值：C:\Program Files (x86)\Java\jdk1.8.0_91        // 要根据自己的实际路径配置
* 变量名：CLASSPATH
* 变量值：.;%JAVA_HOME%\lib\dt.jar;%JAVA_HOME%\lib\tools.jar;         //记得前面有个"."
* 变量名：Path
* 变量值：%JAVA_HOME%\bin;%JAVA_HOME%\jre\bin;

