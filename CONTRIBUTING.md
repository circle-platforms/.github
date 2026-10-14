# Contributing to circle-platforms

Each repository has its own `CONTRIBUTING.md` with its environment, checks and review rules, and an `AGENTS.md` for coding agents. Read those first: [circle](https://github.com/circle-platforms/circle/blob/main/CONTRIBUTING.md) · [circle-hub](https://github.com/circle-platforms/circle-hub/blob/main/CONTRIBUTING.md) · [circle-packs](https://github.com/circle-platforms/circle-packs/blob/main/CONTRIBUTING.md).

Rules shared by all three:

- Inspect status and diffs and preserve other people's work. Stage explicit paths; never use `git add -A`, `git add .` or `git commit -a`.
- Commit messages are one capitalized imperative English sentence without a prefix or final full stop.
- Keep credentials, internal addresses (samples use 192.0.2.0/24), raw business data and local absolute paths out of Git.
- Verification runs on synthetic sources and samples only: no real systems, paid models or real devices.
- Contributions follow the license of the part they change and the contributor terms in the target repository's `CONTRIBUTING.md`. The three product repositories publish code and ordinary documentation under Apache-2.0; the designated design specifications in circle and circle-hub use CC BY 4.0. Third-party content retains its source, license and notices.

**中文** · 三个仓库各有自己的 CONTRIBUTING.md（环境、检查、评审规则）和给编程助手的 AGENTS.md，先读那两份。共用规则：查看状态与 diff、保留他人工作；显式 stage，不用 `git add -A`、`git add .`、`git commit -a`；提交信息一句首字母大写的英文祈使句，无前缀无句号；口令、内网地址（样例用 192.0.2.0/24）、真实业务数据、本机绝对路径不进 Git；验收只用合成来源和样本。贡献遵循所修改部分的许可证，以及目标仓库 CONTRIBUTING.md 中的贡献者条款。三个产品仓库的代码和一般文档使用 Apache-2.0；circle 与 circle-hub 指定的设计规范使用 CC BY 4.0；第三方内容保留其来源、许可证与声明。
