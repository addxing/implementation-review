# Implementation Review

English | [简体中文](README.zh.md)

A concise, general-purpose code review skill for AI coding tools that support Agent Skills.

## Install

```bash
npx skills add addxing/implementation-review
```

## Usage

```text
Use $implementation-review to review the current implementation.
```

You can also specify a scope:

```text
Use $implementation-review to review the login flow, focusing on error handling and state synchronization.
```

## Review Scope

- Dead or ineffective code, missing requirements, and incomplete functionality.
- Implementation errors and issues affecting user experience, stability, or existing features.
- Other potential issues discovered during the review.

The skill instructions are written in Chinese and intentionally kept short. They do not prescribe a language, technology stack, or fixed report format. Reviews use the conversation and accessible code and requirements; provide requirement documents, target directories, or a commit range when useful.

## Files

- `SKILL.md`: skill instructions.
- `agents/openai.yaml`: Codex display metadata and default prompt.
- `skills.sh.json`: skills.sh grouping configuration.
- `README.md` and `README.zh.md`: English and Chinese usage guides.
- `LICENSE.txt`: Apache 2.0 license.

## License

[Apache License 2.0](LICENSE.txt)
