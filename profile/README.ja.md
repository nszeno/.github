# Zeno

**離れた場所のデバイスをつなぎ、リモートのリソースにアクセス。**

[English](README.md) | [简体中文](README.zh-hans.md) | [繁體中文](README.zh-hant.md) | **日本語** | [한국어](README.ko.md) | [Español](README.es.md) | [Русский](README.ru.md)

## ネットワークプロキシ

リモートデバイスを経由して、接続可能なネットワークを利用。

![Zeno ネットワークプロキシ：リモートデバイス経由でネットワークにアクセス](assets/proxy.png)

## ポート転送

リモートデバイスからアクセスできる TCP / UDP サービスを、自分のデバイスで指定した待ち受けアドレスにマッピング。

![Zeno ポート転送：リモートサービスをローカルにマッピング](assets/forwarding.png)

## 仮想ネットワーク

離れたデバイスや LAN を接続。P2P 接続の確立後は、通信が相手のデバイスに直接届きます。

![Zeno 仮想ネットワーク：離れたデバイスや LAN を接続](assets/networking.png)

## 使い始める

ローカルとリモートの両方のデバイスに Zeno Daemon をインストールします。

> インストールには管理者権限が必要です。起動時の自動実行の設定と、仮想ネットワーク機能に必要な仮想ネットワークインターフェースの作成・ルートの設定に使用します。

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
