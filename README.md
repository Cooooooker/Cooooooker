### Hi, I'm Zhipeng 👋

Engineer in Chengdu. Started on iOS, moved to Go backends, now building native UI in Rust, with AI agents in the loop every day.

```rust
struct Engineer {
    name:     &'static str,
    location: &'static str,
    path:     [&'static str; 3],
    now:      &'static [&'static str],
    motto:    &'static str,
}

const ME: Engineer = Engineer {
    name:     "Zhipeng Cheng",
    location: "Chengdu, China",
    path:     ["iOS (Objective-C / Swift)", "Backend (Go)", "Native UI runtime (Rust)"],
    now:      &["Native Shell: TSX → native views on 7 platforms", "Aloud Ink: AI voice input"],
    motto:    "Investigate things, extend knowledge.",
};
```

### 🛠️ Tech Stack

<p>
  <img src="https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white" />
  <img src="https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/Swift-F05138?style=for-the-badge&logo=swift&logoColor=white" />
  <img src="https://img.shields.io/badge/Objective--C-438EFF?style=for-the-badge&logo=apple&logoColor=white" />
  <img src="https://img.shields.io/badge/WebAssembly-654FF0?style=for-the-badge&logo=webassembly&logoColor=white" />
  <br/>
  <img src="https://img.shields.io/badge/iOS-000000?style=for-the-badge&logo=ios&logoColor=white" />
  <img src="https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white" />
  <img src="https://img.shields.io/badge/gRPC-244C5A?style=for-the-badge&logo=google&logoColor=white" />
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white" />
  <img src="https://img.shields.io/badge/Claude_Code-D97757?style=for-the-badge&logo=anthropic&logoColor=white" />
</p>

### 🔭 What I'm working on

<table>
<tr>
<td width="50%" valign="top">

#### 🧩 [Native Shell (NSH)](https://github.com/longbridge/nsh)
<sub>TSX modules rendered with each platform's own UI: iOS, Android, macOS, Windows, Linux, GPUI and the web.</sub>

![](https://img.shields.io/github/stars/longbridge/nsh?style=flat-square&logo=github&color=58A6FF)
![](https://img.shields.io/badge/merged_PRs-37+-8957E5?style=flat-square&logo=git&logoColor=white)

- ✏️ `RichEditor`: IME composition, touch selection, undo grouping
- 😀 `EmojiPicker`: search over every emoji, virtualized grid
- 🌐 Web runtime: text measuring, clipboard images, input methods
- 📱 iOS / Android: keyboard, modals, swipe-back, touch responders

</td>
<td width="50%" valign="top">

#### 🎙️ [Aloud Ink](https://aloud.ink): 说出来，就成文
<sub>AI voice input: press a key, speak, and clean text lands at your cursor. Co-built with [@griffinqiu](https://github.com/griffinqiu).</sub>

![](https://img.shields.io/badge/aloud.ink-live-2EA043?style=flat-square)
![](https://img.shields.io/badge/macOS_·_iOS-000000?style=flat-square&logo=apple)

- 🖥️ macOS client in Rust + GPUI: global hotkey, HUD that keeps focus
- ⚡ Audio streamed over WebSocket to a Go server
- 🧠 ASR, then an LLM strips filler words; text typed back at the cursor
- 📱 iOS keyboard extension on the same protocol

</td>
</tr>
</table>

#### More from [Longbridge open source](https://github.com/longbridge)

| Project | |
|---|---|
| [longbridge-terminal](https://github.com/longbridge/longbridge-terminal) ![](https://img.shields.io/github/stars/longbridge/longbridge-terminal?style=flat-square&label=%E2%98%85&color=555) | AI-native CLI for the Longbridge trading platform (Rust) |
| [openapi](https://github.com/longbridge/openapi) ![](https://img.shields.io/github/stars/longbridge/openapi?style=flat-square&label=%E2%98%85&color=555) · [openapi-go](https://github.com/longbridge/openapi-go) | Longbridge OpenAPI SDKs (Rust core, Go) |
| [developers](https://github.com/longbridge/developers) | Longbridge developer docs site (TypeScript) |
| [nsh-compat](https://github.com/longbridge/nsh-compat) | The API NSH releases froze, and the checks that hold NSH to it |

### 📊 GitHub Stats

<div align="center">
  <img src="./profile-summary-card-output/github_dark/0-profile-details.svg" width="100%" />
  <img src="./profile-summary-card-output/github_dark/3-stats.svg" height="170" />
  <img src="./profile-summary-card-output/github_dark/4-productive-time.svg" height="170" />
  <img height="170" src="https://streak-stats.demolab.com?user=Cooooooker&hide_border=true&theme=github-dark-blue&background=0D1117" />
</div>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Cooooooker/Cooooooker/output/snake-dark.svg" />
  <img alt="contribution snake" src="https://raw.githubusercontent.com/Cooooooker/Cooooooker/output/snake.svg" />
</picture>
