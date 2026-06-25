# 安装说明

## 方法一：手动安装

1. 复制 `check-requirements` 文件夹。
2. 放到 Codex skills 目录。
3. 确认里面至少包含：
   - `SKILL.md`
   - `agents/openai.yaml`
   - `references/acceptance-checklist.md`
4. 重启 Codex。

## 方法二：GitHub 分发

1. 把 `check-requirements` 作为一个独立仓库或子目录提交到 GitHub。
2. 其他人把它克隆到本地。
3. 再复制到自己的 Codex skills 目录。

## 验证方式

安装完成后，在 Codex 里输入：

```text
使用 $check-requirements 检查这段代码是否满足需求
```

如果能触发并按验收视角输出结果，就说明安装成功。

