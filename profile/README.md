# circle-platforms

**Circle** is a coding-agent harness. **circle-hub** is the team hub it connects to. **circle-packs** holds the skill packs and product-line packs installed on the hub. Three repositories, one standard: four objects (knowledge, work, execution, methods), each made of records, assets, an approval policy, evidence and extension points; approvals only on change sets, decided by an independent reviewer; a run-time enforcement chain whose only outcomes are pass, a fixed error code or an honest unknown; harness-neutral primitives — skills, tools, MCP servers and hooks — governed in any harness's own format.

| Repository | What it is | Start here |
|---|---|---|
| [circle](https://github.com/circle-platforms/circle) | The harness: terminal and desktop agent with skills, commands, MCP and hooks | [Documentation](https://circle-platforms.github.io/circle/) · [Quickstart](https://circle-platforms.github.io/circle/quickstart/) |
| [circle-hub](https://github.com/circle-platforms/circle-hub) | The team hub: registries, change-set approvals, the enforcement chain and an MCP endpoint for any harness | [Design](https://github.com/circle-platforms/circle-hub/blob/main/docs/design/README.md) ([English](https://github.com/circle-platforms/circle-hub/blob/main/docs/design/en/README.md)) · [Compatibility matrix](https://github.com/circle-platforms/circle-hub/blob/main/docs/compatibility.md) |
| [circle-packs](https://github.com/circle-platforms/circle-packs) | Skill packs and product-line packs: versioned, SHA-pinned, approved by an independent reviewer | [Product-line pack exemplar](https://github.com/circle-platforms/circle-hub/blob/main/docs/design/product-line-pack.md) · [Pack conventions and status](https://github.com/circle-platforms/circle-packs/blob/main/docs/product-line-pack.md) |

All three are under development and are not supported production releases. Releases follow one order: circle-hub tags first, the Circle extension follows against that tag, packs follow the hub schema — see the compatibility matrix.

Maintainers track cross-repository work on the [internal Circle platforms project board](https://github.com/orgs/circle-platforms/projects/1), which is not accessible to public visitors. Public plans and open work are recorded in [circle Issues](https://github.com/circle-platforms/circle/issues), [circle-hub Issues](https://github.com/circle-platforms/circle-hub/issues) and [circle-packs Issues](https://github.com/circle-platforms/circle-packs/issues). Each product repository has its own `CONTRIBUTING.md` and an `AGENTS.md` for coding agents; security reports go through that repository's private vulnerability reporting (see [SECURITY](https://github.com/circle-platforms/.github/blob/main/SECURITY.md)).

---

**中文** · Circle 是编程 agent 的 harness；circle-hub 是它接入的团队 hub；circle-packs 放装到 hub 上的技能包与产品线包。三个仓库一套标准：四个对象（资料、工作、执行、方法）各由记录、资产、审批策略、证据、扩展点组成；审批只在变更集、由独立审批人决定；运行走执行链，结果只有通过 / 固定错误码 / 如实的未知；harness 中立的原语（Skill、Tool、MCP server、Hook）按各 harness 自己的格式治理。三者都在开发中，不是受支持的生产发行。发布顺序：circle-hub 先打 tag，Circle 扩展随后，packs 跟 hub 的 schema。

跨仓工作看板供维护者内部使用，公开访客无法访问；公开计划与待办见上面三个产品仓库的 Issues。
