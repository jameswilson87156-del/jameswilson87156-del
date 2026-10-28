# 王震龙 · Zhenlong Wang

**测试开发实习方向｜系统质量自动化与 AI Agent 评测｜2027 届软件工程本科**

我希望从事测试开发：把业务规则拆成可执行用例，让 API、浏览器流程和数据状态可以重复验证，并通过运行记录、Trace 与报告定位失败。Java / Spring Boot 背景帮助我理解被测服务与状态流转；项目重点是 Python / pytest、API 与 UI 自动化、评测工具和 CI 质量门禁。

**求职方向：** 测试开发实习生、AI 测试 / Agent 评测实习生

**个人作品集：** [测试开发作品集](https://ai-agent-portfolio-hub.vercel.app/)

## 主项目

### Gitea Quality Lab · 开源系统质量自动化

在隔离 Docker 环境中对 Gitea 28.2.0 做黑盒质量验证，覆盖 REST API、身份与权限、浏览器工作流和 SQLite 重启持久化；每次运行生成 JSON、JUnit、HTML 与浏览器证据，并校验 JSON / JUnit 汇总一致。

- 技术：Python 3.12、pytest、HTTPX、Playwright、Docker Compose、GitHub Actions
- GitHub Actions run [40710451708](https://github.com/jameswilson87156-del/gitea-quality-lab/actions/runs/40710451708)：24 个测试框架单元测试 + 16 个 Gitea 集成用例通过；目标为隔离的 CI Gitea 实例。
- [项目分支](https://github.com/jameswilson87156-del/gitea-quality-lab/tree/feat/gitea-quality-lab) · [验收证据](https://github.com/jameswilson87156-del/gitea-quality-lab/blob/feat/gitea-quality-lab/reports/evidence.md)

### PromptOps Studio · AI Agent 评测与回归

使用 26 条固定合成用例驱动确定性 Mock Agent，以规则检查输出格式、业务约束、工具选择与参数；逐条保存执行结果、Trace 和失败原因，并提供 JSON 报告与同数据集运行比较。

- 技术：Java 17、Spring Boot、Python、pytest、Vue 3、TypeScript、Playwright
- GitHub Actions run [40724124012](https://github.com/jameswilson87156-del/ai-agent-eval-promptops/actions/runs/40724124012)：Maven 36 项、Python API / 工具 26 项、浏览器端到端和 8 次稳定性采样通过。
- 每轮 26 条用例中保留 2 条确定性 Agent 行为失败样本；用例执行成功与 Agent 行为通过分开统计。当前是 Mock / 规则评测，不代表真实模型准确率。
- [功能分支与 README](https://github.com/jameswilson87156-del/ai-agent-eval-promptops/tree/feat/agent-evaluation-platform) · [CI 证据](https://github.com/jameswilson87156-del/ai-agent-eval-promptops/actions/runs/40724124012)

## 测试开发实践

- **用例设计：** 正常、边界、非法输入、权限、幂等、状态机与持久化。
- **自动化：** Java / JUnit、Python / pytest、HTTPX、Playwright / Chromium。
- **质量与性能：** Docker Compose、GitHub Actions、k6、Prometheus、Alertmanager。
- **问题定位：** 固定输入、唯一 Run ID、逐条断言、报告一致性检查和可复现失败。

## 项目边界

运行结果来自本地合成 API、隔离开源软件实例或 CI 临时环境，不代表企业生产测试经验、生产流量或大规模生产容量。PromptOps 使用 Mock Agent，尚未建立真实模型质量基线。MySQL / Redis 测试矩阵、团队缺陷闭环和经授权的生产验证仍需继续补足。

## 工程背景

Java、Spring Boot、MyBatis、MySQL、Vue 3 与 TypeScript 是理解和构造被测系统的基础。真实实习经历将按本人确认的职责、缺陷案例和可核验结果补充；独立项目不改写成任职经历。

[GitHub 项目列表](https://github.com/jameswilson87156-del)
