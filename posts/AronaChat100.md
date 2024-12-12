---
title: AronaChat1.0.0
date: 2024-11-30
tags: [AronaChat, 1.21.1, NeoForge]
---
## 介绍
AronaChat 是一个用于在 Minecraft 里和AI聊天系统的模组

游戏版本:1.21.1

模组加载器:NeoForge

你不会想知道我是为什么想做这个模组的
## 使用的API
AronaChat使用的是[腾讯元器](https://yuanqi.tencent.com/)API
## 使用方式
将AronaChat1.0.0放入mods文件夹中

运行游戏

在成功的启动游戏后打开config\aronachat-common.toml文件

配置文件是这样的
```aronachat-common.toml
Token = ""
ssistant_id = ""
prefix = "阿罗娜"

Token为你腾讯云的token
ssistant_id为只能体的id
prefix为消息的前缀,一般来说输入智能体的名字就可以了,自带冒号
如果你没有Token和ssistant_id,你可以在https://yuanqi.tencent.com/注册一个账号
然后创建一个智能体
然后获取Token和assistant_id
```
配置好后不需要使用/reload,是自动读取的

输入/arona [消息] 就可以发送消息了

## 下载
Github: [点击下载](https://github.com/fingtest6/fingmodapcks/releases/tag/AronaChat1.0.0)
你问我为什么不开源,因为代码写的很烂,我还是要点脸的QWQ 
::: tip
MD5值:5dc2ad4f25ccc8de4f408e09461d31f4
:::
