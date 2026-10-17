# Zeno

**Conecta dispositivos en distintas ubicaciones y accede a recursos remotos.**

[English](README.md) | [简体中文](README.zh-hans.md) | [繁體中文](README.zh-hant.md) | [日本語](README.ja.md) | [한국어](README.ko.md) | **Español** | [Русский](README.ru.md)

## Proxy de red

Accede a la red de un dispositivo remoto a través de él.

![Proxy de red de Zeno: acceso a la red a través de un dispositivo remoto](assets/proxy.png)

## Reenvío de puertos

Asigna los servicios TCP / UDP accesibles desde un dispositivo remoto a una dirección de escucha especificada en tu dispositivo.

![Reenvío de puertos de Zeno: asignación de servicios remotos a puertos locales](assets/forwarding.png)

## Red privada

Conecta dispositivos y redes LAN remotos. Una vez establecida una conexión P2P, el tráfico fluye directamente al otro dispositivo.

![Red privada de Zeno: conexión de dispositivos y redes LAN remotos](assets/networking.png)

## Primeros pasos

Instala Zeno Daemon tanto en el dispositivo local como en el remoto:

> La instalación requiere permisos de administrador para configurar el inicio automático al arrancar el sistema, crear interfaces de red virtuales y configurar las rutas necesarias para la red privada.

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
