<div align="center">

## Hi, I'm Cjantwhy 👋

**Backend Engineer · 后端开发工程师**

I build integrations that keep your tools in sync: spreadsheets, forms, issue trackers, chat, and the APIs your business already runs on.

[English](#english) · [中文](#chinese) · [📫 cjantwhy@gmail.com](mailto:cjantwhy@gmail.com)

</div>

---

<a id="english"></a>

## 🇬🇧 English

### ⭐ Featured Project: [issue-sync](https://github.com/Cjantwhy/issue-sync)

**Two-way sync between Google Sheets and Jira Cloud, with AI triage, Slack notifications and a dashboard.**

People report problems where they already work, in a shared Google Sheet or a Google Form. issue-sync turns each row into a Jira ticket, uses an LLM to set the category, urgency and team, assigns it, and notifies the assignee in Slack. Status changes and comments in Jira flow back to the sheet.

- **Reliable by design**: one ticket per row even under failures and retries, loop-free two-way sync, and a reconciliation job every 15 minutes that repairs missed webhooks
- **AI suggests, rules decide, people override**: all three are recorded, and the dashboard shows how often the model is right
- **Production-ready**: Docker Compose deployment, HMAC-verified webhooks, CI with a full test suite against PostgreSQL

`Python` · `FastAPI` · `PostgreSQL` · `Redis` · `HTMX` · `Docker` · `Jira REST API` · `Google Sheets API` · `Slack API` · `OpenAI-compatible LLMs`

> This project grew out of my day job. I built and maintained the same kind of two-way issue sync in production, between an internal platform, ZenTao (a Jira-style issue tracker) and 70+ shared online spreadsheets used by external partners.

### 🛠 What I Can Do for You

- **Workflow integrations**: connect Google Sheets / Forms, Jira, Slack and other SaaS tools, so data moves on its own instead of being copied by hand
- **Two-way sync done right**: clear field ownership, idempotent writes, loop prevention, and reconciliation for the cases webhooks miss
- **AI-assisted triage**: LLM classification with structured output, rule-based overrides, and accuracy evaluation
- **Third-party API integration**: fetch, normalize and store data from external platforms
- **Search**: fuzzy search and faceted filtering with Elasticsearch
- **Python automation**: data processing, data-fix scripts and price monitoring

### 💼 Experience

**Internal R&D Platform · Backend Developer** (Java / PostgreSQL)
- Built two-way sync between customer issue reports and ZenTao: issues reported from customer sites become tickets automatically, and progress syncs back.
- Integrated 70+ external spreadsheets (Feishu Docs / Tencent Docs, the Chinese equivalents of Google Sheets), so external partners could report and track issues in tools they already used.

**E-commerce Platform · Backend Developer** (PHP / MySQL)
- Integrated the Steam inventory API: fetched user inventories, normalized them into the platform schema and stored them for trading and listings.
- Owned the Elasticsearch product search, with fuzzy matching and aggregation-based filters.
- Wrote Python tooling for pre-release data processing and price comparison.

### 🧰 Tech Stack

`Python` · `Java` · `PHP` · `FastAPI` · `PostgreSQL` · `MySQL` · `Redis` · `Elasticsearch` · `Docker` · `REST APIs` · `Webhooks` · `LLM APIs`

### 📫 Contact

Have a workflow that still depends on copy-paste between tools? Email me at [cjantwhy@gmail.com](mailto:cjantwhy@gmail.com).

---

<a id="chinese"></a>

## 🇨🇳 中文

我的工作是把分散在不同平台的数据**接进来、整理好、同步出去**，变成业务能直接用的功能。

### 🛠 我能提供的服务

- **第三方平台 / API 对接**：接入外部平台数据，完成解析、格式标准化和入库
- **搜索功能开发**：基于 Elasticsearch 实现模糊搜索、聚合筛选和统计
- **系统集成与双向同步**：打通内部平台、项目管理工具（禅道、Jira）和在线协作文档（飞书文档、腾讯文档、Google Sheets）
- **Python 自动化**：批量数据处理、数据修复脚本、商品比价工具

### 💼 工作经历

#### 企业内部研发管理平台 · 后端开发（Java / PostgreSQL）

- **现场问题反馈与禅道同步**：软件部署到客户现场后，使用中遇到的问题会在平台上提交。我负责把这些问题自动同步到禅道，并把处理进度回传平台，实现双向同步。
- **外部协作打通**：对接 **70 余份**飞书文档、腾讯文档外部表单，让外部合作方能在熟悉的在线文档里反馈和跟进问题，数据自动和内部系统保持一致。

#### 电商平台 · 后端开发（PHP / MySQL）

- **Steam 库存数据对接**：调用 Steam 库存接口获取用户库存，负责数据解析、转换成平台统一的数据格式，再写入 MySQL，为交易和展示提供基础数据。
- **商品搜索与展示**：负责商品展示页的 Elasticsearch 搜索模块，用查询 DSL 实现模糊搜索，并通过聚合查询支持分类筛选和统计。
- **数据处理工具**：用 Python 编写脚本，调用内部预留接口，在发版前完成数据处理和修复；开发商品比价脚本，辅助定价决策。

### ⭐ 开源项目

- **[issue-sync](https://github.com/Cjantwhy/issue-sync)**：Google Sheets 与 Jira 双向同步，带 AI 自动分类分派、Slack 通知和看板。思路来自上面的禅道同步项目，这次换成了海外常用的工具链。

### 🧰 技术栈

`Python` · `Java` · `PHP` · `FastAPI` · `PostgreSQL` · `MySQL` · `Redis` · `Elasticsearch` · `Docker` · `禅道` · `飞书文档` · `腾讯文档`

### 📫 联系方式

- 邮箱：[cjantwhy@gmail.com](mailto:cjantwhy@gmail.com)
