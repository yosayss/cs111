# 仓库更新观察台

为 yosayss 跟踪数字生命卡兹克的公开项目和 REA，整理重要版本、功能变化、兼容性风险和建议行动。

## 跟踪范围

- GitHub 账号 [KKKKhazix](https://github.com/KKKKhazix) 下的公开非 Fork 仓库，并发现新项目。
- [morluto/rea](https://github.com/morluto/rea)。

具体清单见 watchlist.json。外部项目只读，不代表获得其维护权限。

## 工作方式

此仓库作为 Super-agent 的任务和成果仓库。采用 yosayss 单账号本地适配：新建 Issue，标题以 `[Superagent Task] ` 开头，正文第一行写 `/superagent @yosayss`，换行后写具体请求。普通评论中 @自己不会派活。现有 DSH 会话定时监控作为兜底继续执行。

第一阶段成果回复原 Issue；仓库内 Markdown 报告和 PR 需另行启用独立 worktree 并验收，不把尚未启用的功能称为可用。

更新报告应给出项目、核查时间、上次与本次版本或提交、变化内容、实际影响、原始链接和未验证边界。小修复合并汇总；没有重要变化不制造结论。

## 当前接入状态（2026-11-05）

已接入并完成端到端验收：账号 yosayss、监听仓库 yosayss/cs111、单账号任务入口、白名单与单 worker 均已配置。[验收任务 #1](https://github.com/yosayss/cs111/issues/1) 被自动接单、执行并在原 Issue 用中文交付，工单正常结束。验收入口 `node F:/11111/superagent-connection/verify.cjs`（退出码 0 全过 / 2 外部网络降级 / 1 配置或服务故障）。

定时更新检查发现重要变化后，会在此仓库创建上述格式的任务 Issue，由 Super-agent 只读分析并在原 Issue 交付；服务或网络未就绪时先留在会话内汇报，恢复后补派，不丢事件。

本仓库不保存任何令牌、密码、个人聊天、机器配置或私人记忆。
