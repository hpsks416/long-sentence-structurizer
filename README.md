# long-sentence-structurizer

当用户输入一段极其冗长、包含多级修饰语（"可...的...的..."）、主语宾语嵌套，或者隐含多个前置条件的需求描述时。

## 环境依赖

- 操作系统：Windows
- 运行时：无（纯指令型 skill，由 agent 直接执行）
- 第三方软件：无（仅依赖系统自带的 PowerShell / 标准库）

## 目录结构

    long-sentence-structurizer/
    ├── SKILL.md    技能入口与工作流
    ├── evals.yaml

## 安装

    # GitHub
    git clone https://github.com/hpsks416/long-sentence-structurizer.git "$env:USERPROFILE\.dsh\skills\long-sentence-structurizer"
    # 或 Gitee（国内直连）
    git clone https://gitee.com/hpsks416/long-sentence-structurizer.git "$env:USERPROFILE\.dsh\skills\long-sentence-structurizer"

克隆后 DSH 自动重新发现，无需构建。

## License

MIT License. See [LICENSE](LICENSE).
