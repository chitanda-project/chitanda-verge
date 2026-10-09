<div align="center">

<img src="https://raw.githubusercontent.com/chitanda-project/chitanda/main/public/avatar.webp" alt="Chitanda" width="120" />

# 🌸 Chitanda Verge (千反田 Verge)

**次世代デスクトップ向け高性能プロキシクライアント**  
*Windows / macOS / Linux 向けクロスプラットフォーム GUI（Tauri 2 採用）*

[![Release](https://img.shields.io/github/v/release/chitanda-project/chitanda-verge?color=blue&style=flat-square)](https://github.com/chitanda-project/chitanda-verge/releases)
[![Build](https://github.com/chitanda-project/chitanda-verge/actions/workflows/build-release.yml/badge.svg)](https://github.com/chitanda-project/chitanda-verge/actions)
[![License](https://img.shields.io/badge/License-GPL--3.0-green.svg?style=flat-square)](LICENSE)
[![Official Website](https://img.shields.io/badge/Official-chitanda.net-blue?style=flat-square)](https://chitanda.net)

<p align="center">
  <b>Chitanda Verge</b> は、<a href="https://github.com/clash-verge-rev/clash-verge-rev">Clash Verge Rev</a> をベースに開発された、次世代プロキシコア <b><a href="https://github.com/chitanda-project/chitanda">Chitanda Core (Mihomo)</a></b> を標準搭載した公式デスクトップクライアントです。<br>
  独自開発の <b>Chitanda プロトコル</b> に完全対応し、高度なルーティングと超高スループットをデスクトップ環境で提供します。
</p>

</div>

> [!WARNING]
> ### ⚠️ 免責事項 (Disclaimer)
> 本プロジェクトおよび関連リソースは、学術研究、ネットワークセキュリティ検証、および正当な管理運用を目的として公開・提供されています。
> 
> 1. **法令遵守の義務**：本ソフトウェアおよび関連コードを利用する際は、**必ずご利用者ご自身の所在国・地域の法令および規則を遵守してください**。
> 2. **利用の禁止**：本ソフトウェアの利用が所在国または地域の法令・規則に違反する場合、**いかなる目的であっても本ソフトウェアのダウンロード、インストール、実行、および二次配布を行わないでください**。
> 3. **免責条項**：開発者およびプロジェクト保守管理者は、本ソフトウェアの使用、誤用、またはそれに関連して生じたいかなる損害、法的紛争、および責任についても一切の責任を負いません。

---

## プレビュー (Preview)

| ダークモード (Dark) | ライトモード (Light) |
| :--- | :--- |
| ![Preview Dark](./docs/preview_dark.png) | ![Preview Light](./docs/preview_light.png) |

---

## 主な機能 (Features)

- 🌸 **Chitanda プロトコル標準サポート**：
  - `h2`（TLS 1.3 + HTTP/2 多重化）、`stream`（RawStream 高速専用線モード）、`h3`（HTTP/3 QUIC）など、次世代トランスポートキャリアをネイティブサポート。
- ⚡ **超軽量かつ高速**：
  - Rust と Tauri 2 アーキテクチャにより、極限までメモリ消費を抑えた軽快な動作を実現。
- 🛡️ **TUN（仮想ネットワークカード）モード**：
  - システム全体のネットワーク通信を透過的にプロキシ処理（管理者権限サービス同梱）。
- 🎨 **自由度の高いカスタマイズ**：
  - ダーク / ライトテーマ、カスタムアクセントカラー、トレイアイコン変更、CSS インジェクションに対応。
- 📜 **高度なプロファイル管理**：
  - Merge（差分マージ）および Script（JavaScript 拡張スクリプト）による柔軟なルール・プロキシグループ制御。
- 🔄 **コアのワンクリック切り替え**：
  - 安定版（Stable）および最新実験版（Alpha）の Chitanda 内核をアプリ内で容易に切り替え可能。
- 💾 **WebDAV バックアップ & 同期**：
  - プロファイルや設定のクラウド同期に対応。

---

## インストール (Installation)

最新のインストーラーおよびポータブル版は、リリースページよりダウンロードしてください：  
📦 **[リリースページ (Releases)](https://github.com/chitanda-project/chitanda-verge/releases)**

### 対応プラットフォーム & 発行版

| プラットフォーム | アーキテクチャ | 形式 |
| :--- | :--- | :--- |
| **Windows** | x64 (64-bit) / ARM64 | インストーラー (`.exe`) / ポータブル版 (`.zip`) |
| **macOS** | Apple Silicon (Mシリーズ) / Intel (x64) | DMG パッケージ (`.dmg`) |
| **Linux** | x64 (amd64) / ARM64 (aarch64) | Debian パッケージ (`.deb`) / AppImage / RPM |

#### エディションの選び方

| エディション | 特徴 | リンク |
| :--- | :--- | :--- |
| **Stable（推奨）** | 正式版。安定版 Chitanda 内核を同梱し、日常利用に最適です。 | [Releases](https://github.com/chitanda-project/chitanda-verge/releases) |
| **AutoBuild** | 開発版。最新の上流機能およびテスト内核をいち早く反映したビルドです。 | [AutoBuild](https://github.com/chitanda-project/chitanda-verge/releases/tag/autobuild) |

---

## 開発とビルド (Development)

ビルド要件：**Node.js 20+**, **pnpm**, **Rust (cargo)**

```bash
# 依存関係のインストール
pnpm install

# Chitanda 内核およびリソースの事前取得
pnpm run prebuild

# 開発サーバーの起動
pnpm run dev
```

---

## プライバシー (Privacy)

Chitanda Verge は、いかなる利用者の個人情報やアクセスログも収集しません。設定およびログはすべてご利用の端末ローカルにのみ保存されます。詳細は [PRIVACY.md](./PRIVACY.md) をご参照ください。

---

## クレジット (Acknowledgements)

本プロジェクトは、以下の素晴らしいオープンソースプロジェクトに基づいて開発・提供されています：

- [clash-verge-rev/clash-verge-rev](https://github.com/clash-verge-rev/clash-verge-rev) - Continuation of Clash Verge
- [tauri-apps/tauri](https://github.com/tauri-apps/tauri) - Build smaller, faster, and more secure desktop applications
- [MetaCubeX/mihomo](https://github.com/MetaCubeX/mihomo) - A rule-based tunnel in Go
- [chitanda-project/chitanda](https://github.com/chitanda-project/chitanda) - High-performance secure proxy engine

---

## ライセンス (License)

本ソフトウェアは [GPL-3.0 License](./LICENSE) のもとで公開されています。
