# Zeno

**공인 IP 없이 원격 기기와 서비스에 연결하세요.**

[English](README.md) | [简体中文](README.zh-hans.md) | [繁體中文](README.zh-hant.md) | [日本語](README.ja.md) | **한국어** | [Español](README.es.md) | [Русский](README.ru.md)

## SOCKS5 프록시

원격 기기를 통해 해당 기기의 네트워크에 접근하세요.

![Zeno SOCKS5 프록시: 원격 기기를 통해 네트워크에 접근](assets/proxy.png)

## 포트 포워딩

원격 TCP / UDP 서비스를 로컬 포트에 연결하세요.

![Zeno 포트 포워딩: 원격 서비스를 로컬 포트에 매핑](assets/forwarding.png)

## 가상 네트워크

게이트웨이를 통해 원격 LAN의 기기에 접근하세요.

![Zeno 가상 네트워크: 게이트웨이를 통해 원격 네트워크에 접근](assets/networking.png)

## 시작하기

로컬 기기와 원격 기기 모두에 Zeno Daemon을 설치하세요.

**macOS**

```sh
curl -fsSL https://dl.nszeno.com/daemon/macos-installer | bash
```

**Linux**

```sh
curl -fsSL https://dl.nszeno.com/daemon/linux-installer | bash
```

**Windows (관리자 권한 PowerShell)**

```powershell
irm https://dl.nszeno.com/daemon/windows-installer | iex
```

설치 후 [대시보드 열기](https://app.nszeno.com)에서 원격 기기의 Peer ID를 사용해 프록시, 포트 포워딩 또는 가상 네트워크를 설정하세요.
