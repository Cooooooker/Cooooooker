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

- **[Native Shell (NSH)](https://github.com/longbridge/nsh)**: TSX modules rendered with each platform's own UI on iOS, Android, macOS, Windows, Linux, GPUI and the web. 37+ merged PRs: `RichEditor`, `EmojiPicker`, the web runtime, iOS / Android input.
- **[Aloud Ink](https://aloud.ink)**: 说出来，就成文. AI voice input for macOS and iOS: speak, and clean text lands at your cursor. Rust + GPUI client, Go server. Co-built with [@griffinqiu](https://github.com/griffinqiu).

#### More from [Longbridge open source](https://github.com/longbridge)

| Project | About |
|---|---|
| [longbridge-terminal](https://github.com/longbridge/longbridge-terminal) | AI-native CLI for the Longbridge trading platform (Rust) |
| [openapi](https://github.com/longbridge/openapi) · [openapi-go](https://github.com/longbridge/openapi-go) | Longbridge OpenAPI SDKs (Rust core, Go) |
| [developers](https://github.com/longbridge/developers) | Longbridge developer docs site (TypeScript) |
| [nsh-compat](https://github.com/longbridge/nsh-compat) | The API NSH releases froze, and the checks that hold NSH to it |
