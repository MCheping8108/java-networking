# ☕Java 网络编程
来源[菜鸟编程-网络编程](https://www.runoob.com/java/java-networking.html)

# 🏃‍如何运行？
1. 下载Java17(JDK)以上的版本。我选择了Java19[点击这里](https://download.oracle.com/java/19/latest/jdk-19_windows-x64_bin.exe)<br>
**最好是JDK**


2. 配置Java环境<br>
如果你下载了压缩包，你得手动配置Java环境，这样子很麻烦。如果你是Windows电脑，我强烈建议你下载exe安装包


3. 安装完毕后请在命令窗口提示符输入下面代码👇

```cmd
java
```

看到这样的说明安装成功了
![Snipaste_2022-11-22_14-56-46.png](https://s2.loli.net/2022/11/22/etoTCOaGqc34vV9.png)

4. 输入这下面4行代码就能成功运行

编译
```
javac src/GreetingServer.java
javac src/GreetingClient.java
```

运行
```
java GreetingServer {端口号}
java GreetingClient {端口号}
```

