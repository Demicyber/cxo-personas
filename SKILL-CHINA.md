---
name: cxo-personas-china
description: >
  China-Market CXO Persona Library for sales teams targeting Chinese enterprises. Provides 19
  C-suite and senior executive persona profiles specific to the China business environment —
  including 3 China-unique roles (出海VP, 政府关系VP, 事业群总裁). Built on research across
  12 China/HK companies. Powers persona-driven meeting preparation for Chinese executive engagement.
  Triggers on: "中国高管画像", "China persona", "中国市场", "出海", "信创", "国企",
  "Chinese executive", "China CXO", "中国CXO", "如何跟中国CFO沟通", "事业群总裁".
---

# CXO Personas Library — China Market (中国市场高管画像)

## 1. Purpose

This skill provides **audience intelligence for the China market** — helping sales teams prepare for meetings with Chinese enterprise executives. It contains 19 persona profiles reflecting how Chinese C-suite and VP-level executives actually think, communicate, and make purchasing decisions.

**This is NOT a translation of the Global persona set.** China personas reflect fundamentally different:
- Organizational structures (事业群/BU制, 赛马机制, 人单合一)
- Regulatory environments (三法合规, 信创, 等保, 算法备案)
- Buying behaviors (政府关系 as gatekeeper, BU Head as real buyer, 招投标 process)
- Communication norms (WeChat-first, hierarchical, relationship-driven)

---

## 2. Core Rules

### Rule 1: China Context Required
These personas apply ONLY to China-market engagements. For global/Western executives, use the standard `cxo-personas` skill. If unsure whether the engagement is China-market, check: Is the company HQ'd in China/HK? Is the executive based in China? Is the deal for China operations?

### Rule 2: Chinese Title Mapping
Chinese executives rarely use English C-suite titles. Use the Title Mapping Guide in [references-china/INDEX.md](references-china/INDEX.md) to match Chinese job titles (e.g., 信息化负责人 → CIO, 事业群总裁 → BU Head).

### Rule 3: Load Full Profile
The INDEX provides summaries only. Always load the **full persona file** for complete guidance. Each persona is 600-900 lines with archetypes, priorities, pain points, objection handling, buying dynamics, and communication style.

### Rule 4: Check for China-Unique Roles
Three roles exist ONLY in the China set:
- **出海VP (VP International)** — for any 出海/globalization discussion
- **政府关系VP (VP Gov Relations)** — for any government/policy/subsidy topic
- **事业群总裁 (BU Head)** — for BU-level enterprise deals (often the REAL buyer)

---

## 3. How to Use

### Step 1: Identify the Persona
Use the **Title Mapping Guide** or **Topic Routing Guide** in [references-china/INDEX.md](references-china/INDEX.md) to match.

### Step 2: Load the Persona
Read the full persona file from `references-china/`.

### Step 3: Apply
Pull relevant insights for:
- Discovery questions and meeting agenda
- Objection handling and negotiation approach
- Communication style and language preferences
- Buying dynamics and decision-making process
- Pain points and value proposition alignment

### Step 4: Multi-Persona Deals
Chinese enterprise deals often involve:
- BU Head (budget owner) + CIO/CTO (technical gate) + 采购 (procurement process)
- VP Gov Relations as shadow stakeholder for government-adjacent deals
- CEO involvement at lower thresholds than Western deals (¥5M+)

Reference the **Cross-Persona Dynamics** section in INDEX.md for common buying committees.

---

## 4. Persona Directory

### Strategic Leadership
- [CEO/Founder](references-china/CEO-Founder.md) — 创始人/CEO, enterprise strategy, 出海决策

### Finance & Operations
- [CFO](references-china/CFO.md) — 财务VP, 降本增效, IPO readiness
- [COO](references-china/COO.md) — 运营VP, 智能制造, supply chain
- [VP Supply Chain](references-china/VP-Supply-Chain.md) — 供应链VP, 小单快反, 国产替代
- [VP Manufacturing](references-china/VP-Manufacturing.md) — 制造VP, 灯塔工厂, IT/OT融合

