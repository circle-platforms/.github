# circle-platforms

**Circle Platforms makes agent work verifiable, shareable and schedulable.** Circle is the agent you work with; circle-hub is the hub it connects to, which checks what agents hand back, keeps the knowledge that passed, and shares the methods a team works by.

## One set of principles

Individuals and teams use the same design:

- **Verify, never generate.** The hub calls no model. It checks what an agent submits: every exact value resolves to a source, every quotation is compared verbatim, and checks are re-run in a sandbox.
- **Nothing counts without a source.** Knowledge enters only with its provenance and can always be traced back to the original.
- **Records are append-only.** What happened is kept; current state is derived from the records.
- **Unknown stays unknown.** It is never shown as a pass or a failure, and conflicting claims are kept side by side.
- **Product knowledge lives in packs.** The core names no product; packs carry the product, system and workflow content.
- **Bring your own model.** Circle works with any OpenAI- or Anthropic-compatible endpoint, and the hub is a standard MCP server any client can use.

## Repositories

| Repository | What it is | Start here |
|---|---|---|
| [circle](https://github.com/circle-platforms/circle) | The agent, in the terminal and in its own window: it reads and edits code, runs commands after asking, drives a browser and device terminals (SSH, Telnet) as a person would, and uses secrets by name so the model never sees them | [Documentation](https://circle-platforms.github.io/circle/) · [Quickstart](https://circle-platforms.github.io/circle/quickstart/) |
| [circle-hub](https://github.com/circle-platforms/circle-hub) | The hub: a standard MCP server that verifies results and never generates them, with task packs, a content-addressed knowledge tree per product line and version, read-only connectors to business systems, append-only records and a read-only console | [Documentation](https://circle-platforms.github.io/circle-hub/) · [Design](https://github.com/circle-platforms/circle-hub/blob/main/docs/design/README.md) ([English](https://github.com/circle-platforms/circle-hub/blob/main/docs/design/en/README.md)) · [Compatibility matrix](https://github.com/circle-platforms/circle-hub/blob/main/docs/compatibility.md) |

## Where we are heading

This is the direction, not what ships today; see each repository for its current state.

**For you**

- **Your knowledge base.** Whatever you read through any Circle client, from any source, is kept in the hub as knowledge you can search and cite again from any other client.
- **Your agents, everywhere.** Each Circle you use, in a terminal or in the desktop application, shows its state to the hub, so you can see what the others are doing and continue there.
- **Your channels.** Telegram, WeChat, WeCom or Feishu reach the hub to receive and send messages, so you can work and hand work to others outside Circle.

**For teams**

- **One interface to every system.** Packs handle the interfaces of each workflow and product line, so data is scheduled and managed in one place instead of sitting in silos.
- **Shared workflows.** A pack uploaded once gives everyone the same process for tasks and collaboration.
- **Scheduled work.** Bots and scheduled tasks keep watch around the clock and keep the team's technical knowledge current, with less back-and-forth.
- **Audit and traceability.** Records and logs show how knowledge flows and how the hub is used, per person and per workflow.

## Status and contributing

Both repositories are under development and are not supported production releases. Maintainers track cross-repository work on the [internal Circle platforms project board](https://github.com/orgs/circle-platforms/projects/1), which is not accessible to public visitors. Public plans and open work are recorded in [circle Issues](https://github.com/circle-platforms/circle/issues) and [circle-hub Issues](https://github.com/circle-platforms/circle-hub/issues). Each repository has its own `CONTRIBUTING.md` and an `AGENTS.md` for coding agents; security reports go through that repository's private vulnerability reporting (see [SECURITY](https://github.com/circle-platforms/.github/blob/main/SECURITY.md)).

---

## 中文

**Circle Platforms 让 agent 的工作可核验、可共享、可调度。**Circle 是你使用的 agent；circle-hub 是它连接的 Hub：核验 agent 交回的结果，保存通过核验的知识，让团队共用同一套方法。

### 同一套原则

个人和团队用的是同一套设计：

- **只核验，不生成。**Hub 不调用任何模型，只核对 agent 交上来的东西：每个精确值都追到来源，每段引文逐字比对，检查在沙箱里重跑。
- **有出处才算数。**知识带着来源进来，随时能追回原文。
- **记录只追加。**发生过的事都留下，当前状态由记录推出。
- **未知保持未知。**不把未知说成通过或失败，矛盾的说法并存标记。
- **产品知识放在包里。**核心不点名任何产品，产品、系统和工作流的内容由包承载。
- **模型自己选。**Circle 能接任何兼容 OpenAI 或 Anthropic 接口的端点，Hub 是标准 MCP 服务器，任何客户端都能用。

### 仓库

- [circle](https://github.com/circle-platforms/circle)：agent，终端里用，也有自己的窗口。读代码、改文件，运行命令前先问你；能像人一样操作浏览器和设备终端（SSH、Telnet）；密钥按名字引用，模型看不到真实值。入口：[文档](https://circle-platforms.github.io/circle/) · [快速开始](https://circle-platforms.github.io/circle/quickstart/)
- [circle-hub](https://github.com/circle-platforms/circle-hub)：Hub，一个只校验、不生成的标准 MCP 服务器。有任务包、按产品线和版本组织的内容寻址知识树、对业务系统的只读连接器、只追加的记录和只读控制台。入口：[文档](https://circle-platforms.github.io/circle-hub/) · [设计](https://github.com/circle-platforms/circle-hub/blob/main/docs/design/README.md) · [兼容矩阵](https://github.com/circle-platforms/circle-hub/blob/main/docs/compatibility.md)

### 发展方向

下面是方向，不是现在已经提供的功能；各仓库的现状见各自的说明。

**对个人**

- **你的个人资料库。**无论从哪里、连接什么资料得到的信息，都以知识库的方式保存在 Hub 上，在任何 Circle 客户端里都能积累和查询。
- **你的多个终端。**无论在哪里使用 Circle，终端还是客户端，工作状态都同步到 Hub，换一个终端也能看到其他终端在做什么，接着做下去。
- **你的消息入口。**接上 Telegram、微信、企业微信、飞书，通过 Hub 实时收发消息，在 Circle 以外的平台沟通，或者把想法和工作交给别人。

**对企业**

- **各工作流和产品线的统一接口。**用 Hub 的任务包统一处理各类应用接口，数据不再是一座座堡垒，而是统一调度和管理。
- **共享的工作流环境。**上传一次任务包，每个员工都用同一套流程做任务、协作，不再各自为战。
- **定时工作流助手。**bot 全天候监控，计划任务按时运行，随时更新最新的技术知识和能力，减少沟通成本和事务传达。
- **审计与追溯。**通过审计和日志，按人、按工作流查看知识流向和 Hub 的使用情况，管理企业的资源和信息。

### 状态与参与

两个仓库都在开发中，不是受支持的生产发行。跨仓工作看板供维护者内部使用，公开访客无法访问；公开计划与待办见上面两个仓库的 Issues。各仓库有自己的 `CONTRIBUTING.md` 和给编程助手的 `AGENTS.md`；安全问题通过所在仓库的私密漏洞报告提交（见 [SECURITY](https://github.com/circle-platforms/.github/blob/main/SECURITY.md)）。
