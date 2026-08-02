# Verity-CE

Verity 模组社区版 | Community Edition

支持自定义 AI API、TTS/STT 配置、多版本适配。原版 by ThatMobb，社区维护版。

Custom AI API, TTS/STT config, multi-loader support. Original by ThatMobb, community-maintained.

---

## 📦 下载 | Download

| 版本 | 加载器 | 下载 |
|---|---|---|
| MC 1.21.1 | NeoForge | [v1.0b](https://github.com/Esylmu/Verity-CE/releases/tag/neoforge-1.21.1-1.0b(ce)) |
| MC 1.20.1 | Fabric / Forge / NeoForge | *Coming soon* |

&gt; ⚠️ **官方渠道声明 | Official Channel Statement**
&gt; 本项目唯一发布渠道为 GitHub Release 页面。任何第三方网站（包括 verity-mod.com、BBSMC 等）提供的 `.exe` 整合包、Bedrock 移植版均非官方出品，请注意甄别，避免下载到恶意软件。
&gt; The only official release channel is GitHub Release. Any third-party `.exe` bundles or Bedrock ports are unofficial.

---

## 🔦 已知问题 | Known Issues

**手电筒无光源 | Flashlight not emitting light**

| 问题层级 | 具体原因 |
|---|---|
| 配置文件缺失 | `verity.mixins.json` 不存在，导致 `MixinEntityRenderer`、`MixinLevelRenderer`、`LightTextureMixin` 三个 Mixin 类未被注册 |
| 启动器配置失效 | `neoforge.mods.toml` 中引用 mixin JSON 的行被注释 |

**修复状态：** 正在处理，预计下个版本解决  
**Fix Status:** In progress, expected next release

---

## 📊 功能投票 | Feature Vote

我们正在收集社区意见，决定下一个版本的功能方向：  
We're collecting community feedback for the next update:

[👉 参与投票 | Vote here](https://github.com/Esylmu/Verity-CE/discussions/1)

截止时间 | Deadline: **2026年8月9日 | August 9, 2026**

---

## 📚 社区资源 | Community Resources

| 资源 | 说明 | 链接 |
|---|---|---|
| 📖 文档站 | 安装指南、Wiki、兼容性测试（by zhongyao） | [verity-mod.com](https://www.verity-mod.com) |
| 🇨🇳 中文汉化版 | Pojav 安卓启动器适配（by xzy4260） | [B站视频](https://www.bilibili.com) |
| 🎮 B站教程 | Verity 模组使用教程 | [B站搜索](https://search.bilibili.com) |

---

## 🛠️ 技术信息 | Technical Info

- **支持加载器 | Supported Loaders:** Fabric / NeoForge / Forge
- **支持版本 | Supported Versions:** 1.20.1+ / 1.21.1
- **核心功能 | Core Features:**
  - 自定义 AI API 配置 | Custom AI API configuration
  - TTS 语音合成 | Text-to-Speech
  - STT 语音识别 | Speech-to-Text
  - AI 聊天与指令辅助 | AI chat & command assistance

---

## 🙏 致谢 | Credits

- 原版 | Original: [ThatMobb](https://github.com/ThatMobb)
- 文档站 | Docs: [zhongyao](https://www.verity-mod.com)
- 中文汉化 | CN Localization: [xzy4260](https://space.bilibili.com)
- 社区反馈 | Community feedback: [Lcs2_FLC](https://space.bilibili.com) 等

---

## 📜 原版状态 | Original Status

原版 Verity Mod 已从 CurseForge/Modrinth 下架，本仓库基于反编译的 Verity 2.1.0 进行修复和功能增强。

The original Verity Mod has been removed from CurseForge/Modrinth. This repository is based on decompiled Verity 2.1.0 for fixes and enhancements.

---

## ⚖️ 免责声明 | Disclaimer

本仓库为社区复刻版，仅供学习交流使用。请支持原版作者 ThatMobb。

This is a community edition for educational purposes. Please support the original author ThatMobb.
