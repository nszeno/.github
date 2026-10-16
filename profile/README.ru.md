# Zeno

**Подключайтесь к удалённым устройствам и сервисам без публичного IP-адреса.**

[English](README.md) | [简体中文](README.zh-hans.md) | [繁體中文](README.zh-hant.md) | [日本語](README.ja.md) | [한국어](README.ko.md) | [Español](README.es.md) | **Русский**

## SOCKS5-прокси

Получайте доступ к сети удалённого устройства через это устройство.

![SOCKS5-прокси Zeno: доступ к сети через удалённое устройство](assets/proxy.png)

## Проброс портов

Подключайте удалённые TCP / UDP-сервисы к локальным портам.

![Проброс портов Zeno: перенаправление удалённых сервисов на локальные порты](assets/forwarding.png)

## Частная сеть

Получайте доступ к устройствам в удалённой локальной сети через шлюз.

![Частная сеть Zeno: доступ к удалённой сети через шлюз](assets/networking.png)

## Начало работы

Установите Zeno Daemon на локальное и удалённое устройства:

**macOS**

```sh
curl -fsSL https://dl.nszeno.com/daemon/macos-installer | bash
```

**Linux**

```sh
curl -fsSL https://dl.nszeno.com/daemon/linux-installer | bash
```

**Windows (PowerShell от имени администратора)**

```powershell
irm https://dl.nszeno.com/daemon/windows-installer | iex
```

После установки [Открыть панель управления](https://app.nszeno.com) и используйте Peer ID удалённого устройства для настройки прокси, проброса портов или частной сети.
