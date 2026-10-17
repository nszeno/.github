# Zeno

**パブリック IP アドレスなしで、離れたデバイスやサービスに接続。**

[English](README.md) | [简体中文](README.zh-hans.md) | [繁體中文](README.zh-hant.md) | **日本語** | [한국어](README.ko.md) | [Español](README.es.md) | [Русский](README.ru.md)

## SOCKS5 プロキシ

リモートデバイスを経由して、そのネットワークにアクセス。

![Zeno SOCKS5 プロキシ：リモートデバイス経由でネットワークにアクセス](assets/proxy.png)

## ポート転送

リモートの TCP / UDP サービスをローカルポートに接続。

![Zeno ポート転送：リモートサービスをローカルにマッピング](assets/forwarding.png)

## 仮想ネットワーク

ゲートウェイ経由で離れた LAN 内のデバイスにアクセス。

![Zeno 仮想ネットワーク：ゲートウェイ経由でリモートネットワークにアクセス](assets/networking.png)

## 使い始める

ローカルとリモートの両方のデバイスに Zeno Daemon をインストールします。

インストールには管理者権限が必要です。起動時の自動実行の設定と、仮想ネットワーク機能に必要な仮想ネットワークインターフェースの作成・ルートの設定に使用します。

**macOS**

```sh
curl -fsSL https://dl.nszeno.com/daemon/macos-installer | bash
```

**Linux**

```sh
curl -fsSL https://dl.nszeno.com/daemon/linux-installer | bash
```

**Windows（管理者として PowerShell を起動）**

```powershell
irm https://dl.nszeno.com/daemon/windows-installer | iex
```

インストール後、[ダッシュボードを開く](https://app.nszeno.com)から、リモートデバイスの Peer ID を使ってプロキシ、ポート転送、仮想ネットワークを設定します。
