# long-sentence-structurizer

将充满嵌套、长难句的"工程口语"或模糊的自然语言需求，自动拆解并重写为高度结构化的Markdown提示词（包含目标、约束、步骤、前置条件）。在用户提供复杂系统设计、UI交互逻辑或长篇需求描述时触发。

## 这是什么

DSH（DeepSeek Harness）skill —— 一个可由 AI agent 按需自动加载的能力单元。克隆到 skill 目录后，DSH 会依据上方描述自动发现并触发它，无需构建。

## 安装

最简单：用 [dsh-config](https://github.com/hpsks416/dsh-config) 的一键脚本 `install.ps1` 批量安装全部 skill。单个安装：

    # GitHub
    git clone https://github.com/hpsks416/long-sentence-structurizer.git "$env:USERPROFILE\.dsh\skills\long-sentence-structurizer"
    # 或 Gitee（国内直连更快）
    git clone https://gitee.com/hpsks416/long-sentence-structurizer.git "$env:USERPROFILE\.dsh\skills\long-sentence-structurizer"

克隆后 DSH 会自动重新发现，无需重启。更新用：

    git -C "$env:USERPROFILE\.dsh\skills\long-sentence-structurizer" pull

## 目录结构

    long-sentence-structurizer/
    ├── SKILL.md    技能入口与工作流
    ├── evals.yaml

## 依赖

无运行时依赖，纯指令型 skill（由 agent 直接执行 Markdown 工作流）。

## License

MIT License. See [LICENSE](LICENSE).
