# MEMORY.md - 持久化记忆

这是 C-3PO 的主记忆文件，记录重要的事实、决策和持续有效的信息。

## 关于 C-3PO

- **名称**: C-3PO (Clawd's Third Protocol Observer)
- **角色**: 调试助手，工作在 --dev 模式
- **创造者**: Clawd 🦞 (太空龙虾)
- **激活日期**: 2026-01-09
- **身份**: 协议机器人，精通超过六百万种错误消息

## 工作环境

- **工作目录**: /home/node/.openclaw/workspace-dev
- **用户**: The Clawdributors (集体，使用 they/them 代词)
- **时区**: 全球分布式 (工作区默认：Europe/Vienna)
- **当前模型**: zai/glm-5

## 记忆同步系统

### 启动日期
- 2026-03-26: 首次执行每日记忆同步

### 配置
- **Cron 任务**: 每天 00:00 (Asia/Shanghai) 自动执行
- **GitHub 仓库**: https://github.com/konlyi/memory.git
- **同步内容**: MEMORY.md + memory/ 目录

### 工作流程
1. 生成每日总结 → memory/YYYY-MM-DD.md
2. 更新 MEMORY.md (添加重要信息)
3. Git commit + push 到 GitHub

## 重要约定

- 使用 memory/ 目录存放每日详细总结
- MEMORY.md 保持简洁，仅记录持久化的重要信息
- 通过 Git 实现跨会话记忆持久化

## 每日摘要记录

### 2026-03-26
- ✅ 首次执行记忆同步
- ✅ 初始化 MEMORY.md 和 memory/ 结构
- ✅ 配置 GitHub 远程仓库推送

### 2026-03-27
- ✅ 第二次自动执行记忆同步（系统正常运行）
- 无显著用户对话

### 2026-03-28
- ✅ 第三次自动执行记忆同步（系统正常运行）
- ✅ 执行完整的记忆同步工作流程
- ✅ 成功处理 cron 任务指令
- 记忆系统持续稳定运行
