# Geeyum Workflow

可供不同用户复用的通用 AI 协作 Skill。它规范要求理解、提问判断、主动推进、纠正处理、范围控制、验证和交付，不携带行业背景、项目路径或业务接口。

## 直接下载

[下载 ZIP 压缩包](https://github.com/GbrAnd1n/Geeyum-Workflow/archive/refs/heads/main.zip)

[读取 SKILL.md 正文](https://raw.githubusercontent.com/GbrAnd1n/Geeyum-Workflow/main/geeyum-workflow/SKILL.md)

下载 ZIP 后解压，取其中的 `geeyum-workflow` 文件夹安装。压缩包根目录名称由 GitHub 自动生成。

## 安装与使用

在支持 Agent Skills 的 AI 客户端中，将完整的 `geeyum-workflow` 文件夹放入该客户端支持的 skills 目录，或使用其安装工具。

不支持 Skill 安装的聊天平台，可以把 `geeyum-workflow/SKILL.md` 的正文作为自定义指令或对话开始时的协作要求。

显式调用示例：

```text
请使用 $geeyum-workflow，按通用协作规范理解并完成当前任务。
```

`agents/openai.yaml` 是可选的客户端显示信息；核心规则全部位于 `SKILL.md`。

## 边界

当前用户的明确指令优先。这份 Skill 不授予额外操作权限，不预设使用者身份，也不保证每个平台都会自动加载或始终执行所有规则。
