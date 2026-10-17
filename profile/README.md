# Zeno

**Connect devices across locations and access remote resources.**

**English** | [简体中文](README.zh-hans.md) | [繁體中文](README.zh-hant.md) | [日本語](README.ja.md) | [한국어](README.ko.md) | [Español](README.es.md) | [Русский](README.ru.md)

## Network Proxy

Use a remote device to access the networks it can reach.

![Zeno Network Proxy: access a network through a remote device](assets/proxy.png)

## Port Forwarding

Map TCP / UDP services reachable from a remote device to a specified listening address on your device.

![Zeno Port Forwarding: map remote services to local ports](assets/forwarding.png)

## Private Networking

Connect remote devices and LANs. Once a P2P connection is established, traffic flows directly to the peer.

![Zeno Private Networking: connect remote devices and LANs](assets/networking.png)

## Get started

Install Zeno Daemon on both your local and remote devices:

> Installation requires administrator privileges to configure automatic startup at boot and to create virtual network interfaces and configure routes for private networking.

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