### Technology & Digital
- [CTO](references-china/CTO.md) — 技术VP, 大模型, 出海架构
- [CIO](references-china/CIO.md) — IT总监, 信创, ERP, 等保
- [VP AI](references-china/VP-AI.md) — AI负责人, 大模型战略, AI落地
- [CDO (Data)](references-china/CDO-Data.md) — 数据VP, 数据要素市场化, 数据资产入表

### Revenue & Growth
- [CMO](references-china/CMO.md) — 品牌VP, 私域流量, 品效合一
- [CPO (Product)](references-china/CPO-Product.md) — 产品VP, 赛马机制, AB测试
- [BU Head](references-china/BU-Head.md) 🇨🇳 — 事业群总裁, 内部CEO, P&L独立

### International 🇨🇳
- [VP International](references-china/VP-International.md) 🇨🇳 — 出海VP, geopolitical risk, 本地化

### People & Culture
- [CHRO](references-china/CHRO.md) — HRVP, 组织活力, AI人才战, 35岁危机

### Risk, Legal & Compliance
- [CISO](references-china/CISO.md) — 安全负责人, 等保2.0, 护网, 信创安全
- [CCO](references-china/CCO.md) — 合规总监, 三法合规, 算法备案, 反垄断
- [General Counsel](references-china/General-Counsel.md) — 总法律顾问, IP, 出口管制
- [CRO (Risk)](references-china/CRO-Risk.md) — 风控总监, 金融监管, 地缘政治风险

### Government & Policy 🇨🇳
- [VP Gov Relations](references-china/VP-Government-Relations.md) 🇨🇳 — 政府关系VP, 政策申报, 补贴

---

## 5. Key Differences from Global Set

| Dimension | Global | China |
|---|---|---|
| **Org structure** | Functional hierarchy | 事业群/BU制 + 赛马机制 |
| **Real buyer** | C-suite functional owner | Often BU Head (P&L authority) |
| **IT decisions** | Best-of-breed | 信创 mandate constrains choice |
| **Regulatory** | Industry-specific | Universal三法 + sector-specific |
| **Communication** | Email/Slack | WeChat/企业微信-first |
| **Procurement** | Vendor evaluation | 招投标 (bidding) for large deals |
| **Government role** | Minimal | Active partner (subsidies, policy) |
| **Unique roles** | — | 出海VP, 政府关系VP, 事业群总裁 |

---

## 6. Research Foundation

Built on deep research into 12 China/HK companies:

| Company | Sector | Key Contribution |
|---|---|---|
| Anker (安克) | Consumer Electronics | 出海品牌 DTC model |
| 海康威视 | IoT/Security | Entity List adaptation, 信创 |
| 海尔 | Smart Home/Industrial | 人单合一, COSMOPlat, 灯塔工厂 |
| 理想汽车 | NEV | Founder-driven, 智能制造 |
| Shein | Fast Fashion | 小单快反, born-global |
| ByteDance | Platform/AI | 大模型, 飞书, 全球化 |
| 禾观 | AI SaaS | Early-stage, PMF |
| Cathay Pacific | Aviation | Legacy modernization, recovery |
| WeBull | Fintech | Multi-jurisdiction compliance |
| 港交所 | Financial Infra | Regulator + commercial dual role |
| 猎豹移动 | Mobile Internet | 出海教训 (cautionary tale) |
| 腾讯游戏 | Gaming | 工作室群, 版号, 赛马 |

---

## 7. Pitfalls

1. **Do NOT assume Western buying process** — Chinese enterprises use 招投标, have stronger hierarchy, and involve government relations
2. **Do NOT use global personas for China executives** — even same title (e.g., CFO) has fundamentally different priorities
3. **BU Head is often MORE powerful than functional C-suite** — if selling to a large Chinese tech company, find the BU Head first
4. **VP Gov Relations is invisible but critical** — for any deal involving 国企 or government contracts, this persona gates access
5. **信创 is not optional** — for 国企 and many 民企, domestic tech substitution is mandated, not a preference
