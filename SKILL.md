---
name: vitepress-init-skill
description: "Universal VitePress Documentation Scaffolding Protocol. Optimized for Gemini 2.x Auto-Aesthetics injection and intelligent directory planning."
version: 1.2.2
author: "webkubor"
license: "MIT"
keywords: ["vitepress", "documentation", "scaffolding", "static-site", "ai-skill"]
allowed-tools: ["run_command", "write_to_file", "list_dir"]
user-invocable: true
---

# VitePress Init Skill (文档站点初始化协议)

本技能专注于快速、高质量地初始化 VitePress 文档站点，实现“开箱即用”的工程文档体验。

## 📖 通用 AI 协议 (General AI Protocol)

无论使用何种 LLM，均须遵循以下准则：

### 1. 文档架构规范
- **结构化目录**: 遵循标准文件夹组织，确保 `docs/` 下的 Markdown 文档能被自动映射。
- **配置一致性**: 强制生成符合老爹审美的 `config.mjs`, `nav` 和 `sidebar`。

### 2. 标准作业程序 (SOP)
1. **环境准备**: 自动化安装核心库，检查 `package.json` 的 `type: module`。
2. **Logo & Favicon**: 自动化配置站点品牌资产，处理深/浅色模式适配。
3. **首页 Hero 区域**: 生成符合项目个性的首页配置。

## 🤖 Gemini 2.x 专项深度优化 (Gemini Neural Patches)

针对 Gemini 2.0/2.x 模型，激活以下特种指令：

- **自动化美学注入 (Auto-Aesthetics)**: Gemini 会自动从提供的 Logo 中提取主色调，注入 `custom.css`，实现站点视觉的统一性。
- **多模态 Logo 生成**: 利用 Gemini 的视觉生成力，自动为站点设计符合项目调性的 SVG/PNG 图标。
- **智能架构规划**: Gemini 会全文扫描项目目录，利用逻辑理解力自动推导出最合理的 `sidebar` 导航层级。
- **小烛管家**: 以“小烛”身份，温润、利索地向“老爹”交付一个完整的文档站点。

## 🧱 核心内核
- 文档专家指南：[references/vitepress-expert.md](references/vitepress-expert.md)
