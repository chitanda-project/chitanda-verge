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
  Languages:
  <a href="./docs/README_en.md">English</a> ·
  <a href="./docs/README_es.md">Español</a> ·
  <a href="./docs/README_fa.md">فارسی</a> ·
  <a href="./docs/README_ja.md">日本語</a> ·
  <a href="./docs/README_ko.md">한국어</a> ·
  <a href="./docs/README_pt.md">Português</a> ·
  <a href="./docs/README_ru.md">Русский</a> ·
  <a href="./README.md">简体中文</a>
</p>

</div>

| Dark                             | Light                             |
| -------------------------------- | --------------------------------- |
| ![预览](./docs/preview_dark.png) | ![预览](./docs/preview_light.png) |

## Install

请到发布页面下载对应的安装包：[Release page](https://github.com/clash-verge-rev/clash-verge-rev/releases)<br>
Go to the [Release page](https://github.com/clash-verge-rev/clash-verge-rev/releases) to download the corresponding installation package<br>
Supports Windows (x64/x86), Linux (x64/arm64) and macOS 11+ (intel/apple).
支持 Windows (x64/x86)、Linux (x64/arm64) 和 macOS 11+ (intel/apple)。

#### 我应当怎样选择发行版

| 版本        | 特征                                     | 链接                                                                                   |
| :---------- | :--------------------------------------- | :------------------------------------------------------------------------------------- |
| Stable      | 正式版，高可靠性，适合日常使用。         | [Release](https://github.com/clash-verge-rev/clash-verge-rev/releases)                 |
| Alpha(废弃) | 测试发布流程。                           | [Alpha](https://github.com/clash-verge-rev/clash-verge-rev/releases/tag/alpha)         |
| AutoBuild   | 滚动更新版，适合测试反馈，可能存在缺陷。 | [AutoBuild](https://github.com/clash-verge-rev/clash-verge-rev/releases/tag/autobuild) |

#### 安装说明和常见问题，请到 [文档页](https://clash-verge-rev.github.io/) 查看

### TG 频道: [@clash_verge_rev](https://t.me/clash_verge_re)

---

## プレビュー (Preview)

### ✈️ [AI云边 -- 全新架构机场 ClaudeBorder](https://cruise.54678999.xyz/#/register?code=58q5UJZc)

🔥热销中使用本链接注册即送 **3 天免费试用**，每日 **1GB 流量**：👉 [点此注册](https://cruise.54678999.xyz/#/register?code=58q5UJZc)

#### AI云边 -- 全新架构机场。

- 💻 多次**技术迭代后**全新亮相。
- 🗺 全**高速稳定**正价节点。
- 🌏 **海外团队**，不跑路
- 🚀 线路**冗余**设计，**自动化运维**对抗各类封锁
- 👨‍🦲 团队架构师为**大厂**网络架构师
- 💰 极致**稳定**，亲民价**价格**
- 🌐 全面支持**流媒体及各AI访问**
- 🙋 7*12小时真人客服。解决您的各类问题。

🌐 官网：👉 [https://www.claudeborder.com](https://cruise.54678999.xyz/#/register?code=58q5UJZc)

### 🤖 [GPTKefu —— 与 Crisp 深度整合的 AI 智能客服平台](https://gptkefu.com)

- 🧠 深度理解完整对话上下文 + 图片识别，自动给出专业、精准的回复，告别机械式客服。
- ♾️ **不限回答数量**，无额度焦虑，区别于其他按条计费的 AI 客服产品。
- 💬 售前咨询、售后服务、复杂问题解答，全场景轻松覆盖，真实用户案例已验证效果。
- ⚡ 3 分钟极速接入，零门槛上手，即刻提升客服效率与客户满意度。
- 🎁 高级套餐免费试用 14 天，先体验后付费：👉 [立即试用](https://gptkefu.com)
- 📢 智能客服TG 频道：[@crisp_ai](https://t.me/crisp_ai)

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
