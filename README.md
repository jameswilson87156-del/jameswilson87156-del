# 王震龙 · Zhenlong Wang

**2027 届软件工程本科生｜AI 全栈开发方向（Java 后端 + AI 应用）**

以 Java 后端为基础，实践 Vue 3 / TypeScript 前端交付与 AI 应用集成；关注模型输出约束、业务事实校验、评测和运行证据。

[个人作品集](https://wzl8.top) · [GitHub 项目](https://github.com/jameswilson87156-del)

**求职范围：** 全国各地，接受异地；目前大四无课程安排。

## 精选项目

### CommerceFlow AI Mall

商品、购物车、订单、库存与 AI 客服的全栈电商项目。重点展示订单状态流转、库存回补与重复请求处理，以及 AI 回答如何受业务事实约束。

**技术栈：** Java 17 · Spring Boot 3 · MySQL · Redis · Vue 3 · UniApp · FastAPI

[查看仓库与验证记录](https://github.com/jameswilson87156-del/commerceflow-ai-mall)

<a href="https://github.com/jameswilson87156-del/commerceflow-ai-mall"><img src="https://raw.githubusercontent.com/jameswilson87156-del/commerceflow-ai-mall/main/screenshots/v2/01-operations-overview-real.png" alt="CommerceFlow AI Mall 实际运行的运营总览截图" width="100%"></a>

### Enterprise AI Ticket Copilot

面向工单处理的 AI 应用，覆盖分类、知识检索、引用展示、人工确认、运行追踪与失败降级。评测数据、逐样本结果和已知限制以仓库中的报告为准。

**技术栈：** Java 17 · Spring Boot 3 · Python · FastAPI

[查看仓库与验证记录](https://github.com/jameswilson87156-del/enterprise-ai-ticket-copilot)

<a href="https://github.com/jameswilson87156-del/enterprise-ai-ticket-copilot"><img src="https://raw.githubusercontent.com/jameswilson87156-del/enterprise-ai-ticket-copilot/main/docs/images/ticket-workbench.png" alt="Ticket Copilot 实际运行的工单工作台截图" width="100%"></a>

### 其他工程实践：DevFlow Copilot

围绕 Prompt、Provider 调用、Tool Call、运行 Trace 和证据回放的 AI 工作流项目。项目中的 Agent 表述以应用工作流为边界，具体能力以仓库实现为准。

[查看仓库](https://github.com/jameswilson87156-del/devflow-copilot)

## 评测证据摘录

<details>
<summary>展开查看本地评测范围与限制</summary>

- **Ticket Copilot：** 固定 16 条合成检索样本的迭代结果中，Citation Precision 从 81.11% 提升到 97.78%，失败样本从 6 条降到 1 条；EVAL-016 仍有误召回。该数据集参与过方法调整，不是独立盲测。
- **CommerceFlow：** 本地 MOCK 评测覆盖 44 条常规问题、18 条复合问题和 90 条红队样本；另有 24 项 SKU 同义词定向测试。MOCK 结果不代表真实模型准确率，本轮没有真实模型请求。
- **历史 DeepSeek 批次：** Ticket 普通分类 38/40、Macro-F1 0.9499；CommerceFlow 普通客服场景 22/22（19,324 tokens）。均为历史合成样本批次，不代表当前候选的模型质量，也与离线规则和 MOCK 结果分开统计。

</details>

## 实习经历

**南京玻璃纤维研究设计院有限公司（江宁分公司）· 研发部** · 2026.08–2026.10

参与公司在用企业内网系统的二次开发，围绕材料性能、原材料、微结构性能、工艺和仿真性能五类资源库，参与字段与表关系梳理、数据库结构和初始化脚本、REST API、分页关联查询、ZIP 资料批量导入、PDF/Excel 查看预览及旧页面兼容联调。

**技术栈：** Java 17 · Spring Boot 3 · MyBatis-Plus · MySQL · Swagger/Knife4j

## 技术方向

- **Java 后端：** Java、Spring Boot、MyBatis-Plus、MySQL、Redis、REST API
- **AI 应用：** Python、FastAPI、模型 Provider 接入、检索评测、Prompt、Tool Calling、人工复核
- **全栈交付：** Vue 3、TypeScript、Vite、Next.js、Git、Docker、Linux

> 项目指标只在对应仓库说明数据来源、样本范围和验证方式；合成数据、Mock 与真实模型结果分开记录，不代表生产效果。
