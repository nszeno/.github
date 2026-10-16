# Zeno

**Conecta dispositivos y servicios remotos sin una IP pública.**

[English](README.md) | [简体中文](README.zh-hans.md) | [繁體中文](README.zh-hant.md) | [日本語](README.ja.md) | [한국어](README.ko.md) | **Español** | [Русский](README.ru.md)

## Proxy SOCKS5

Accede a la red de un dispositivo remoto a través de él.

![Proxy SOCKS5 de Zeno: acceso a la red a través de un dispositivo remoto](assets/proxy.png)

## Reenvío de puertos

Conecta servicios TCP / UDP remotos a puertos locales.

![Reenvío de puertos de Zeno: asignación de servicios remotos a puertos locales](assets/forwarding.png)

## Red privada

Accede a los dispositivos de una LAN remota mediante una puerta de enlace.

![Red privada de Zeno: acceso a una red remota mediante una puerta de enlace](assets/networking.png)

## Primeros pasos

Instala Zeno Daemon tanto en el dispositivo local como en el remoto:

**macOS**

```sh
curl -fsSL https://dl.nszeno.com/daemon/macos-installer | bash
```

**Linux**

```sh
curl -fsSL https://dl.nszeno.com/daemon/linux-installer | bash
```

**Windows (PowerShell como administrador)**

```powershell
irm https://dl.nszeno.com/daemon/windows-installer | iex
```

Tras la instalación, [Abrir el panel](https://app.nszeno.com) y usa el Peer ID del dispositivo remoto para configurar el proxy, el reenvío de puertos o la red privada.
