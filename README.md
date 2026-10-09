# High-Density Writing

用于正式文章、研究报告、分析材料、商业文案和技术文档的写作与润色技能。保留事实、证据边界和作者语气，删除套话与重复，让结论、主次和因果更清楚。

## 文件

- [SKILL.md](SKILL.md)：完整技能定义与写作规则。

## 安装到 Codex

将仓库克隆到个人技能目录。Windows PowerShell 示例：

```powershell
git clone https://github.com/chester890222/high-density-writing.git "$env:USERPROFILE\.agents\skills\high-density-writing"
```

如果该目录已存在，先比较已有文件，避免覆盖本地修改。安装后重新启动 Codex 会话以加载技能。

## 使用

在请求中指定 `$high-density-writing`，并提供原文或写作任务。例如：

```text
$high-density-writing 润色以下研究报告，保留原有数据、引用和观点，删除套话与重复。
```

用户指定的受众、文体、篇幅、语气、结构和修改范围优先于技能的默认偏好。技能约束最终成稿；数据和方法仍由相关领域工作流程负责。
