# Zeno

**서로 다른 곳의 기기를 연결하고 원격 리소스에 접근하세요.**

[English](README.md) | [简体中文](README.zh-hans.md) | [繁體中文](README.zh-hant.md) | [日本語](README.ja.md) | **한국어** | [Español](README.es.md) | [Русский](README.ru.md)

## 네트워크 프록시

원격 기기를 경유해 해당 기기가 연결할 수 있는 네트워크를 이용하세요.

![Zeno 네트워크 프록시: 원격 기기를 통해 네트워크에 접근](assets/proxy.png)

## 포트 포워딩

원격 기기에서 접근할 수 있는 TCP / UDP 서비스를 내 기기의 지정된 수신 주소에 매핑하세요.

![Zeno 포트 포워딩: 원격 서비스를 로컬 포트에 매핑](assets/forwarding.png)

## 가상 네트워크

원격 기기와 LAN을 연결하세요. P2P 연결이 성립되면 트래픽이 상대 기기로 직접 전달됩니다.

![Zeno 가상 네트워크: 원격 기기와 LAN 연결](assets/networking.png)

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
