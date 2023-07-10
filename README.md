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

typora收费了，离线下载地址：~~https://typora.io/releases/all~~
不知道为什么，Windows 测试版的版本 0.10 和 0.11 安装后提示不能使用，估计内置了倒计时吧。


版本 0.9 安装后，不会提示，还能使用。
https://www.cnblogs.com/ioufev/articles/15610121.html

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

---

### VS

激活：

https://www.skyfinder.cc/2021/11/12/visual-studio-2022-key/

https://www.cnblogs.com/fanqisoft/p/15530729.html

2019:NYWVH-HT4XC-R2WYW-9Y3CM-X4V3Y

* vcpkg

---

### VSCode
![image](https://github.com/ImAlien/download/assets/35003534/959fa4c1-f353-49da-980e-2565ef8ca788)

#### 插件：

live server： 保存时实时显示， 配合设置中自动保存更好

auto rename tag: 更改标签后自动改后面的标签

auto close tag : 自动补全尾标签

c/c++: c++环境

#### C++环境：



---

### Steam

常用游戏

---

### 工具

snipaste

wps

### python

---

下载安装python即可

### 常用软件

---

钉钉

qq

微信



