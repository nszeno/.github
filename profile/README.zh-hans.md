# Zeno

**无需公网 IP，连接异地设备与服务。**

[English](README.md) | **简体中文** | [繁體中文](README.zh-hant.md) | [日本語](README.ja.md) | [한국어](README.ko.md) | [Español](README.es.md) | [Русский](README.ru.md)

## SOCKS5 代理

通过远端设备，访问它所在的网络。

![Zeno SOCKS5 代理：通过远端设备访问网络](assets/proxy.png)

## 端口转发

把远端 TCP / UDP 服务，接到本地端口。

![Zeno 端口转发：将远端服务映射到本地](assets/forwarding.png)

## 虚拟组网

通过网关连接异地局域网，访问其中的设备。

![Zeno 虚拟组网：通过网关访问远端网络](assets/networking.png)

## 开始使用

在本机和远端设备上安装 Zeno Daemon：

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
