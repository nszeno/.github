# Zeno

**Connect remote devices and services without a public IP address.**

**English** | [简体中文](README.zh-hans.md) | [繁體中文](README.zh-hant.md) | [日本語](README.ja.md) | [한국어](README.ko.md) | [Español](README.es.md) | [Русский](README.ru.md)

## SOCKS5 Proxy

Access a remote device’s network through that device.

![Zeno SOCKS5 Proxy: access a network through a remote device](assets/proxy.png)

## Port Forwarding

Map remote TCP / UDP services to local ports.

![Zeno Port Forwarding: map remote services to local ports](assets/forwarding.png)

## Private Networking

Access devices on a remote LAN through a gateway.

![Zeno Private Networking: access a remote network through a gateway](assets/networking.png)

## Get started

Install Zeno Daemon on both your local and remote devices:

**macOS**

```sh
curl -fsSL https://dl.nszeno.com/daemon/macos-installer | bash
```

**Linux**

```sh
curl -fsSL https://dl.nszeno.com/daemon/linux-installer | bash
```

**Windows (PowerShell as administrator)**

```powershell
irm https://dl.nszeno.com/daemon/windows-installer | iex
```

After installation, [Open dashboard](https://app.nszeno.com) and use the remote device’s Peer ID to configure Proxy, Forwarding, or Networking.
