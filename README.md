<h1 align="center">
  <img src="./src-tauri/icons/icon.png" alt="Clash" width="128" />
  <br>
  🌸 Chitanda Verge
  <br>
</h1>

<h3 align="center">
A high-performance Mihomo GUI for Desktop with native <b>Chitanda Protocol</b> support, based on <a href="https://github.com/clash-verge-rev/clash-verge-rev">Clash Verge Rev</a> and <a href="https://github.com/tauri-apps/tauri">Tauri</a>.
</h3>

<p align="center">
  <a href="https://github.com/chitanda-project/chitanda-verge/releases"><img src="https://img.shields.io/github/v/release/chitanda-project/chitanda-verge?color=blue&style=flat-square" alt="Release" /></a>
  <a href="https://github.com/chitanda-project/chitanda-verge/actions/workflows/build-release.yml"><img src="https://github.com/chitanda-project/chitanda-verge/actions/workflows/build-release.yml/badge.svg" alt="Build" /></a>
  <a href="https://chitanda.net"><img src="https://img.shields.io/badge/Official-chitanda.net-blue?style=flat-square" alt="Website" /></a>
</p>

## Preview

| Dark                             | Light                             |
| -------------------------------- | --------------------------------- |
| ![预览](./docs/preview_dark.png) | ![预览](./docs/preview_light.png) |

## Install

请到发布页面下载内置 **Chitanda Mihomo 内核** 的安装包：[Release page](https://github.com/chitanda-project/chitanda-verge/releases)<br>
Go to the [Release page](https://github.com/chitanda-project/chitanda-verge/releases) to download the corresponding installation package with pre-bundled Chitanda Mihomo Core.<br>
Supports Windows (x64/ARM64), Linux (x64/ARM64) and macOS 11+ (Intel/Apple Silicon).

#### 发行版说明

| 版本        | 特征                                     | 链接                                                                                   |
| :---------- | :--------------------------------------- | :------------------------------------------------------------------------------------- |
| Stable      | 正式版，内置稳定版 Chitanda 内核，适合日常使用。 | [Release](https://github.com/chitanda-project/chitanda-verge/releases)                 |
| AutoBuild   | 滚动构建版，同步最新内核更新与上游特性。 | [AutoBuild](https://github.com/chitanda-project/chitanda-verge/releases/tag/autobuild) |

---

## Features

- 基于性能强劲的 Rust 和 Tauri 2 框架
- 内置 **[Chitanda Mihomo 内核](https://github.com/chitanda-project/chitanda)**，原生支持 Chitanda 协议，并支持切换 `Alpha` 版本内核。
- 简洁美观的用户界面，支持自定义主题颜色、代理组/托盘图标以及 `CSS Injection`。
- 配置文件管理和增强（Merge 和 Script），配置文件语法提示。
- 系统代理和守卫、`TUN(虚拟网卡)` 模式。
- 可视化节点和规则编辑
- WebDav 配置备份和同步

### FAQ

Refer to [Doc FAQ Page](https://clash-verge-rev.github.io/faq/windows.html)

### Donation

[捐助Clash Verge Rev的开发](https://github.com/sponsors/clash-verge-rev)

## Development

See [CONTRIBUTING.md](./CONTRIBUTING.md) for more details.

To run the development server, execute the following commands after all prerequisites for **Tauri** are installed:

```shell
pnpm i
pnpm run prebuild
pnpm dev
```

`pnpm dev` preserves the Development Channel's installed service state: an
existing service is used, while a previously uninstalled service remains
uninstalled and the app starts in Sidecar mode. Use `pnpm dev:service` to
explicitly install or update the isolated development service before launch,
or `pnpm dev:sidecar` to force the unprivileged Sidecar workflow.

## Contributions

Issue and PR welcome!

## Acknowledgement

Clash Verge rev was based on or inspired by these projects and so on:

- [zzzgydi/clash-verge](https://github.com/zzzgydi/clash-verge): A Clash GUI based on tauri. Supports Windows, macOS and Linux.
- [tauri-apps/tauri](https://github.com/tauri-apps/tauri): Build smaller, faster, and more secure desktop applications with a web frontend.
- [Dreamacro/clash](https://github.com/Dreamacro/clash): A rule-based tunnel in Go.
- [MetaCubeX/mihomo](https://github.com/MetaCubeX/mihomo): A rule-based tunnel in Go.
- [Fndroid/clash_for_windows_pkg](https://github.com/Fndroid/clash_for_windows_pkg): A Windows/macOS GUI based on Clash.
- [vitejs/vite](https://github.com/vitejs/vite): Next generation frontend tooling. It's fast!

## Privacy

Clash Verge Rev 不收集任何用户数据，配置与日志仅保存在本地。详见[隐私政策](./PRIVACY.md)。

Clash Verge Rev does not collect any user data; configuration and logs stay on
your own device. See the [Privacy Policy](./PRIVACY.md) for details.

## License

GPL-3.0 License. See [License here](./LICENSE) for details.
