# persona-style-migration · 博主人设蒸馏与文风迁移

> 研究/复刻博主表达风格，把内容改写成目标文风，生成对话 AI 人设配置。

博主人设蒸馏与文风迁移方法论。三阶段工作流：① 全网采集并蒸馏出目标博主的人物骨架与文风技法；② 将技法迁移到用户自身内容（保事实、迁技法、不换人设、补标签）；③ 生成对话类 AI 产品的个性化配置（以 DeepSeek「AI 对我的了解」4 模块为模板）。

## 📦 包含的 Skills

### `persona-style-migration`
博主人设蒸馏与文风迁移方法论。当用户想研究/复刻某个博主或 KOL 的表达风格、把内容改成某博主文风、让 AI 输出更像某博主、或给对话产品写人设配置时使用。



## 🚀 安装与使用

这些 skills 面向 [WorkBuddy](https://www.codebuddy.cn) 的 skill 体系（亦兼容 Claude Code / Codex 等同类 skill 目录）。

```bash
git clone https://github.com/bhkjhbkjb/persona-style-migration.git
# 把需要的 skill 文件夹复制到你的 skills 目录
cp -r persona-style-migration/<skill-name> ~/.workbuddy/skills/
```

在 WorkBuddy 中直接以 skill 名称触发即可（如输入 `/<skill-name>` 或自然语言描述）。

## 📂 目录结构

```
persona-style-migration/
├── SKILL.md
└── references/
    ├── distillation-framework.md
    ├── style-migration-method.md
    ├── deepseek-config-template.md
    └── shuipao-corpus.md
```

## 🔒 安全说明

本仓库已去除敏感信息（服务器 IP、API 密钥、内部地址等），相关位置以占位符（如 `<DEPLOY_SERVER_IP>`、`<MOMENT_RESEARCH_HOST>`）标注，请按你自己的运行环境替换。

---

*由 **Hreed** 维护 · 欢迎 Star / 提 Issue*
