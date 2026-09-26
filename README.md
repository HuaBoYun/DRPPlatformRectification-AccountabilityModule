> 🌐 English | [简体中文](doc/README-zh.md)

# Wenxin Large Model · Finance-Domain Large Language Model

> Empowering AI to directly solve enterprise problems | The entire software layer is open source, free forever

![Model](https://img.shields.io/badge/Model-Wenxin-blue?style=flat-square) ![Domain](https://img.shields.io/badge/Domain-Finance-green?style=flat-square) ![Intelligence](https://img.shields.io/badge/Intelligence-4_Capabilities-orange?style=flat-square) ![Engines](https://img.shields.io/badge/Engines-5-red?style=flat-square)

## Platform Overview

Wenxin Large Model is a finance-domain large language model developed by Huabo Cloud (Beijing) Technology Co., Ltd. in collaboration with the technical team of Harbin Institute of Technology. Focused on the "finance brain", it deeply integrates finance-domain knowledge with reasoning and decision-making capabilities, empowering AI to directly solve enterprise problems.

The platform provides three working modes and five engines; the finance capabilities of Wenxin Large Model form the four intelligence capabilities. The model and the five engines together constitute the Enterprise AI Ontology, from which ten applications covering the entire finance chain grow. Applications are built on AI capabilities and can iterate and adjust quickly with business needs.

**Three Working Modes**

- **Menu-based** — use applications through function menus, ready out of the box
- **Skill-based** — encapsulate large-model capabilities as composable skills, orchestrated per scenario
- **Conversational** — talk to the large model to perform business operations directly; AI solves problems directly

**Four Intelligence Capabilities**

- **AI Office** — the conversational working capability of the large model, turning daily office tasks into natural language
- **AI Consulting** — management-consulting capability; finance expert knowledge is distilled into intelligent Q&A
- **AI Modeling** — dynamic modeling capability; indicators, rules and risk models are built dynamically with the business
- **AI Coding** — application generation capability; dynamic modeling, real-time coding, delivery anytime

The four intelligence capabilities run on top of the Enterprise AI Ontology and act on the enterprise's business objects and rules, forming a value loop from model capability to business execution.

| **AI Office** | **AI Consulting** | **AI Modeling** | **AI Coding** |
|---|---|---|---|
| ![AI Office](images/smart-office-1.png)<br>![AI Office](images/smart-office-2.png) | ![AI Consulting](images/smart-consulting-1.png)<br>![AI Consulting](images/smart-consulting-2.png) | ![AI Modeling](images/smart-modeling-1.png)<br>![AI Modeling](images/smart-modeling-2.png)<br>![AI Modeling](images/smart-modeling-3.png) | ![AI Coding](images/smart-coding-1.png)<br>![AI Coding](images/smart-coding-2.png) |

**Wenxin Agents**

The Wenxin Agent is the running unit that carries the four intelligence capabilities and executes business: on the Agent Platform, model capabilities, knowledge bases, tools and business processes are orchestrated together, applied to the Enterprise AI Ontology and distributed to business modules for use — covering the whole flow from building to using.

- **Build** — create applications on the Agent Platform (conversational or workflow type), visually orchestrate workflow nodes (LLM calls, knowledge retrieval, conditional branches, template conversion, code execution, tool calls, etc.), write prompts and configure model parameters; attach knowledge bases (upload enterprise policies and business documents for retrieval augmentation) and tool plugins, so agents acquire enterprise knowledge and business capabilities
- **Debug & Publish** — validate results through conversation debugging; publish applications upon confirmation and automatically obtain an API key; supports dual-track operation of draft debugging and published running
- **Authorize & Distribute** — in System Settings → Agent Management, distribute and authorize agents to business modules and members, controlling who can use what, and where
- **Use** — business users invoke agents through the AI assistant inside business modules, raising business requests via conversation; the agent understands and executes the corresponding business operations; direct business access via conversation is also supported
- **Audit Trail** — conversation history and running records are retained for review, supporting continuous agent optimization

| ![Wenxin Agent · Debug & Publish](images/agent-2.png) | ![Wenxin Agent · Business Use](images/agent-3.png) |

**Five Engines**

Organization Engine · Role Engine · Process Engine · Form Engine · Rule Engine — the operational foundation that brings the large model into enterprise operation.

**Enterprise AI Ontology**

The Enterprise AI Ontology is the enterprise's digital twin and operating layer: it models the enterprise's organizational structure, business objects, relationships and control rules into a standardized knowledge system. Its foundation consists of three parts — enterprise-specific development templates constrain AI behavior norms, MCP tool integration connects enterprise knowledge and norms, and skill authorization defines capability boundaries and execution approvals. Wenxin Large Model runs on top of the ontology, becoming an AI that understands the enterprise's own structure, norms and business, continuously operating, learning and executing business within the enterprise.

**Platform Architecture**

Wenxin Large Model is structured in four layers from top to bottom: the large-model foundation, the five engines, the Enterprise AI Ontology, and the applications of the four intelligence capabilities. The large-model foundation provides finance-domain understanding, reasoning and decision-making; the five engines — organization, role, process, form and rule — model enterprise operating elements into a standardized knowledge system; together they constitute the Enterprise AI Ontology — the enterprise's digital twin and operating layer, accumulating business objects, relationships and control rules. The four intelligence capabilities run on top of the ontology, growing applications that cover the entire business chain of enterprise supervision and operation.

![Wenxin Large Model Architecture](images/architecture.png)

## Ten Finance Applications

The following applications are all built on the Wenxin Large Model platform. They are the concrete implementations of the four intelligence capabilities in finance business scenarios, covering the entire business chain of enterprise supervision and operation; each application can be used standalone or run as an integrated whole.

| # | Application | One-line Introduction |
|---|---|---|
| 1 | SOE Look-Through | Thirteen look-through supervision dimensions, full-level look-through from group headquarters to end-level enterprises, revealing true operating conditions |
| 2 | Risk Control | Full lifecycle management of risk identification, assessment, monitoring, early warning and disposal; an intelligent risk-control cockpit shows risk posture in real time |
| 3 | Internal Control & Compliance | Internal control matrix management, compliance rule base, compliance checks and process execution monitoring, ensuring operations meet regulatory requirements |
| 4 | Intelligent Contract | Full lifecycle contract management with AI-assisted drafting and review plus legal risk identification, reducing contract performance risk |
| 5 | Financial Sharing | Centralized processing of general ledger, receivables, payables, fixed assets and expense reimbursement, improving financial operations efficiency |
| 6 | Management Accounting | Cost centers, product costing, internal settlement, multi-dimensional cost analysis and control, supporting management decisions |
| 7 | Global Treasury | Cash management, account management, capital planning, investment and financing management, bill management, derivatives management |
| 8 | Intelligent Legal | AI-powered legal document review, compliance checks, case retrieval and legal analysis advice |
| 9 | Agile Audit | Full-process management of audit planning, project implementation, report review, archives, rectification and quality assessment, with AI-assisted tools improving efficiency |
| 10 | Rectification & Accountability | Post-issue rectification tracking, accountability tracing, closed-loop management and effectiveness evaluation |

### Application UI Preview

| Application | UI |
|---|---|
| **1. SOE Look-Through** | ![1. SOE Look-Through](images/app-01-guochuantou-1.png) ![1. SOE Look-Through](images/app-01-guochuantou-2.png) |
| **2. Risk Control** | ![2. Risk Control](images/app-02-fengxianguankong-1.png) ![2. Risk Control](images/app-02-fengxianguankong-2.png) |
| **3. Internal Control & Compliance** | ![3. Internal Control & Compliance](images/app-03-neikonghegui-1.png) ![3. Internal Control & Compliance](images/app-03-neikonghegui-2.png) |
| **4. Intelligent Contract** | ![4. Intelligent Contract](images/app-04-zhihuihetong-1.png) ![4. Intelligent Contract](images/app-04-zhihuihetong-2.png) |
| **5. Financial Sharing** | ![5. Financial Sharing](images/app-05-caiwugongxiang-1.png) ![5. Financial Sharing](images/app-05-caiwugongxiang-2.png) |
| **6. Management Accounting** | ![6. Management Accounting](images/app-06-guanlikuaiji-1.png) ![6. Management Accounting](images/app-06-guanlikuaiji-2.png) |
| **7. Global Treasury** | ![7. Global Treasury](images/app-07-quanqiusiku-1.png) ![7. Global Treasury](images/app-07-quanqiusiku-2.png) |
| **8. Intelligent Legal** | ![8. Intelligent Legal](images/app-08-zhihuifawu-1.png) ![8. Intelligent Legal](images/app-08-zhihuifawu-2.png) |
| **9. Agile Audit** | ![9. Agile Audit](images/app-09-minjieshenji-1.png) ![9. Agile Audit](images/app-09-minjieshenji-2.png) |
| **10. Rectification & Accountability** | ![10. Rectification & Accountability](images/app-10-zhenggaizhuijiu-1.png) ![10. Rectification & Accountability](images/app-10-zhenggaizhuijiu-2.png) |

## Open-Source Statement

The software layer of this project (all business modules) is open source and free forever: both individuals and enterprises may use it free of charge and are allowed to modify it; commercial use is prohibited — no enterprise, institution or individual may sell this software or package it as a paid product/service.

- **Version system**: Government Supervision Edition / Central Enterprise Edition / State-Owned Enterprise Edition / Listed Company Edition / International Enterprise Edition / University Training Edition / Industry Custom Edition / Open-Source Free Edition
- **Database adaptation**: Fully adapted to Xinchuang (domestic IT innovation) environments (DM / Oracle / MySQL), meeting the localization requirements of central and state-owned enterprises
- **License**: Free to use · Commercial use prohibited

| Rights & Obligations | Description |
|---|---|
| ✓ Personal use | Allowed — for personal study, research and use, completely free |
| ✓ Enterprise use | Allowed — internal installation and deployment for your own business operations, free forever |
| ✓ Modification | Allowed — may be modified and re-developed for your own business needs (modified versions are likewise prohibited from commercial use) |
| × Commercial use (prohibited) | Must not sell, resell or distribute for a fee this software (including modified and derivative versions), directly or indirectly |
| × Commercial use (prohibited) | Must not package this software as a paid product or paid service (including SaaS mode) for external offering |
| ! Commercial licensing | Resale, integration into paid products, or providing paid services requires a separate written commercial license agreement |
| ! Copyright notice | The original copyright statement must be retained when using and redistributing |
| × Warranty | Not provided — the software is provided "as is", with no express or implied warranty |

Applicable scenarios: personal study and research; free internal enterprise use. Business cooperation (resale, integration, paid services) requires commercial authorization.

## Contact Us

- Website: https://huabocn.com
- Email: 18600042653@163.com

Wenxin Large Model · Master AI, Ask the Heart

---

# Rectification & Accountability Powered by Wenxin Large Model

Rectification & Accountability consolidates issues found by audit and internal control, forming a closed loop through notification, tracking, implementation, acceptance and reporting, with accountability pursued for ineffective rectification — the last mile of the supervision system.

![Rectification & Accountability built with Wenxin Large Model](images/10-zhenggaizhuijiu.png)

## Feature Composition

### Rectification Home

Home-page KPIs present the status distribution of total issues, pending, in-rectification and closed items, plus issue closure rate, accountability case count and unresolved issue count; a rectification closed-loop topology presents the full chain — issue aggregation, rectification notices, rectification plans, rectification implementation, rectification tracking, acceptance & closure, ledger archiving and accountability.

### Issue Aggregation

Audit issue summaries and internal-control issue summaries are merged into a rectification list — issue records carry source, category and responsible unit; issue counts and distribution are searchable and exportable.

### Rectification Notices

Notices are issued by source (audit, internal control, etc.), specifying rectification items, responsible units, responsible persons and deadlines, matched one-to-one with the issue list, with issuance audit-trailed.

### Rectification Ledger & Tracking

The rectification ledger records item by item, with statuses flowing through pending → in rectification → awaiting acceptance → accepted → closed, each change audited; rectification progress is recorded as completion percentage; acceptance gives pass/fail opinions — only passing items can be closed; rectification queries search by status, unit and time.

### Subsequent Rectification & Rectification Reports

Near-deadline and overdue tasks are auto-alerted; unclosed issues enter subsequent rectification under continuous supervision; the rectification report summarizes this period's rectification and remaining issues; implementation ledgers and past rectification lists preserve year-over-year history.

### Accountability

Issues with ineffective rectification initiate accountability acceptance and violation verification — from acceptance, verification, retrospective checking to review reporting, fully audit-trailed: no issue left unresolved, no responsibility unpursued, with grounds and process traceable.

### Supervision Dashboard

Issue closure rate and rectification completion rate quantify effectiveness; accountability cases and unresolved issues alert in red; rectification rate statistics and issue rectification list summaries aggregate by source and category — providing data support for supervision appraisal and responsibility determination.

## Business Process

Audit and internal-control issues are aggregated into a rectification list — rectification notices are issued to start cases — responsible units formulate plans and organize implementation — rectification tracking records progress item by item — acceptance and closure (failures are rejected back) — unclosed items enter subsequent rectification supervision — rectification reports and ledgers are archived — ineffective rectification initiates accountability acceptance, verification and pursuit — indicators such as closure rate quantify effectiveness throughout.

## Business Value

Rectification & Accountability opens up the last mile of supervision implementation: issues run a fully closed process from aggregation, notification, tracking and acceptance to reporting; subsequent rectification is continuously supervised, responsibility is traced to individuals, and closure rates quantify effectiveness — issues found by audit and internal control are truly rectified and accounted for.

## Repository Contents

| Service | Port | Description |
|---|---|---|
| springboot-hbyunAudit | 8065 | Rectification & accountability service |
| doc/ | — | [Backend Service Startup Guide](doc/后端服务启动说明.md): build configuration, database preparation, sanitization reference, startup steps and troubleshooting |

Issue sources integrate with the Agile Audit module (Wenxin Large Model Agile Audit Module) and the Internal Control & Compliance module (Wenxin Large Model Internal Control & Compliance Module); the platform depends on the registry, gateway, system module and AI large-model services provided by the base module repository.

## Tech Stack & Startup

- Tech stack: Spring Boot / Spring Cloud (Eureka + Gateway), JDK 1.8, Maven 3.6+, DM/MySQL database, Redis.
- Startup order: first start the registry and gateway from the base module repository, then start this module: `mvn spring-boot:run`.
- Before the first build, install the offline jars (DM driver etc., see the `repository` directory of the base module repository); see the [Backend Service Startup Guide](doc/后端服务启动说明.md) for details.
- The code is sanitized: database passwords, secrets and IPs are placeholders; replace them with real environment configuration (application-dev.yml) before startup.
