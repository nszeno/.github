# Zeno

**连接异地设备，访问远端资源。**

[English](README.md) | **简体中文** | [繁體中文](README.zh-hant.md) | [日本語](README.ja.md) | [한국어](README.ko.md) | [Español](README.es.md) | [Русский](README.ru.md)

## 网络代理

通过远端设备，访问其可达的网络。

![Zeno 网络代理：通过远端设备访问网络](assets/proxy.png)

## 端口转发

将远端设备可访问的 TCP / UDP 服务映射到本机指定监听地址。

![Zeno 端口转发：将远端服务映射到本地](assets/forwarding.png)

## 虚拟组网

连接异地设备与局域网，建立 P2P 连接后流量直达对端。

![Zeno 虚拟组网：连接异地设备与局域网](assets/networking.png)

## 开始使用

在本机和远端设备上安装 Zeno Daemon：

> 安装需要管理员权限，用于配置开机启动，以及创建虚拟网络接口和配置路由，以支持私有网络功能。

**macOS**

```sh
curl -fsSL https://dl.nszeno.com/daemon/macos-installer | bash
```

**Linux**

```sh
curl -fsSL https://dl.nszeno.com/daemon/linux-installer | bash
```

**Windows（管理员 PowerShell）**

```powershell
irm https://dl.nszeno.com/daemon/windows-installer | iex
```

安装后，[打开控制台](https://app.nszeno.com)，使用远端设备的 Peer ID 配置代理、转发或组网。
