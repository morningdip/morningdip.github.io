---
layout: post
title: 我的 macOS 軟體清單
subtitle: 強迫症的軟體清單應該值得一看
header-img: img/in-post/2022-05-16/header.jpg
header-style: text
catalog: true
tags:
  - macOS
  - 心得
---

嘿嘿該我秀一手了吧！這個時候點擊很有用

## 前言

當我第一次進入 macOS 的叢林時我也像一隻小白兔到處看大神的推薦軟體，
用了五年其實一直也想分享一下我的軟體清單。
我很喜歡使用 [Homebrew](https://brew.sh/index_zh-tw) 來管理我的軟體清單，
對於能使用終端機快速、優雅的下載更新軟體，我是完全沒有抵抗力的。

基本上，我很討厭非原生軟體，每次啟動應用程式，看他在 Dock 上面跳啊跳我就覺得很不順眼。
舉例來說 Electron 寫出來的程式，後台點開來看執行程式又臭又長，又耗資源。
所以能躲我是盡量不安裝。

可以考慮關閉 Mac 檢查網路下載應用程式的警告
{:.info}
```zsh
echo 'export HOMEBREW_CASK_OPTS=--no-quarantine' >> ~/.zshrc
```

---

## 軟體清單

### Shell 環境設定

- [Zimfw](https://github.com/zimfw/zimfw) 

    優點就是比 [Oh My Zsh](https://ohmyz.sh) 快上不少，主流的擴充套件也都可以安裝

- [Powerlevel10k](https://github.com/romkatv/powerlevel10k)

    優秀的客製化終端介面，好看

- [Zsh-z](https://github.com/agkozak/zsh-z)

    可以快速切換目錄，只需要打大略的關鍵字就可以，非常方便

- [Serendipity Theme](https://serendipitytheme.com)

    好看的色彩主題

- [Dracula Theme](https://draculatheme.com)

    好看的色彩主題 2

### Homebrew 軟體

- [iTerm2](https://iterm2.com)

    取代原生的終端機，分割視窗的功能很好用，個人化也好看
    
- [Bartender 4](https://www.macbartender.com)

    整理選單列的小工具，還你乾淨整潔的選單列

- [Brooklyn](https://github.com/pedrommcarrasco/Brooklyn)

    好看的蘋果動態效果螢幕保護程式，擺著可以看一個下午

- [Swish](https://highlyopinionated.co/swish/)

    視窗管理工具，可以用快捷鍵或手勢將視窗錨定在固定位置，為了強迫症患者而生的一套軟體

- [Raycast](https://www.macbartender.com)

    類似 [Alfred](https://www.alfredapp.com) 的 Spotlight 搜尋工具，擁有強大的擴充功能

- [BetterTouchTool](https://folivora.ai)

    自訂觸控板手勢、快捷鍵的小工具

- [Visual Studio Code](https://code.visualstudio.com)

    雖然是 Electron 框架，但有著非常大量且實用的擴充功能，本來想大聲斥責，但實在太香了

- [Surge](https://nssurge.com)

    強大的網路代理工具，高效能、高穩定性又占用極少資源

- [Telegram](https://macos.telegram.org)

    很讚的聊天軟體，我覺得這才是聊天軟體應該有的樣子

### Mac App Store 軟體

- [Meta](https://www.nightbirdsevolve.com/meta/)

    強大的元數據編輯器，支援各種音樂、影片格式

- [Infuse](https://firecore.com/infuse)

    跨 iPadOS、iOS、macOS 平台的影片播放器，主要用來掛載雲端硬碟

- [Vinegar](https://andadinosaur.com/launch-vinegar)

    把 YouTube 的播放器替換成 HTML 播放器，去廣告、去追蹤，占用更少資源

- [Wipr](https://giorgiocalderolla.com/wipr.html)

    原生、更輕巧的廣告阻擋器，缺點可能是沒辦法自定義阻擋清單

---

## 結語

以上就是我比較常用的 Mac 軟體，當然還有一些常見的我就不贅述了，
Mac 的生態還有很多很棒<s>也很貴</s>的應用程式，就大家多討論多分享囉！
