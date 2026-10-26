# agent-roadmap

从零到 AI Agent 开发的 7 周实验仓库（阶段一：2026.10.12 – 2026.11.29）。
每周一个目录，目录里的 README 写清「任务 / 产出 / 怎么跑 / 验收标准」。

## 7 周路线

| 周 | 日期 | 主题 | 交付物 |
|---|---|---|---|
| W1 | 10.12–10.18 | Git 工作流 + 项目结构 | 规范化的课设仓库 + 本仓库 |
| W2 | 10.19–10.25 | Python 进阶 + CLI 工具 | 带参数解析/异常/日志的 CLI |
| W3 | 10.26–11.01 | HTTP / REST / 异步 | 并发抓取脚本 + 耗时对比 |
| W4 | 11.02–11.08 | 大模型 API 入门 | 4 个 API 脚本（基础/参数/JSON/流式） |
| W5 | 11.09–11.15 | Prompt 工程 + Function Calling | 工具调用 demo + 5 个提示词模板 |
| W6 | 11.16–11.22 | LangChain 最小闭环 | 一条 LCEL 链（结构化输出） |
| W7 | 11.23–11.29 | LangGraph 最小 Agent | 能跑的最小 Agent + 架构图（红线 1） |

## 环境要求

- Python 3.11、uv（本机已有：uv 0.12.10）
- 本机 python **没有 pip**，一律用 uv：

```bash
uv venv .venv --python 3.11
uv pip install --python .venv/Scripts/python.exe -r requirements.txt
```

- 大模型 Key 放 `.env`（从 `.env.example` 复制），**永不提交**
- 运行示例（PowerShell / Git Bash 均可）：

```bash
.venv/Scripts/python.exe week4-llm-api/hello_llm.py
```

## 目录

- `docs/` — 学习日志与每周复盘
- `week1-git-basics/` … `week7-langgraph-agent/` — 每周代码与说明
