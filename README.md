# UHF RFID 资料包

感谢来到此仓库，本仓库代码、文档均为资料收集。

因本人前段时间从事 UHF RFID「超高频射频识别」二次开发，经过一段时间观察发现：国产设备的通信协议几乎全部一致（猜测是否是来自同一内部厂家？），故收集一下方便自己和大家后期使用。

如有补充和疑问欢迎提交 Issue。

- USB 设备：指使用 USB 直连到电脑的小型设备（手掌大小），主要用于发行标签。
- 一体机：指使用网线或串口通信的较大型设备（13寸 Mac 大小），主要用于感应标签。
- 分体机：指使用网口通信的较大型设备，一台主机连接多条感应天线，主要用于感应标签。

另外，一体机的 C# SDK 我进行了二次封装，使之更匹配 OOP 思想，可参见：<https://github.com/wi1dcard/UHFReader.NET>