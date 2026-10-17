# Zeno

**서로 다른 곳의 기기를 연결하고 원격 리소스에 접근하세요.**

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

> 설치에는 관리자 권한이 필요합니다. 부팅 시 자동 시작을 설정하고, 가상 네트워크 기능에 필요한 가상 네트워크 인터페이스를 생성하고 라우팅을 설정하는 데 사용됩니다.

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
