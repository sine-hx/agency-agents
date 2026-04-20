# Claude Code 集成

Agency 是为 Claude Code 构建的。无需转换 — 智能体使用现有的 `.md` + YAML 前置数据格式原生工作。

## 安装

```bash
# 将所有智能体复制到您的 Claude Code 智能体目录
./scripts/install.sh --tool claude-code

# 或手动复制某个类别
cp engineering/*.md ~/.claude/agents/
```

## 激活智能体

在任何 Claude Code 会话中，通过名称引用智能体：

```
激活 Frontend Developer 帮我构建一个 React 组件。
```

```
使用 Reality Checker 智能体验证此功能是否可投入生产。
```

## 智能体目录

智能体按部门组织。完整当前名单请参见[主 README](../../README.md)。