### AndSyncTouch

安卓点击同步器[XPOSED_MODULE]

将A手机操作同步到B手机，支持更多A->[B C D E F G H]

### 原理解析

本质上是在两台不同的手机上(也可以是同一台手机)，录制然后重放点击操作。

完成整个功能只需要三个步骤:

- A手机操作轨迹录制保存

- A的轨迹文件传输到B手机上

- B手机读取轨迹进行复现操作

如果是同一个手机，则无需传输过程。


### 传输服务器

compile "org.java-websocket:Java-WebSocket:1.5.3"



