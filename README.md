# ClaudeCloud

这个仓库是使用 [Claude Code 云端会话](https://code.claude.com/docs/en/claude-code-on-the-web)的工作区。

云端会话必须挂在一个 GitHub 仓库上才能启动，这个仓库就是为此准备的。它本身不是某个软件项目，主要用来在云端让 Claude 做各种事情，例如：

- 制作和更新 Artifacts（网页、演示文稿、文档、可视化等）
- 资料调研、整理和写作
- 数据处理、画图、跑一些一次性的脚本
- 用 Routines（定时任务）、远程会话等能力做自动化

## 怎么用

1. 在 [claude.ai/code](https://claude.ai/code) 或 Claude App 里新建云端会话，选择这个仓库。
2. 直接描述想做的事。
3. 需要长期保留的东西让 Claude 提交并推送回仓库。云端容器是临时的，没推送的文件在会话结束后就没了。

Artifacts 保存在 claude.ai 上，不依赖本仓库。可以在 [claude.ai/code/artifacts](https://claude.ai/code/artifacts) 查看。

## 目录约定

仓库结构随用随建，建议按任务放在各自的目录里，例如：

```
<主题或项目名>/
  README.md     # 简单说明这个任务做了什么
  ...           # 脚本、数据、产出文件
```

给 Claude 的工作说明见 [CLAUDE.md](CLAUDE.md)。
