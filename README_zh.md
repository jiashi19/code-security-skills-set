# 🛡️ Code Security Skills Set

中文 | [English](./README.md)

本项目旨在收集和分类整理面向 AI Agent 工作流（如 Claude Code、OpenClaw、MCP 等）的代码安全审计、漏洞挖掘以及 Agent 自身安全的技能（Skills）、插件（Plugins）和工具。

## 📑 目录导航

* [SAST & 静态分析](#1-sast--静态分析)
* [应用安全 & 漏洞挖掘](#2-应用安全--漏洞挖掘)
* [智能合约审计](#3-智能合约审计)
* [Agent/Skill 自身安全检测](#4-agentskill-自身安全检测)
* [综合技能集合](#5-综合技能集合)

## 1. SAST & 静态分析
为 Agent 提供强大的静态代码扫描能力（包括调用 CodeQL、Semgrep 等）。
* [trailofbits/skills](https://github.com/trailofbits/skills/tree/main/plugins/static-analysis) - Trail of Bits 出品，包含调用 CodeQL、Semgrep 以及 SARIF 解析的技能。
* [semgrep/skills](https://github.com/semgrep/skills) - Semgrep 官方出品，运行 Semgrep 静态分析扫描并为安全漏洞和 Bug 模式创建自定义检测规则。
* [EastSword/skill-dfyx_code_security_review](https://github.com/EastSword/skill-dfyx_code_security_review) - 面向中文社区的全面代码审计 skill，基于丰富的案例库和 AI 的推理能力设计。
* [RuoJi6/java-audit-skills](https://github.com/RuoJi6/java-audit-skills) - Java 审计技能集合。

## 2. 应用安全 & 漏洞挖掘
辅助安全研究员或开发人员在代码库中寻找注入、凭证泄露等逻辑漏洞。
* [ghostsecurity/skills](https://github.com/ghostsecurity/skills) - Ghost Security 提供的 AppSec 技能集合，供 Agent 使用。
* [UseAI-pro/openclaw-skills-security](https://github.com/UseAI-pro/openclaw-skills-security) - 主要面向 **OpenClaw** ，检测skill的prompt注入、凭证泄露等。
* [eth0izzle/security-skills](https://github.com/eth0izzle/security-skills) - 帮助安全团队保持安全的专属技能集。
* [instavm/security-skills](https://github.com/instavm/security-skills) - 将大量真实安全报告凝练为可用技能的仓库。

## 3. 智能合约审计
* [kadenzipfel/scv-scan](https://github.com/kadenzipfel/scv-scan) - 针对 Solidity 的安全扫描 skill，专为 Web3 和智能合约审计设计。

## 4. Agent/Skill 自身安全检测
AI 基础设施自身的安全防护（红队测试、防止恶意 Skill、越权操作等）。
* [huifer/skill-security-scan](https://github.com/huifer/skill-security-scan) - 专注检测 Skills 安全性的 CLI 工具，建议在安装第三方 skill 前进行风险检查。
* [cisco-ai-defense/skill-scanner](https://github.com/cisco-ai-defense/skill-scanner) - Cisco 的 Agent-Skill 安全扫描器，面向风险检测。
* [snyk/agent-scan](https://github.com/snyk/agent-scan) - Snyk 的 Agent/MCP 扫描工具，在机器上发现并扫描智能体组件，以便检测prompt 注入和漏洞（包括agents、MCP 服务器和skills）。
* [Tencent/AI-Infra-Guard](https://github.com/Tencent/AI-Infra-Guard) - 腾讯开源的面向 AI 平台/Agent/Skill 的红队安全检测综合扫描平台。
* [prompt-security/clawsec](https://github.com/prompt-security/clawsec) - OpenClaw 等相关agent平台的安全技能套件，专门保护agent自身的安全。
* [adversa-ai/secureclaw](https://github.com/adversa-ai/secureclaw) - OpenClaw 的安全插件。

## 5. 综合技能集合
包含但不限于安全的通用大型合集。
* [affaan-m/everything-claude-code](https://github.com/affaan-m/everything-claude-code) - 一个大型的 Claude Code skills & 插件集合。

## 🤝 贡献
仍待完善，欢迎 Pull Request 或 Issue。

## 📄 许可证
[MIT License](LICENSE)