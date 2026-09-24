# 实现完整性审查

[English](README.md) | 简体中文

一个简洁、通用的代码审查 Skill，适用于支持 Agent Skills 的 AI 编程工具。

## 安装

```bash
npx skills add addxing/implementation-review
```

## 使用

```text
使用 $implementation-review 审查当前实现。
```

也可以指定审查范围：

```text
使用 $implementation-review 审查登录功能，重点检查异常处理和状态同步。
```

## 审查内容

- 无效代码、需求遗漏和功能不完整。
- 实现错误，以及影响用户体验、稳定性或现有功能的问题。
- 审查过程中发现的其他潜在问题。

技能正文保持简短，不限定项目语言、技术栈或固定输出格式。审查依据来自当前对话及可访问的代码和需求；使用时可补充需求文档、目标目录或提交范围。

## 文件说明

- `SKILL.md`：技能指令。
- `agents/openai.yaml`：Codex 界面名称、简介和默认提示词。
- `skills.sh.json`：skills.sh 分组配置。
- `README.md`、`README.zh.md`：英文和中文使用说明。
- `LICENSE.txt`：Apache 2.0 许可证。

## 许可证

[Apache License 2.0](LICENSE.txt)
