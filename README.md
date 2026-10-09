# ClaudeCloud

这个仓库只是使用 [Claude Code 云端会话](https://code.claude.com/docs/en/claude-code-on-the-web)的环境。

云端会话必须挂在一个 GitHub 仓库上才能启动，这个仓库就是为此准备的。它本身不是某个软件项目，也不存放任何工作内容：**仓库里只有 `README.md` 和 `CLAUDE.md` 两个文件。**

在云端让 Claude 做的事情，例如：

- 制作和更新 Artifacts（网页、演示文稿、文档、可视化等）
- 资料调研、整理和写作
- 数据处理、画图、跑一些一次性的脚本
- 用 Routines（定时任务）、远程会话等能力做自动化

## 怎么用

1. 在 [claude.ai/code](https://claude.ai/code) 或 Claude App 里新建云端会话，选择这个仓库。
2. 直接描述想做的事。
3. 产出以 Artifact 或直接发送文件的方式交付，不会提交到仓库。云端容器是临时的，会话结束后容器里的文件就没了。

Artifacts 保存在 claude.ai 上，可以在 [claude.ai/code/artifacts](https://claude.ai/code/artifacts) 查看。

给 Claude 的工作说明见 [CLAUDE.md](CLAUDE.md)。
