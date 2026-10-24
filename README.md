# surDancePlayer

Beat-aware dance practice player for Android, Windows, and macOS.

**This repository publishes release packages only.** Source code is maintained privately (Gitea). Download installers from [Releases](https://github.com/lsuen/surDancePlayer-releases/releases).

---

## English

### Downloads

| Platform | File | Notes |
|----------|------|--------|
| Android (offline) | `surDancePlayer-full-VERSION.apk` | Full offline APK (phone / tablet / TV) |
| Windows | `surDancePlayer-Setup-VERSION.exe` | NSIS installer (WebView2 required) |
| Windows (portable) | `surDancePlayer-win-portable-VERSION.zip` | Unzip and run `surDancePlayer.exe` |
| macOS | `surDancePlayer-macos-VERSION-arm64.zip` / `…-x64.zip` | Unzip → `surDancePlayer.app` |

Replace `VERSION` with the tag on the [Releases](https://github.com/lsuen/surDancePlayer-releases/releases) page (for example `3.1.38`).

### Install

#### Android

1. Download the `full` APK from Releases.
2. On the device, allow install from this source if prompted.
3. Open the APK and install. Desktop name: **SurDance**.

#### Windows

1. Download `surDancePlayer-Setup-VERSION.exe` and run it, **or** unzip the portable zip and run `surDancePlayer.exe`.
2. Install [WebView2 Runtime](https://developer.microsoft.com/microsoft-edge/webview2/) if Windows asks for it.
3. Launch from Start Menu / Desktop shortcut (installer) or the portable folder.

#### macOS (Homebrew — recommended)

```bash
brew tap lsuen/surdance
brew install --cask surdance-player
```

Upgrade later:

```bash
brew update
brew upgrade --cask surdance-player
```

#### macOS (manual)

1. Download the zip for your chip (`arm64` = Apple Silicon, `x64` = Intel).
2. Unzip, drag `surDancePlayer.app` to Applications.
3. First launch (unsigned build): right-click the app → **Open**, or run:

```bash
xattr -cr /Applications/surDancePlayer.app
```

### Web / online

- Production: https://dance.nnrc.ren  
- Preview: https://tdance.nnrc.ren  

---

## 中文

### 下载

| 平台 | 文件 | 说明 |
|------|------|------|
| Android 离线 | `surDancePlayer-full-VERSION.apk` | 全量离线包（手机 / 平板 / 电视） |
| Windows | `surDancePlayer-Setup-VERSION.exe` | 安装包（需 WebView2） |
| Windows 绿色版 | `surDancePlayer-win-portable-VERSION.zip` | 解压运行 `surDancePlayer.exe` |
| macOS | `surDancePlayer-macos-VERSION-arm64.zip` / `…-x64.zip` | 解压得到 `surDancePlayer.app` |

`VERSION` 以 [Releases](https://github.com/lsuen/surDancePlayer-releases/releases) 页面标签为准。

### 安装

#### Android

1. 从 Releases 下载 `full` APK。  
2. 按系统提示允许「未知来源」安装。  
3. 安装后桌面名：**SurDance**。

#### Windows

1. 运行 `surDancePlayer-Setup-VERSION.exe`，或解压绿色版后运行 `surDancePlayer.exe`。  
2. 若提示缺少组件，安装 [WebView2](https://developer.microsoft.com/microsoft-edge/webview2/)。  
3. 从开始菜单 / 桌面快捷方式，或绿色版目录启动。

#### macOS（推荐 Homebrew）

```bash
brew tap lsuen/surdance
brew install --cask surdance-player
```

升级：

```bash
brew update
brew upgrade --cask surdance-player
```

#### macOS（手动）

1. 按芯片下载对应 zip（`arm64` = Apple 芯片，`x64` = Intel）。  
2. 解压后把 `surDancePlayer.app` 拖到「应用程序」。  
3. 首次打开（未公证）：在 Finder 里右键 → **打开**，或执行：

```bash
xattr -cr /Applications/surDancePlayer.app
```

### 网页版

- 生产：https://dance.nnrc.ren  
- 预览：https://tdance.nnrc.ren  

### 作者

孙文龙 (Sun Wenlong)
