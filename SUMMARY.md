# Workspace Summary

## 当前摘要

`E:\Workspace` 是本地优先的长期工作区。当前已建立 Workspace 级规则、活跃项目登记、项目模板、记忆承载目录和 AOS 项目仓库。

AOS 当前正式基线为 `v0.1.0` 基础底座：AOS 产品仓库 `main @ 7b48fe1`，annotated tag `v0.1.0` 指向 `7b48fe1`。这表示基础底座完成，不代表整个 AOS 产品已经完成。

## 活跃项目

- `project_001_AOS`：v0.1.0 foundation baseline completed / P1 planning and contracts next.

## 已完成

- M0：确认方向、工作规则和关键技术取舍。
- M1：建立 Workspace、项目骨架、核心文档和交接体系。
- M2：完成最小只读 CLI：
  - `aos status`
  - `aos status --json`
  - `aos doctor`
  - `aos doctor --json`
- Ruff 0.15.20 已接入并通过 `check` 与 `format --check`。
- Gitleaks v8.30.1 已接入并通过当前文件与完整 Git 历史扫描。
- 14 个 unittest 已通过。
- AOS `v0.1.0` 基础底座版本点已创建。
- Workspace 与 AOS 两个私有 GitHub 远程仓库已建立并同步。
- GitHub 最小 clone 恢复测试已通过。

## 尚未完成

- Canonical Markdown memory store。
- Knowledge Entry schema 实现。
- Cognee 接入。
- codebase-memory 接入。
- `error` / `reflection` / `memory` / `context` 命令。
- Dashboard。
- MCP 原生支持。
- 自动日志和自动索引。
- 商业授权、同步和 API。

## 下一主线

P1：架构合同与数据规范。

近期顺序：

1. 校准现有文档状态。
2. 建立架构合同和 schema。
3. 建立 Markdown 原始记忆层。
4. 接入 codebase-memory。
5. 接入 Cognee。
6. 形成 v0.2.0 记忆与索引基础。

后续工作仍需保持本地优先、Search First、按需读取和用户最新明确指令优先。
