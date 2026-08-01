# Verity-CE

Verity 模组社区版 | 支持自定义 AI API、TTS/STT 配置、多版本适配。原版 by ThatMobb，社区维护版。

## 原版状态

原版 Verity Mod 已从 CurseForge/Modrinth 下架，本仓库基于反编译的 Verity 2.1.0 进行修复和功能增强。

## 改进内容

### 1. 版本适配
- Minecraft 1.21.1（原版 1.21.11 兼容性差）
- GeckoLib 4.9.1（Maven 仓库直拉，无需本地 JAR）

### 2. API 解耦
原版硬编码 ChatGPT，国内无法使用。现支持：
- **自定义 API 端点**（豆包、Groq、OpenRouter 等）
- **自定义模型名称**
- **可配置 TTS/STT 参数**

### 3. Bug 修复
- 修复 GeckoLib 4.x API 迁移问题
- 修复反编译导致的类型转换错误
- 移除残留示例代码
- 解决多端实体生成冲突

## 下载

见 [Releases](../../releases)

## 配置说明

在 `config/verity-common.toml` 中配置：

```toml
[api]
apiBaseUrl = "https://api.example.com/v1"
apiKey = "your-api-key"
modelName = "gpt-4o"

[tts]
ttsBaseUrl = "https://tts.example.com"
ttsModel = "zh-CN-XiaoxiaoNeural"


#官方文档与下载渠道仅为 GitHub Release 页面，其他第三方网站（如 verity-mod.com）为社区贡献，请注意甄别
