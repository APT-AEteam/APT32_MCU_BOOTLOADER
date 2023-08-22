# 爱普特bootloader库
# 概述
BootLoader库提供了爱普特不同系列芯片的升级代码。用户可以直接在该库上进行二次开发。其代码文件结构如下：

<code>
├─bootloader                                  //bootloader代码主体，内部结构可参考csi代码结构
├─doc                                         //文档目录，内含BootLoader使用说明文档 
└─tool                                        //工具目录，内含升级用的上位机软件 （由于110和171是主从机的升级方式，故没有上位机软件）
</code>

# 说明
本仓库是爱普特芯片bootloader库的入口，所有的bootloader都可以在此找到。目前提供bootloader代码的芯片有 APT32F103X , APT32F173X。更多芯片及其csi代码持续更新中，敬请期待~

# 内容

## bootloader代码库
该部分用于显示各芯片bootloader代码仓库。
|csi demo|说明|
|:----------|:-----------|
[APT32F103X_bootloader](https://github.com/APT-AEteam/APT32F103X_Bootloader.git) |APT32F103X芯片的bootloader程序仓库
[APT32F173X_bootloader](https://github.com/APT-AEteam/APT32F173X_Bootloader.git) |APT32F173X芯片的bootloader程序仓库
