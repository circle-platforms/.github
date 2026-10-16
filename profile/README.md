# circle-platforms

**Circle Platforms** helps you work on code with agents, share team knowledge, track tasks, and run workflows with human approval.

Companies already have their own systems: issue trackers, code repositories, knowledge bases, OA, test environments and devices. Connecting agents to them is easy; the hard part is deciding who may touch what, approving each action against its exact content, and leaving evidence others can check. Circle Platforms is built for that. Where it is going and in what order: [platform direction and roadmap](https://github.com/circle-platforms/circle-hub/blob/main/docs/roadmap.en.md).

| Repository | What it is | Start here |
|---|---|---|
| [circle](https://github.com/circle-platforms/circle) | The harness: terminal and desktop agent with skills, commands, MCP and hooks | [Documentation](https://circle-platforms.github.io/circle/) · [Quickstart](https://circle-platforms.github.io/circle/quickstart/) |
| [circle-hub](https://github.com/circle-platforms/circle-hub) | The team hub: registries, change-set approvals, the enforcement chain and an MCP endpoint for any harness | [Design](https://github.com/circle-platforms/circle-hub/blob/main/docs/design/README.md) ([English](https://github.com/circle-platforms/circle-hub/blob/main/docs/design/en/README.md)) · [Compatibility matrix](https://github.com/circle-platforms/circle-hub/blob/main/docs/compatibility.md) |
| [circle-packs](https://github.com/circle-platforms/circle-packs) | Skill packs and product-line packs: versioned, SHA-pinned, approved by an independent reviewer | [Product-line pack exemplar](https://github.com/circle-platforms/circle-hub/blob/main/docs/design/product-line-pack.md) · [Pack conventions and status](https://github.com/circle-platforms/circle-packs/blob/main/docs/product-line-pack.md) |

All three are under development and are not supported production releases. Releases follow one order: circle-hub tags first, the Circle extension follows against that tag, packs follow the hub schema — see the compatibility matrix.

Maintainers track cross-repository work on the [internal Circle platforms project board](https://github.com/orgs/circle-platforms/projects/1), which is not accessible to public visitors. Public plans and open work are recorded in [circle Issues](https://github.com/circle-platforms/circle/issues), [circle-hub Issues](https://github.com/circle-platforms/circle-hub/issues) and [circle-packs Issues](https://github.com/circle-platforms/circle-packs/issues). Each product repository has its own `CONTRIBUTING.md` and an `AGENTS.md` for coding agents; security reports go through that repository's private vulnerability reporting (see [SECURITY](https://github.com/circle-platforms/.github/blob/main/SECURITY.md)).

---

**中文** · Circle Platforms 帮助你用 agent 编写和修改代码、共享团队知识、跟踪任务，并在人的审批下执行工作流程。Circle 是终端与桌面的编程 agent；circle-hub 负责团队共享、任务与审批；circle-packs 提供安装到 hub 的技能包与产品线包。各仓库的文档入口见上表。企业已有的缺陷系统、代码库、知识库、OA、测试环境和设备，接上 agent 并不难，难的是定义谁能动什么、按具体内容批准每个动作、留下别人能核对的证据；Circle Platforms 为此而做，方向和顺序见[平台方向与路线图](https://github.com/circle-platforms/circle-hub/blob/main/docs/roadmap.md)。三者都在开发中，不是受支持的生产发行。发布顺序：circle-hub 先打 tag，Circle 扩展随后，packs 跟 hub 的 schema。

跨仓工作看板供维护者内部使用，公开访客无法访问；公开计划与待办见上面三个产品仓库的 Issues。
