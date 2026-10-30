# surDancePlayer

Beat-aware dance practice player for Android, Windows, macOS, and Linux CLI.

**This repository publishes release packages only.** Source is private. Download installers from [Releases](https://github.com/lsuen/surDancePlayer-releases/releases).  
**Download hub (all platforms):** https://lsuen.github.io/surdance-web/downloads.html

---

## English

### Downloads

| Platform | File | Notes |
|----------|------|--------|
| Android (offline) | `surDancePlayer-full-VERSION.apk` | Full offline APK (phone / tablet / TV) |
| Windows | `surDancePlayer-Setup-VERSION.exe` | NSIS installer (WebView2 required) |
| Windows (portable) | `surDancePlayer-win-portable-VERSION.zip` | Unzip and run `surDancePlayer.exe` |
| macOS | `surDancePlayer-macos-VERSION-arm64.zip` / `…-x64.zip` | Unzip → `surDancePlayer.app` |
| Linux CLI | `surDancePlayer-linux-cli-VERSION.tar.gz` | `dance-player` + embedded `web/` |

Replace `VERSION` with the tag on the [Releases](https://github.com/lsuen/surDancePlayer-releases/releases) page (for example `3.1.43`).

### Install

#### Android

1. Download the `full` APK from Releases.
2. Allow install from this source if prompted.
3. Install. Desktop name: **SurDance**.

#### Windows

1. Download `surDancePlayer-Setup-VERSION.exe` **or** the portable zip.
2. Install [WebView2 Runtime](https://developer.microsoft.com/microsoft-edge/webview2/) if Windows asks.
3. Launch from Start Menu or the portable folder.

#### macOS (Homebrew — recommended)

```bash
brew tap lsuen/surdance
brew install --cask surdance-player
```

#### macOS (manual)

1. Download the zip for your chip (`arm64` = Apple Silicon, `x64` = Intel).
2. Unzip, drag `surDancePlayer.app` to Applications.
3. First launch (unsigned): right-click → **Open**, or `xattr -cr /Applications/surDancePlayer.app`.

#### Linux CLI

```bash
tar -xzf surDancePlayer-linux-cli-VERSION.tar.gz
cd linuxcli
./dance-player serve --host 127.0.0.1 --port 8080 --web-dist web
# open http://127.0.0.1:8080
```

### Web / online

- Free WebApp: https://lsuen.github.io/surdance-web/
- Downloads hub: https://lsuen.github.io/surdance-web/downloads.html
- Preview: https://tdance.nnrc.ren
- Production: https://dance.nnrc.ren

---

## 中文

### 下载

| 平台 | 文件 | 说明 |
|------|------|------|
| Android 离线 | `surDancePlayer-full-VERSION.apk` | 全量离线包（手机 / 平板 / 电视） |
| Windows | `surDancePlayer-Setup-VERSION.exe` | 安装包（需 WebView2） |
| Windows 绿色版 | `surDancePlayer-win-portable-VERSION.zip` | 解压运行 `surDancePlayer.exe` |
| macOS | `surDancePlayer-macos-VERSION-arm64.zip` / `…-x64.zip` | 解压得到 `surDancePlayer.app` |
| Linux 命令行 | `surDancePlayer-linux-cli-VERSION.tar.gz` | `dance-player` + 内嵌 `web/` |

`VERSION` 以 [Releases](https://github.com/lsuen/surDancePlayer-releases/releases) 标签为准。  
各系统汇总：https://lsuen.github.io/surdance-web/downloads.html

### 安装

#### Android

下载 `full` APK → 允许未知来源（如需要）→ 安装。桌面名 **SurDance**。

#### Windows

下载 Setup 或 portable zip → 缺组件时安装 WebView2 → 运行。

#### macOS（推荐 Homebrew）

```bash
brew tap lsuen/surdance
brew install --cask surdance-player
```

或下载 zip，把 `.app` 拖进「应用程序」。首次未签名可右键打开或执行 `xattr -cr /Applications/surDancePlayer.app`。

#### Linux 命令行

```bash
tar -xzf surDancePlayer-linux-cli-VERSION.tar.gz
cd linuxcli
./dance-player serve --host 127.0.0.1 --port 8080 --web-dist web
# 浏览器打开 http://127.0.0.1:8080
```

### 在线

- 无偿 WebApp：https://lsuen.github.io/surdance-web/
- 下载导航：https://lsuen.github.io/surdance-web/downloads.html
- 预览：https://tdance.nnrc.ren
- 生产：https://dance.nnrc.ren
