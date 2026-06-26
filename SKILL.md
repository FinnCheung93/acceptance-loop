---
name: subagent-review-loop
description: 用真实 subagent 执行“审阅-修订-复查-收拢”工作法。适用于用户明确要求 subagent、群侠会审、review loop、独立审阅、多角色验收、react 审阅 loop，或要求“用子 agent 审到高优先级问题没问题”的方案、文档、skill、模板、迁移计划和高风险改动。普通 review、看看、列问题不默认触发，除非用户同意升级。
metadata:
  chinese-name: 群侠会审
  version: v0.1.0
  updated: 2026-06-26
---

# Subagent Review Loop

先设定本轮目标，然后用真实 subagent 独立审阅对象。主 agent 根据意见处理，再让 subagent 复查。

问题可以用 P0/P1/P2/P3，也可以用等价优先级。高优先级问题必须修复、证伪或转用户裁决；低优先级问题不要求清零。

不要用主 agent 角色扮演冒充 subagent。不要把主 agent 的预设答案提前泄漏给首轮 reviewer。没有写入授权时，只给审阅结论和修改建议。

收尾时说明：本轮目标、参与审阅的 subagent、高优先级问题是否清零、是否改了文件、最终状态。
