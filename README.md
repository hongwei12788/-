# check-requirements

一个用于验收 AI 生成代码的 Codex skill。

它适合用来检查：

- 代码是否满足用户需求
- 是否遗漏了边界条件或约束
- UI 文案、输出格式、文件名、路径是否一致
- 变更是否有足够的测试或运行证据

## 使用方式

在 Codex 中直接调用：

```text
$check-requirements
```

也可以直接把需求说明、代码片段、diff 或截图发给 Codex，然后让它按这个 skill 做验收。

## 目录结构

```text
check-requirements/
  SKILL.md
  agents/
    openai.yaml
  references/
    acceptance-checklist.md
```

## 安装

把整个 `check-requirements` 文件夹放到你的 Codex skills 目录下。

Windows 默认路径：

```text
C:\Users\<you>\.codex\skills\
```

安装后重启 Codex 或刷新 skills 列表即可。

## 适用场景

- 让 AI 写完代码后做验收
- 审核一个 PR 或 diff 是否真的满足需求
- 检查功能、文案、格式、边界条件是否对齐

