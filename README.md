# 仓库更新观察台

为 yosayss 跟踪数字生命卡兹克的公开项目和 REA，整理重要版本、功能变化、兼容性风险和建议行动。

## 跟踪范围

- GitHub 账号 [KKKKhazix](https://github.com/KKKKhazix) 下的公开非 Fork 仓库，并发现新项目。
- [morluto/rea](https://github.com/morluto/rea)。

具体清单见 watchlist.json。外部项目只读，不代表获得其维护权限。

## 工作方式

此仓库作为 Super-agent 的任务和成果仓库。采用 yosayss 单账号本地适配：新建 Issue，标题以 `[Superagent Task] ` 开头，正文第一行写 `/superagent @yosayss`，换行后写具体请求。普通评论中 @自己不会派活。接入完成前，现有 DSH 会话定时监控继续执行。

第一阶段成果回复原 Issue；仓库内 Markdown 报告和 PR 需另行启用独立 worktree 并验收，不把尚未启用的功能称为可用。

更新报告应给出项目、核查时间、上次与本次版本或提交、变化内容、实际影响、原始链接和未验证边界。小修复合并汇总；没有重要变化不制造结论。

## 当前接入状态

这些文件是本地准备内容，尚未推送。GitHub 机器人账号、协作者权限、登录验证和首次任务验收完成后，才能标记接入成功。

本仓库不保存任何令牌、密码、个人聊天、机器配置或私人记忆。
