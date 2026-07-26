# Concerta

Concerta 是一个事实驱动、专注且克制的通用 Codex Skill。它会先明确目标、事实与约束，遵循既有风格并优先复用现有成果，再选择最小充分方案、完成有效验证并简洁报告。

适用于代码编写、修改、调试与评审，也适用于研究、分析、规划、写作、内容制作和资源搜集等非简单任务。

灵感来自于 ADHD 的工作日常习惯，把一些常犯的错误和规避方法融合到 Skill 中。不过现在最新版本的 Codex 模型已经足够强大了，所以很多原本的条条框框限制我也去掉了。

## 安装

### 使用 Skill Installer

在 Codex 中输入：

```text
$skill-installer install https://github.com/XUMUMI/Concerta/tree/main/skills/concerta
```

安装后新建任务即可使用。

### 手动安装

克隆仓库：

```bash
git clone https://github.com/XUMUMI/Concerta.git
```

将仓库中的 `skills/concerta` 目录复制到 Codex 的 Skill 目录：

```text
~/.codex/skills/concerta
```

Windows 对应路径为：

```text
%USERPROFILE%\.codex\skills\concerta
```

安装完成后，目标目录应直接包含：

```text
concerta/
├── SKILL.md
└── agents/
    └── openai.yaml
```

## 使用

Concerta 可以根据任务内容自动触发，也可以显式调用：

```text
Use $concerta to <task>.
```

## 许可证

MIT
