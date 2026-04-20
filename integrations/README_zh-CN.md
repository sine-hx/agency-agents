# 🔌 集成

本目录包含 Agency 集成以及支持的智能编程工具的转换格式。

## 支持的工具

- **[Claude Code](#claude-code)** — `.md` 智能体，直接使用仓库
- **[GitHub Copilot](#github-copilot)** — `.md` 智能体，直接使用仓库
- **[Antigravity](#antigravity)** — `SKILL.md` 每个智能体在 `antigravity/` 目录
- **[Gemini CLI](#gemini-cli)** — 扩展 + `SKILL.md` 文件在 `gemini-cli/` 目录
- **[OpenCode](#opencode)** — `.md` 智能体文件在 `opencode/` 目录
- **[OpenClaw](#openclaw)** — `SOUL.md` + `AGENTS.md` + `IDENTITY.md` 工作空间
- **[Cursor](#cursor)** — `.mdc` 规则文件在 `cursor/` 目录
- **[Aider](#aider)** — `CONVENTIONS.md` 在 `aider/` 目录
- **[Windsurf](#windsurf)** — `.windsurfrules` 在 `windsurf/` 目录
- **[Kimi Code](#kimi-code)** — YAML 智能体规范在 `kimi/` 目录

## 快速安装

```bash
# 自动安装所有检测到的工具
./scripts/install.sh

# 安装特定的主目录范围工具
./scripts/install.sh --tool antigravity
./scripts/install.sh --tool copilot
./scripts/install.sh --tool openclaw
./scripts/install.sh --tool claude-code

# Gemini CLI 在全新克隆后需要先生成集成文件
./scripts/convert.sh --tool gemini-cli
./scripts/install.sh --tool gemini-cli
```

对于项目范围的工具，如 OpenCode、Cursor、Aider 和 Windsurf，请从目标项目根目录运行安装程序，如下面各工具特定部分所示。

## 重新生成集成文件

如果您添加或修改了智能体，请重新生成所有集成文件：

```bash
./scripts/convert.sh
```

---

## Claude Code

Agency 最初是为 Claude Code 设计的。智能体无需转换即可原生工作。

```bash
cp -r <category>/*.md ~/.claude/agents/
# 或一次性安装所有内容：
./scripts/install.sh --tool claude-code
```

详见 [claude-code/README.md](claude-code/README.md)。

---

## GitHub Copilot

Agency 也可与 GitHub Copilot 原生配合使用。智能体可以直接复制到 `~/.github/agents/` 和 `~/.copilot/agents/` 而无需转换。

```bash
./scripts/install.sh --tool copilot
```

详见 [github-copilot/README.md](github-copilot/README.md)。

---

## Antigravity

技能安装到 `~/.gemini/antigravity/skills/`。每个智能体成为以 `agency-` 为前缀的独立技能，以避免命名冲突。

```bash
./scripts/install.sh --tool antigravity
```

详见 [antigravity/README.md](antigravity/README.md)。

---

## Gemini CLI

智能体打包为 Gemini CLI 扩展，包含独立的技能文件。扩展安装到 `~/.gemini/extensions/agency-agents/`。
由于 Gemini 清单和技能文件夹是生成的产物，在全新克隆后安装前需要运行 `./scripts/convert.sh --tool gemini-cli`。

```bash
./scripts/convert.sh --tool gemini-cli
./scripts/install.sh --tool gemini-cli
```

详见 [gemini-cli/README.md](gemini-cli/README.md)。

---

## OpenCode

每个智能体成为项目范围的 `.md` 文件，位于 `.opencode/agents/`。

```bash
cd /your/project && /path/to/agency-agents/scripts/install.sh --tool opencode
```

详见 [opencode/README.md](opencode/README.md)。

---

## OpenClaw

每个智能体成为包含 `SOUL.md`、`AGENTS.md` 和 `IDENTITY.md` 的 OpenClaw 工作空间。

安装前，生成 OpenClaw 工作空间：

```bash
./scripts/convert.sh --tool openclaw
```

然后安装：

```bash
./scripts/install.sh --tool openclaw
```

详见 [openclaw/README.md](openclaw/README.md)。

---

## Cursor

每个智能体成为 `.mdc` 规则文件。规则是项目范围的 — 从项目根目录运行安装程序。

```bash
cd /your/project && /path/to/agency-agents/scripts/install.sh --tool cursor
```

详见 [cursor/README.md](cursor/README.md)。

---

## Aider

所有智能体整合到单个 `CONVENTIONS.md` 文件中，Aider 在项目根目录中检测到此文件时会自动读取。

```bash
cd /your/project && /path/to/agency-agents/scripts/install.sh --tool aider
```

详见 [aider/README.md](aider/README.md)。

---

## Windsurf

所有智能体整合到单个 `.windsurfrules` 文件中，用于项目根目录。

```bash
cd /your/project && /path/to/agency-agents/scripts/install.sh --tool windsurf
```

详见 [windsurf/README.md](windsurf/README.md)。

---

## Kimi Code

每个智能体转换为 Kimi Code CLI 智能体规范（YAML 格式，带独立的系统提示文件）。智能体安装到 `~/.config/kimi/agents/`。

由于 Kimi 智能体文件是从源 Markdown 生成的，在全新克隆后安装前需要运行 `./scripts/convert.sh --tool kimi`。

```bash
./scripts/convert.sh --tool kimi
./scripts/install.sh --tool kimi
```

### 使用方法

安装后，使用 `--agent-file` 标志来使用智能体：

```bash
kimi --agent-file ~/.config/kimi/agents/frontend-developer/agent.yaml
```

或在特定项目中：

```bash
cd /your/project
kimi --agent-file ~/.config/kimi/agents/frontend-developer/agent.yaml \
     --work-dir /your/project
```

详见 [kimi/README.md](kimi/README.md)。