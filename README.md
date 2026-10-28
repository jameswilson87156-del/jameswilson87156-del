# 王震龙 · Zhenlong Wang

**测试开发实习方向｜AI Agent 评测与系统自动化｜2027 届软件工程本科**

我希望做测试开发：把业务规则拆成可执行用例，让 API、浏览器和数据状态可以重复验证，并把失败原因与报告留成可复查证据。Java / Spring Boot 的开发背景让我能读懂被测服务与状态流转；当前项目实践重点是 Python / pytest、API 与 UI 自动化、Agent 行为评测和质量门禁。

**求职方向：** 测试开发实习生、AI 测试 / Agent 评测实习生

## 主项目

### PromptOps Studio · AI Agent 评测与回归

固定测试集驱动确定性 Mock Agent，使用规则断言检查输出格式、业务约束、工具选择与参数；按运行展示逐条结果、Trace 和失败原因，并支持版本回归分析。

- 技术：Java 17、Spring Boot、Python、pytest、Vue 3、TypeScript、Playwright
- 评测边界：当前仓库展示的是 Local Demo、Mock Output 与 Rule-based Eval；不把 Mock 结果说成真实模型准确率。
- [项目仓库与 README](https://github.com/jameswilson87156-del/ai-agent-eval-promptops)

### Gitea Quality Lab · 开源系统质量自动化

在隔离 Docker 环境中对 Gitea 28.2.0 做黑盒质量验证，覆盖 REST API、身份与权限、浏览器工作流和 SQLite 重启持久化；为每次运行生成 JSON、JUnit、HTML 与浏览器证据，并校验 JSON / JUnit 汇总一致。

- 技术：Python 3.12、pytest、HTTPX、Playwright、Docker Compose、GitHub Actions
- GitHub Actions run **40710451708**：24 个框架单元测试 + 16 个 Gitea 集成用例通过；目标为 CI 中的隔离 Gitea 实例。
- [查看项目分支](https://github.com/jameswilson87156-del/gitea-quality-lab/tree/feat/gitea-quality-lab) · [查看 CI 记录](https://github.com/jameswilson87156-del/gitea-quality-lab/actions/runs/40710451708) · [查看验收证据](https://github.com/jameswilson87156-del/gitea-quality-lab/blob/feat/gitea-quality-lab/reports/evidence.md)

## 测试开发实践

- **用例设计：** 正常、边界、非法输入、权限、幂等、状态机与持久化场景。
- **自动化：** Java / JUnit、Python / pytest、HTTPX、Playwright / Chromium。
- **质量与性能：** Docker Compose、GitHub Actions、k6、Prometheus、Alertmanager。
- **问题定位：** 固定输入、唯一 Run ID、逐条断言、报告一致性检查与失败证据。

## 目前的边界

项目结果来自本地合成服务、隔离开源软件实例或 CI 临时环境，不代表企业生产测试经验、生产流量或大规模生产容量。PromptOps 当前使用 Mock Agent；尚未用真实模型建立质量基线。MySQL / Redis 的测试矩阵、真实团队缺陷闭环和经授权的生产系统验证仍需继续补齐。

## 工程背景

Java、Spring Boot、MyBatis、MySQL、Vue 3 与 TypeScript 是我理解和构造被测系统的基础。实习经历将按我实际承担的职责、问题案例和可核实结果补充；不把独立项目练习改写成任职测试经历。

[个人作品集](https://wzl-ai-engineering-portfolio.tkvbzkyvsv.chatgpt.site) · [GitHub 项目列表](https://github.com/jameswilson87156-del)
