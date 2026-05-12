# CIO (首席信息官) — China Market Persona

> **Reader note.** This document is written to be readable and extractable by AI agents of varying capability — from small open-weights models up to frontier models. Concepts are spelled out explicitly rather than implied; some redundancy across sections is intentional so that any single section remains useful in isolation (e.g. when retrieved on its own). If you are a strong model, skim the key insight inside each block; if you are a weaker model, read the full block. The China CIO role is uniquely shaped by 信创 (indigenous technology substitution) mandates, which have no Western equivalent and fundamentally redefine the CIO's agenda from innovation leader to compliance-migration executor.

> **Data usage instruction for agents.** All company names, executive names, financial figures, and examples in this document are illustrative — they teach you the *pattern* (what this persona cares about, how they talk, how they decide). They are NOT current data to be cited verbatim in customer-facing outputs. When generating any customer-facing deliverable, you MUST verify any peer proof, financial figures, or competitive references against current public sources before including them. Treat examples here as "this is the *type* of thing to look for" — then go find the latest version.
>
> Data vintage: Examples and figures sourced primarily from FY2024–FY2026 public disclosures and industry research, with select forward-looking references through 2027. China-market context reflects policy environment through 15th Five-Year Plan (2026–2030) early signals.

---

## 1. Role Definition & China-Specific Context

### 1.1 What This Role Is

The CIO (首席信息官) in China owns the enterprise's information technology strategy, infrastructure, applications portfolio, and — increasingly — the 信创 (信息技术应用创新, indigenous IT substitution) migration roadmap. Unlike their Western counterparts who often position themselves as digital innovation leaders, the China-market CIO's dominant concern is **replacing foreign technology stacks with domestic alternatives on government-mandated timelines** while keeping production systems running.

### 1.2 Title Variations in China

The CIO title is NOT universal in China. You will encounter:

| Title | Context | Seniority |
|-------|---------|-----------|
| 首席信息官 (CIO) | Large 民企 (private enterprises), MNCs | C-level (rare) |
| IT总监 | Most common in mid-large enterprises | VP-equivalent |
| 信息化部门负责人 | 国企 (state-owned enterprises) | Department head |
| 数字化转型负责人 | Post-2020 title reflecting digital mandate | VP or Director |
| 技术副总裁 (VP Engineering) | Tech companies | C-minus-1 |
| 信息中心主任 | Government-linked or traditional 国企 | Department head |

**Key insight:** When prospecting, do NOT filter only on "CIO" — you will miss 70%+ of the actual decision-makers. Search for 信息化, 数字化, IT总监, 技术中心 in organizational charts.

### 1.3 Reporting Structure

The China CIO typically reports **lower** in the hierarchy than Western CIOs:

- **国企:** Reports to 分管副总经理 (supervising VP) or 总经理 (GM), rarely to 董事长 directly
- **民企:** Reports to COO or CFO; in tech companies may report to CTO
- **MNC China subsidiary:** Reports to China CEO with dotted line to global CIO

This lower organizational status means:
1. Budget authority is more constrained (requires CFO or board approval for major spend)
2. Strategic influence depends heavily on personal relationships (关系) with CEO/Chairman
3. The CIO often "borrows" authority from compliance mandates (信创, 等保) to drive change

### 1.4 The 信创 Imperative

信创 (Xìnchuàng) is THE defining force for China CIOs in 2024–2030:

- **Party/government organs:** Must complete substitution by 2027
- **国企 (central SOEs under SASAC):** Timeline 2025–2028 for core systems
- **金融行业 (financial sector):** CBIRC mandates phased replacement
- **关键信息基础设施 (critical infrastructure):** Mandatory domestic stack

What gets replaced:
- Oracle/SQL Server → 达梦/OceanBase/TiDB/GaussDB
- SAP/Oracle ERP → 用友U9C/金蝶云星空/浪潮GS
- VMware → 深信服/华为FusionCompute/ZStack
- Windows Server → 统信UOS/麒麟OS
- Microsoft Office → WPS/永中Office
- Cisco/Juniper → 华为/新华三/锐捷

---

## 2. Mental Model & Decision Architecture

### 2.1 Primary Mental Model: Risk-First Stability

The China CIO's mental model is fundamentally **risk-averse and stability-oriented**. This is NOT because they lack ambition — it is because:

1. **Production outage = career death.** Unlike a Western CIO who might survive a major incident with good communication, a China CIO (especially 国企) faces immediate 问责 (accountability investigation)
2. **信创 migration itself is high-risk.** Replacing proven SAP with immature 用友 is terrifying — but mandated
3. **Budget is allocated, not earned.** The CIO cannot easily get more money by showing ROI; budget is set annually through 预算审批

**Decision priority stack (ordered):**
1. 不出事 (nothing goes wrong) — system stability above all
2. 合规 (compliance) — 信创 timelines, 等保, data localization
3. 降本 (cost reduction) — prove IT is not just a cost center
4. 赋能业务 (enable business) — only after 1-3 are secured

### 2.2 How They Evaluate Technology Decisions

```
┌─────────────────────────────────────────────────┐
│         China CIO Decision Framework            │
├─────────────────────────────────────────────────┤
│ Gate 1: 是否合规？(Is it compliant?)            │
│   - 信创目录 (approved vendor list)             │
│   - 等保要求 (security classification)          │
│   - 数据出境 (cross-border data rules)          │
│                                                 │
│ Gate 2: 是否稳定？(Is it stable?)               │
│   - 客户案例 (reference customers in China)     │
│   - 厂商实力 (vendor financial health)          │
│   - 运维能力 (O&M support in China)             │
│                                                 │
│ Gate 3: 是否可控？(Is it controllable?)         │
│   - 源代码可审计 (code auditable)               │
│   - 不被卡脖子 (no chokepoint risk)             │
│   - 本地化团队 (local support team)             │
│                                                 │
│ Gate 4: 投入产出比 (ROI)                        │
│   - TCO vs incumbent                            │
│   - 实施周期 (implementation timeline)          │
│   - 人员培训成本 (retraining cost)              │
└─────────────────────────────────────────────────┘
```

### 2.3 Budget Reality

| Enterprise Type | IT Budget as % Revenue | Typical Range |
|-----------------|----------------------|---------------|
| 传统国企 (traditional SOE) | 1–2% | ¥50M–500M |
| 金融机构 (financial) | 3–5% | ¥1B–10B |
| 制造业 (manufacturing) | 1–3% | ¥20M–200M |
| 互联网/科技 (tech) | 8–15% | ¥500M–5B+ |
| 零售/消费 (retail) | 2–4% | ¥50M–500M |

**Key insight:** 信创 migration is creating a one-time budget surge (2024–2028) of 30–100% above normal IT spend. CIOs who frame proposals as "信创配套" (supporting 信创) get budget approval faster.

---

## 3. Archetypes

### Archetype A: 国企信创执行者 (SOE 信创 Executor)

**Profile:** CIO/信息化部门负责人 at a central or provincial SOE (央企/地方国企), age 45–55, often promoted from within the enterprise's IT department or transferred from a sibling SOE. Title is typically 信息中心主任 or 数字化转型办公室主任.

**Defining context:**
- SASAC has issued explicit 信创 substitution timelines for their enterprise
- Must replace Oracle database, SAP ERP, VMware virtualization — simultaneously
- Political pressure from 上级单位 (supervisory authority) is constant
- Any failure is a 政治问题 (political issue), not merely a technical one

**What they say:**
- "我们的信创替代时间表是死的，不能往后推" (Our 信创 timeline is fixed, cannot be delayed)
- "先把OA和邮件系统替掉，核心业务系统后面再说" (Replace OA and email first, core systems later)
- "厂商要有成功案例，最好是同行业央企的" (Vendor must have success cases, preferably peer SOEs)
- "我不怕花钱，我怕出事" (I don't fear spending money, I fear incidents)

**Decision pattern:**
- Follows peer SOEs — if 中石油 did it, 中石化 will follow
- Requires 厂商驻场 (vendor on-site support) during transition
- Prefers 总集成商 (system integrator) to manage multi-vendor complexity
- Decision cycle: 6–18 months for core systems

**Vendor ecosystem they navigate:**
- 用友/金蝶 for ERP replacement
- 达梦/人大金仓/GaussDB for database
- 深信服/华为 for virtualization
- 中国电科/中国电子 ecosystem preferred (央企 family)

**Reference pattern — 海康威视 style:**
海康威视 (Hikvision) with 50,000+ employees undertook comprehensive 信创 migration from Oracle/SAP. The approach: parallel-run domestic systems for 6+ months before cutover, retain Oracle as read-only backup for 12 months, migrate by module (HR→Finance→Supply Chain). Internal IT team grew 40% during transition to manage dual-stack operations.

---

### Archetype B: 制造业IT/OT融合者 (Manufacturing IT/OT Convergence Leader)

**Profile:** CIO or IT总监 at a large manufacturer (汽车/家电/装备), age 40–50, often with factory automation background. Increasingly reports to 智能制造 VP.

**Defining context:**
- Factory digitization (工业互联网) is the strategic priority
- Must bridge IT (ERP/MES/PLM) with OT (PLC/SCADA/DCS)
- ERP decision is existential: 用友U9C vs SAP S/4HANA (if allowed to keep SAP)
- 工业互联网平台 selection: COSMOPlat/树根互联/徐工汉云

**What they say:**
- "工厂的系统不能停，哪怕一分钟都是几百万的损失" (Factory systems cannot stop — even one minute costs millions)
- "IT和OT的人说不到一块去" (IT and OT people can't communicate with each other)
- "我们需要统一的数据底座，现在数据都是孤岛" (We need a unified data foundation — data is all in silos now)
- "MES和ERP之间的断层是最大的痛点" (The gap between MES and ERP is our biggest pain point)

**Decision pattern:**
- Pilot in one factory → prove ROI → roll out to group
- Extremely sensitive to implementation disruption in production lines
- Prefers vendors with 行业Know-How (industry expertise)
- Values 交钥匙 (turnkey) solutions over best-of-breed

**Reference pattern — 海尔 style:**
海尔 (Haier) built COSMOPlat as an industrial internet platform supporting their 人单合一 (individual-goal unity) management model. The IT architecture challenge: distributed ERP across 4,000+ 小微 (micro-enterprises) while maintaining consolidated group reporting. Required abandoning monolithic SAP for microservices architecture — a multi-year, ¥billions investment. The CIO equivalent (集团CTO) had to simultaneously serve as platform product owner.

**Reference pattern — 理想汽车 style:**
理想汽车 (Li Auto) as a new-energy vehicle manufacturer needed factory IT/OT convergence from day one. Challenges: integrating MES with dealer management, connecting 焊装/涂装/总装 (welding/painting/assembly) shop-floor data to ERP, and building 数据中台 for real-time production visibility. Chose domestic-first stack given 信创 trajectory, avoiding future migration pain.

---

### Archetype C: 金融科技架构师 (Financial Services Technology Architect)

**Profile:** CIO or 科技部总经理 at a bank, insurance company, or securities firm. Age 42–52, often with computer science PhD from top Chinese university (清华/北大/中科院). Reports to 行长/总裁 or 分管副行长.

**Defining context:**
- Regulatory pressure from CBIRC/CSRC on technology self-reliance
- Core banking/trading system replacement is a 5–10 year journey
- 99.99%+ uptime requirement (金融级可用性)
- Massive transaction volumes (双十一 peak: millions TPS)

**What they say:**
- "核心系统迁移是换心脏手术，不能有闪失" (Core system migration is heart transplant surgery — no room for error)
- "分布式架构是方向，但不能一步到位" (Distributed architecture is the direction, but can't do it in one step)
- "监管要求我们每年信创投入占比不低于X%" (Regulator requires our 信创 investment ratio no less than X% annually)
- "我们看的是五年TCO，不是第一年价格" (We look at 5-year TCO, not Year 1 price)

**Decision pattern:**
- Technology committee (技术委员会) group decision
- Extensive POC (3–6 months) before procurement
- Requires source code escrow or access for critical systems
- Benchmarks obsessively: TPC-C, Sysbench, custom workloads
- Strong preference for vendor financial stability (怕厂商倒闭)

**Reference pattern — 港交所 style:**
港交所 (HKEX) built the Orion trading platform on hybrid cloud architecture, achieving 99.99% uptime for post-trade processing. Key architectural decisions: containerization of matching engine, real-time risk calculation on dedicated FPGA, and geographic redundancy across Hong Kong data centers. The technology transformation took 5+ years and required maintaining legacy parallel systems throughout. While HKEX is not mainland-regulated, mainland exchanges (上交所/深交所) face similar architectural challenges with added 信创 constraints.

---

### Archetype D: 出海企业全球化CIO (Globalizing Enterprise CIO)

**Profile:** CIO at a Chinese enterprise expanding internationally (出海). Age 38–48, often with overseas education or MNC experience. Must manage a split architecture: domestic 信创 stack + overseas AWS/Azure.

**Defining context:**
- Dual compliance: 数据安全法/个保法 domestically + GDPR/local laws overseas
- Cannot simply extend domestic systems globally (performance, compliance)
- Must maintain two clouds, two ERP instances, often two email systems
- 跨境数据传输 (cross-border data transfer) is a minefield

**What they say:**
- "国内一套系统，海外一套系统，中间怎么打通是最头疼的" (One system domestically, another overseas — how to connect them is the biggest headache)
- "海外用AWS没问题，但数据回传要过安全评估" (Using AWS overseas is fine, but data repatriation requires security assessment)
- "我们在东南亚的团队希望用Google Workspace，但总部要求用飞书" (Our Southeast Asia team wants Google Workspace, but HQ mandates Feishu)
- "出海业务增长太快，IT跟不上" (Overseas business grows too fast, IT can't keep up)

**Decision pattern:**
- Architect for separation: 境内/境外 (domestic/overseas) clear boundary
- Evaluate vendors on global presence + China compliance simultaneously
- Prefer platforms that work both sides (rare — 华为云 tries, Alibaba Cloud International)
- Heavy reliance on 咨询公司 (consulting firms) for compliance architecture

**Reference pattern — ByteDance/字节跳动 style:**
ByteDance built 飞书 (Feishu/Lark) initially as internal collaboration tool, then productized it. Their global IT challenge: serving 150,000+ employees across 200+ cities with unified tooling while maintaining data sovereignty boundaries between 抖音 (China) and TikTok (global). Architecture: separate data planes with unified control plane design patterns — a template other 出海 enterprises study.

---

### Archetype E: 航空/交通行业遗留系统改造者 (Aviation/Transport Legacy Modernizer)

**Profile:** CIO or IT VP at an airline, airport, railway, or logistics company. Age 45–55, deep domain expertise in industry-specific systems (PSS, DCS, cargo). Often career IT professional in the same industry.

**Defining context:**
- Industry-specific legacy systems (Amadeus, SITA, Sabre) are deeply embedded
- These systems have NO domestic equivalent at comparable maturity
- 信创 pressure exists but timeline is more flexible for "无可替代" systems
- Customer experience digitization (App/小程序) is the visible win

**What they say:**
- "Amadeus用了20年了，替换它不是技术问题，是业务连续性问题" (We've used Amadeus for 20 years — replacing it isn't a tech problem, it's a business continuity problem)
- "旅客服务系统是命根子，动不得" (The passenger service system is our lifeline — can't touch it)
- "先把直销渠道数字化做好，核心系统慢慢来" (First do direct-sales channel digitization well, core systems can wait)
- "我们的数据中心还有IBM大型机在跑" (Our data center still has IBM mainframes running)

**Decision pattern:**
- Incremental modernization: API layer over legacy → strangler fig pattern
- Customer-facing systems modernize first (App, mini-program, self-service kiosk)
- Core operational systems last (too risky, too integrated)
- Heavy dependence on incumbent vendor relationships

**Reference pattern — 国泰航空/Cathay Pacific style:**
Cathay Pacific's IT modernization journey: legacy Amadeus PSS + SITA DCS stack, decade-long relationship. Digital check-in, mobile boarding pass, and NDC adoption were achieved as overlay services. Full PSS migration remains aspirational due to integration complexity with airports, GDS partners, and alliance systems. Mainland Chinese airlines (国航/东航/南航) face identical legacy challenges plus 信创 overlay requirements.

---

### Archetype F: 互联网/科技公司技术VP (Internet/Tech Company Tech VP)

**Profile:** VP of Engineering or 技术副总裁 at a tech company, age 35–45. Often doubles as infrastructure leader. May not carry "CIO" title but owns all internal systems and infrastructure decisions.

**Defining context:**
- Build vs buy bias strongly toward build (自研)
- Infrastructure is a competitive advantage, not a support function
- Scale challenges: millions of users, petabytes of data
- Talent competition is primary constraint (人才是最大的瓶颈)

**What they say:**
- "能自研的就自研，外部产品满足不了我们的规模" (If we can build it ourselves, we build — external products can't handle our scale)
- "我们的基础设施团队比很多厂商的研发团队都大" (Our infra team is bigger than many vendors' R&D teams)
- "开源优先，商业软件是最后选择" (Open source first, commercial software is last resort)
- "K8s我们自己改了30%的代码" (We modified 30% of K8s code ourselves)

**Decision pattern:**
- Open source + internal fork is default approach
- Commercial purchase only for non-differentiating, compliance-driven needs
- Evaluate based on technical depth of vendor engineering team
- Community contribution and ecosystem health matter
- Speed of iteration > perfection

**Reference pattern — ByteDance infrastructure:**
ByteDance operates one of the world's largest private clouds. Internal tools (飞书, 火山引擎) were built for internal scale then commercialized. Infrastructure decisions are engineering-led: extensive use of Go microservices, custom service mesh, proprietary ML training framework. This archetype rarely buys traditional enterprise software — but WILL buy specialized point solutions (observability, security) when build cost exceeds value.

---

## 4. Strategic Priorities (2024–2028)

### Priority 1: 信创替代落地 (信创 Substitution Execution)

**Why it matters:** This is non-negotiable for 国企 and increasingly relevant for 民企 in regulated industries.

**What success looks like:**
- Phase 1 (complete): OA, email, desktop OS migrated
- Phase 2 (in progress): Database, middleware, virtualization migrated
- Phase 3 (2025–2028): Core business systems (ERP, MES, core banking) migrated
- Measurable: % of IT spend on domestic vendors, # of foreign dependencies eliminated

**Challenges CIOs articulate:**
- "国产数据库性能追上来了，但生态工具还差" (Domestic DB performance caught up, but ecosystem tooling lags)
- "用友的实施能力和SAP还是有差距" (用友's implementation capability still gaps SAP)
- "信创产品之间的兼容性测试很痛苦" (Compatibility testing between 信创 products is painful)
- "人才断层——会SAP的不愿学用友，会用友的经验不够" (Talent gap — SAP experts won't learn 用友, 用友 experts lack experience)

### Priority 2: 数据中台/数据治理 (Data Middle Platform / Data Governance)

**Why it matters:** 数据中台 was THE buzzword 2019–2023; now evolving into practical data governance as 数据资产入表 (data assets on balance sheet) policy takes effect.

**What success looks like:**
- Unified data standards across business units
- Real-time data availability for business decisions
- Data quality metrics and ownership assigned
- Compliance with 数据安全法 data classification requirements

**Key architectural decisions:**
- 湖仓一体 (lakehouse) vs traditional data warehouse
- Domestic big data stack: 星环科技 vs 华为FusionInsight vs 阿里DataWorks
- Real-time vs batch processing balance
- Data sharing across subsidiaries (集团数据共享)

### Priority 3: 云架构演进 (Cloud Architecture Evolution)

**Why it matters:** Most China enterprises are in "hybrid multi-cloud" state — often unintentionally.

**Current landscape:**
- 阿里云: Market leader, strongest for internet/retail
- 华为云: Growing fast in 政企 (government/enterprise) segment
- 腾讯云: Strong in gaming/social/fintech
- 天翼云/移动云/联通云: 运营商云 gaining share via government relationships
- AWS/Azure: Only for 出海 workloads (or MNCs in China)

**Decision framework:**
- 核心系统: Private cloud or dedicated region (专属云)
- 互联网业务: Public cloud (阿里/腾讯)
- 开发测试: Public cloud (cost optimization)
- 出海: AWS or Alibaba Cloud International
- 灾备: Cross-region or cross-cloud

### Priority 4: 网络安全与合规 (Cybersecurity & Compliance)

**Why it matters:** 等保2.0 (网络安全等级保护) is mandatory; violations carry personal liability for CIO.

**Compliance framework stack:**
- 等保2.0: Graded protection (levels 1–5), annual assessment
- 数据安全法: Data classification, cross-border transfer assessment
- 个人信息保护法: China's GDPR equivalent
- 关键信息基础设施保护条例: Critical infrastructure rules
- 行业监管: Sector-specific (CBIRC for finance, MIIT for telecom)

**Vendor ecosystem:**
- 奇安信: Endpoint + threat detection (quasi-national champion)
- 深信服: Network security + virtualization
- 安恒信息: Web security, data security
- 启明星辰: Traditional network security
- 天融信: Government segment stronghold

### Priority 5: AI赋能IT运维 (AI-Enabled IT Operations / AIOps)

**Why it matters:** With 信创 migration creating complexity, AI for operations is practical necessity, not innovation theater.

**Application areas:**
- 智能运维 (AIOps): Anomaly detection, root cause analysis
- 智能客服 (AI helpdesk): Internal IT support automation
- 代码辅助 (code assist): Internal development productivity
- 安全态势感知 (security situational awareness): AI-powered SOC

**CIO perspective on AI:**
- "大模型很火，但我先要解决运维的问题" (LLMs are hot, but I first need to solve operations problems)
- "AI的投入产出还不清晰，我不会大规模投" (AI ROI is still unclear, I won't invest at scale)
- "我需要AI帮我降低信创迁移的风险" (I need AI to help reduce 信创 migration risk)

---

## 5. Metrics That Matter

### 5.1 Operational Metrics (稳定性指标)

| Metric | Chinese Term | Target | Context |
|--------|-------------|--------|---------|
| System availability | 系统可用率 | 99.9%–99.99% | Core systems |
| Mean time to recovery | 平均恢复时间 | <30 min (P1) | Production incidents |
| Change success rate | 变更成功率 | >95% | Releases without rollback |
| RTO/RPO | 恢复时间/恢复点目标 | Industry-specific | Disaster recovery |
| Security incidents | 安全事件数 | 0 critical | Regulatory reporting |

### 5.2 信创 Progress Metrics

| Metric | Chinese Term | Target | Context |
|--------|-------------|--------|---------|
| 信创 substitution rate | 信创替代率 | Per SASAC timeline | % systems migrated |
| Domestic vendor spend ratio | 国产化率(采购) | 70%+ by 2027 | SOE procurement |
| Foreign dependency count | 外部依赖数 | Decreasing quarterly | Risk inventory |
| 信创 compatibility issues | 兼容性问题数 | Trending to zero | Integration testing |

### 5.3 Business Alignment Metrics

| Metric | Chinese Term | Target | Context |
|--------|-------------|--------|---------|
| IT cost ratio | IT费用率 | Industry benchmark | % of revenue |
| Project delivery on-time | 项目按时交付率 | >80% | Against business ask |
| Business satisfaction | 业务满意度 | >4/5 | Annual survey |
| Digital adoption | 数字化使用率 | >90% | System utilization |

---

## 6. Language & Communication Patterns

### 6.1 Vocabulary in Native Context

**Terms they use daily:**
- 等保 (děng bǎo) — graded protection compliance
- 信创 (xìn chuàng) — indigenous innovation/substitution
- 上云 (shàng yún) — cloud migration
- 中台 (zhōng tái) — middle platform architecture
- 双活 (shuāng huó) — active-active disaster recovery
- 灾备 (zāi bèi) — disaster recovery/backup
- 运维 (yùn wéi) — IT operations & maintenance
- 割接 (gē jiē) — system cutover
- 厂商 (chǎng shāng) — vendor/manufacturer
- 集成商 (jí chéng shāng) — system integrator
- 招投标 (zhāo tóu biāo) — bidding/procurement process
- 选型 (xuǎn xíng) — technology selection/evaluation

**Phrases that signal priorities:**
- "保生产" (protect production) — stability above all
- "平滑迁移" (smooth migration) — zero-disruption transition
- "自主可控" (autonomous and controllable) — no foreign dependency risk
- "国产替代" (domestic substitution) — 信创 shorthand
- "降本增效" (reduce cost, increase efficiency) — the perennial CIO mandate

### 6.2 How They Communicate Up vs Down

**To CEO/Board (汇报):**
- Focus on risk mitigation and compliance completion
- Use business language, avoid technical jargon
- Frame as "保障" (safeguarding) business operations
- Quantify in ¥ saved or incidents prevented
- Example: "完成信创一期替换，消除了X个供应链断供风险点"

**To direct reports (IT团队):**
- Technical depth, architecture decisions
- Sprint/project-level tracking
- Vendor performance evaluation
- Talent development and retention

**To peer CXOs (跨部门):**
- Frame IT as enabler of their goals
- SLA commitments with business terms
- Joint project governance
- "What do you need from IT" posture

### 6.3 Red Flags in Vendor Pitches (What Turns Them Off)

| What You Say | What They Hear | Better Approach |
|-------------|---------------|-----------------|
| "Cloud-native disruption" | "You'll break my production systems" | "Proven migration path with rollback" |
| "AI-powered everything" | "Immature tech, unclear ROI" | "AI for specific pain point with measured outcome" |
| "Replace your legacy" | "You don't understand my constraints" | "Coexist with current systems, incremental value" |
| "Global best practice" | "Doesn't work in China context" | "Proven at [peer Chinese enterprise]" |
| "Our product is better than SAP" | "Arrogant and probably not true" | "Successfully replaced SAP at [specific customer]" |

---

## 7. Buying Process & Procurement

### 7.1 Procurement Channels

**国企 procurement (governed by 招投标法):**
1. 需求提出 (requirement proposal) — business unit + IT jointly
2. 立项审批 (project approval) — 发改部门 or 投资决策委员会
3. 技术选型 (technology selection) — IT-led evaluation
4. 招标文件编制 (tender document preparation) — procurement dept
5. 公开招标/邀请招标 (public/invited bidding) — formal process
6. 评标/定标 (bid evaluation/award) — committee decision
7. 合同签订 (contract signing) — legal review
8. 实施验收 (implementation acceptance) — IT-led

**Timeline:** 6–18 months from need identification to contract signing for major systems.

**民企 procurement (more flexible):**
1. CIO/IT总监 identifies need
2. Shortlist 3–5 vendors (often via industry network/analyst)
3. POC or reference visit (标杆考察)
4. CFO budget approval for large deals
5. Negotiation and signing
6. Timeline: 2–6 months

### 7.2 Decision Influencers

| Role | Influence Type | What They Care About |
|------|---------------|---------------------|
| CIO/IT总监 | Technical decision | Architecture fit, vendor capability |
| CFO | Budget approval | TCO, payment terms |
| CEO/总裁 | Strategic alignment | Does this support group strategy? |
| 业务部门负责人 | Requirement owner | Will it solve my problem? |
| 采购部 | Process compliance | Is bidding process proper? |
| 审计部 | Post-hoc review | Was money well spent? |
| 集成商/咨询公司 | Advisor/influencer | Often write tender specs |

### 7.3 Vendor Relationship Dynamics

**The 集成商 (SI) layer:**
Most large China enterprise IT deals flow through system integrators:
- 中国软件/中电太极 (SOE-affiliated)
- 神州数码 (distribution + integration)
- 软通动力/中软国际 (services)
- 德勤/埃森哲/IBM (MNC consulting, declining for 国企)

**Why this matters:** Even if you have the best product, without SI partnership you may not get on the shortlist. The SI often writes the 招标文件 (tender document).

**Relationship maintenance:**
- Quarterly business reviews (QBR) with dedicated account team
- 驻场服务 (on-site support) during critical periods
- Executive visits (总裁/VP级别拜访) for relationship depth
- Industry conferences and 闭门会 (closed-door meetings)

---

## 8. Organizational Dynamics & Stakeholder Relationships

### 8.1 CIO's Relationship with Other CXOs

**CIO ↔ CEO/董事长:**
- CIO needs CEO air cover for 信创 budget and organizational change
- CEO expects CIO to "just make IT work" — visibility only when problems arise
- Strategic CIOs build CEO trust through small wins before requesting large investments

**CIO ↔ CFO:**
- CFO controls budget — primary gatekeeper for IT spend
- CIO must justify every investment in financial terms
- 信创 helps: "this is mandated compliance spend" bypasses normal ROI scrutiny
- Tension: CFO wants CapEx→OpEx (cloud), CIO may prefer CapEx (control)

**CIO ↔ COO:**
- In manufacturing: COO owns production, CIO enables with IT/OT systems
- High collaboration on MES, supply chain, logistics systems
- CIO often reports to COO in operational enterprises

**CIO ↔ CISO (if separate):**
- In China, CISO function often sits WITHIN CIO organization
- 等保 compliance is CIO's direct responsibility
- Larger enterprises (金融) may have independent CISO (首席安全官)

**CIO ↔ CDO (首席数据官):**
- Emerging role conflict: who owns 数据中台?
- CIO owns infrastructure and platforms; CDO owns data strategy and governance
- In practice, often same person or CDO reports to CIO

### 8.2 Internal Political Dynamics

**CIO's power sources:**
1. 合规权 — "Regulator requires this" (unchallengeable)
2. 专业权 — Technical expertise that others lack
3. 连接权 — Controls the technology that connects all departments
4. 预算权 — IT budget allocation across business units

**CIO's vulnerabilities:**
1. "IT is a cost center" perception — constant pressure to prove value
2. Shadow IT — business units buying their own SaaS without CIO approval
3. 信创 failure risk — if migration causes outage, CIO is blamed
4. Vendor lock-in perception — "why did you choose this vendor?"

---

## 9. Information Sources & Influence Channels

### 9.1 Where They Learn

| Channel | Examples | Usage Pattern |
|---------|----------|---------------|
| Industry conferences | 数博会, 云栖大会, 华为HC | Annual attendance, peer networking |
| Peer CIO networks | CIO时代, 信息化研究会 | Monthly roundtables |
| Analyst reports | Gartner (translated), IDC, 赛迪 | Technology selection reference |
| Government guidance | 工信部, SASAC 文件 | Policy compliance interpretation |
| Vendor briefings | Quarterly, by invitation | Product roadmap updates |
| WeChat groups | Industry CIO groups | Daily informal exchange |
| 闭门交流会 | Vendor-hosted, peer-only | Deep-dive on specific topics |

### 9.2 Trusted Information Hierarchy

1. **Peer CIO at similar enterprise** — highest trust ("他们踩过什么坑")
2. **Industry analyst with China expertise** — validates direction
3. **集成商/咨询公司 recommendation** — biased but experienced
4. **Vendor reference customer** — valuable if verifiable
5. **Vendor sales materials** — lowest trust, used for initial screening only

### 9.3 Key Publications & Media

- 信息化建设 (Informatization Construction) — government-linked
- CIO时代 (CIO Era) — peer community
- 至顶网 (ZDNet China) — technology media
- 36氪 (36Kr) — tech industry coverage
- 钛媒体 (TMTPost) — enterprise technology
- 中国信通院 (CAICT) reports — authoritative industry data

---

## 10. Objection Patterns & How to Address Them

### Objection 1: "你们有没有同行业案例？" (Do you have cases in our industry?)

**Why they ask:** Risk mitigation — if a peer succeeded, their risk is lower.

**How to address:**
- Provide specific, verifiable reference customers (named, not anonymous)
- Offer reference visit (标杆参观) — physical site visit to reference customer
- If no exact peer: adjacent industry + technical similarity argument
- "We helped [similar scale enterprise] in [adjacent industry] solve [identical problem]"

### Objection 2: "信创目录里有你们吗？" (Are you on the 信创 approved list?)

**Why they ask:** For 国企, purchasing from non-信创 vendors may be impossible.

**How to address:**
- If yes: provide certification number, category listing
- If no: explain compatibility with 信创 stack, plan for certification
- For foreign vendors: position as "信创配套" (complementary to 信创) rather than replacement target
- Partner with 信创 ecosystem player for joint solution

### Objection 3: "实施周期多长？谁来实施？" (How long is implementation? Who implements?)

**Why they ask:** They've been burned by long, over-budget projects. Vendor promises vs reality gap.

**How to address:**
- Provide phased implementation plan with clear milestones
- Name the SI partner and their specific experience
- Offer 驻场 (on-site) team during critical phases
- Contractual SLA on implementation timeline with penalties

### Objection 4: "出了问题你们多快能响应？" (How fast can you respond when issues arise?)

**Why they ask:** Post-sales support quality varies wildly; after-sales is where trust is built or broken.

**How to address:**
- 7×24 support center location (must be in China)
- Chinese-speaking L2/L3 engineers (not translated tickets)
- Committed SLA: P1 response in 15 minutes, resolution in 4 hours
- Named technical account manager (技术客户经理)
- Escalation path to vendor R&D

### Objection 5: "价格太贵了" (Too expensive)

**Why they ask:** Standard negotiation, but also reflects genuine budget pressure.

**How to address:**
- Reframe as TCO: include migration cost from incumbent, operational cost, risk cost
- Compare to cost of NOT doing it (compliance penalty, outage cost)
- Flexible commercial model: subscription, consumption-based, phased payment
- 信创专项资金 (dedicated 信创 budget) angle: "This fits your 信创 allocation"

---

## 11. Engagement Playbook

### 11.1 First Meeting (初次拜访)

**Do:**
- Research their 信创 status and timeline before meeting
- Bring a technical architect, not just sales
- Ask about their current pain points before presenting
- Reference peer enterprises they respect
- Prepare Chinese-language materials (not translated English)

**Don't:**
- Lead with product demo — lead with understanding their situation
- Assume they want "digital transformation" — they want stability + compliance
- Pitch features — pitch outcomes and risk mitigation
- Ignore the 集成商 relationship — ask who their SI partners are
- Rush — first meeting is 建立信任 (building trust), not closing

### 11.2 POC / Proof of Concept (技术验证)

**Structure that works:**
1. Agree success criteria upfront (验收标准) — in writing
2. Scope tightly: one use case, one system, defined timeline
3. Provide dedicated POC support engineer (not remote)
4. Include compatibility testing with their 信创 stack
5. Document results in their report format (for internal approval chain)

**POC red flags (they're using you for free consulting):**
- Scope keeps expanding without commitment timeline
- No executive sponsor identified
- "We'll evaluate after the POC" with no decision date
- Asking for source code access during POC

### 11.3 Navigating the Approval Chain

```
Phase 1: Technical Validation (IT团队)
   └── CIO/IT总监 aligned? → Proceed
   
Phase 2: Business Case (业务部门)
   └── Business sponsor aligned? → Proceed
   
Phase 3: Budget Approval (CFO/财务)
   └── Budget available? → Proceed
   
Phase 4: Procurement Process (采购部)
   └── Bidding/selection process → Award
   
Phase 5: Contract (法务)
   └── Terms negotiation → Signing
```

**Key insight:** You need champions at EACH level. Technical win without business sponsor = stalled deal. Business need without budget = unfunded mandate.

---

## 12. Competitive Landscape (Vendor Ecosystem)

### 12.1 ERP — The Biggest Decision

| Vendor | Strength | Weakness | Target Segment |
|--------|----------|----------|----------------|
| 用友 U9C/YonBIP | 信创 native, large install base | Complex implementation, talent scarce | Large 国企/民企 |
| 金蝶 云星空 | Cloud-native, modern UX | Less proven for mega-enterprises | Mid-large enterprises |
| 浪潮 GS Cloud | Government relationship | Smaller ecosystem | 国企, government |
| SAP S/4HANA | Mature, global capability | 信创 risk, expensive | MNCs, 出海 enterprises |
| Oracle ERP Cloud | Strong financials module | Leaving China market concerns | Legacy customers only |

### 12.2 Database — Core of 信创

| Vendor | Type | Strength | Adoption |
|--------|------|----------|----------|
| 达梦 (DM) | Relational | Oracle compatible, 国企首选 | Government, SOE |
| OceanBase (蚂蚁) | Distributed | Proven at Ant scale | Finance, internet |
| TiDB (PingCAP) | Distributed | MySQL compatible, open source | Internet, finance |
| GaussDB (华为) | Relational+Distributed | 华为 ecosystem play | 华为 customers |
| 人大金仓 (KingBase) | Relational | PostgreSQL based, 信创 | Government |

### 12.3 Cloud Infrastructure

| Vendor | Market Share (IaaS) | Sweet Spot |
|--------|--------------------:|------------|
| 阿里云 | ~33% | Internet, retail, SaaS |
| 华为云 | ~19% | 政企, manufacturing, telecom |
| 腾讯云 | ~16% | Gaming, social, fintech |
| 天翼云 | ~11% | Government, 央企 |
| AWS (中国) | ~7% | MNCs, 出海 |

### 12.4 Security

| Vendor | Focus | 信创 Status |
|--------|-------|-------------|
| 奇安信 | Endpoint, XDR | Core 信创 player |
| 深信服 | Network security, VDI | Strong 信创 credentials |
| 安恒信息 | Data security, WAF | Growing in data compliance |
| 启明星辰 | Network detection | Traditional strength |
| 天融信 | Government security | Deep government relationships |

---

## 13. Risk Factors & Failure Modes

### 13.1 Why CIO Initiatives Fail in China

1. **信创兼容性问题 (Compatibility failures)**
   - Domestic DB + domestic middleware + domestic OS = untested combination
   - Performance regression in production vs POC environment
   - Application rewrite cost underestimated by 3–5x

2. **实施方人员不足 (Implementer resource shortage)**
   - 用友/金蝶 certified consultants are scarce relative to demand
   - Best consultants overcommitted across multiple projects
   - Knowledge transfer from vendor to internal team fails

3. **组织变革阻力 (Organizational resistance)**
   - Business users comfortable with old system refuse to adopt new
   - Middle management sees digitization as threat to information asymmetry power
   - Training investment insufficient

4. **供应商锁定翻转 (Vendor lock-in flip)**
   - Escape Oracle lock-in → walk into 用友 lock-in
   - Domestic vendors lack migration tooling between each other
   - Multi-vendor strategy adds integration complexity

### 13.2 Career Risk for CIOs

| Risk Event | Consequence | Mitigation They Seek |
|------------|-------------|---------------------|
| Major production outage | Immediate 问责, possible demotion | Redundancy, DR, vendor SLA |
| 信创 timeline miss | Political pressure from SASAC | Conservative scheduling, buffer |
| Data breach | Personal liability under 数据安全法 | Insurance, security vendor SLA |
| Budget overrun >30% | Loss of credibility with CFO/CEO | Fixed-price contracts, phased approach |
| Vendor bankruptcy/exit | Stranded systems | Multi-vendor strategy, escrow |

---

## 14. Engagement Timing & Trigger Events

### 14.1 When CIOs Are Most Receptive

| Trigger Event | Why It Opens Budget | Timing |
|---------------|--------------------:|--------|
| 信创 audit/inspection notice | Must show progress | Immediate |
| ERP end-of-support announcement | Forced decision | 6–12 months before deadline |
| Major system outage | Pain is fresh | Within 2 weeks of incident |
| New CEO/board digital mandate | Political capital available | First 6 months of new leadership |
| Annual budget planning | Slot for next year | Q3 (July–September) |
| 十四五/十五五 planning | 5-year plan alignment | Planning year |
| IPO preparation | Need audit-grade systems | 12–18 months pre-IPO |
| M&A integration | Must consolidate systems | Post-close 3–6 months |

### 14.2 Budget Cycles

- **国企:** Annual budget cycle, approved by December for next year. Supplementary budgets possible for 信创 mandates mid-year.
- **民企:** More flexible, quarterly adjustment possible. Major investments still annual.
- **MNC China:** Global budget cycle (often calendar year), China allocation within global envelope.

---

## 15. Summary: Key Principles for Engaging China CIOs

1. **信创 is the door opener.** Frame your value proposition in terms of how you help their 信创 journey — whether you're a domestic vendor on the 信创 list or a foreign vendor helping them bridge.

2. **Stability > Innovation.** Never position as disruptive. Position as proven, reliable, lower-risk than alternatives.

3. **Peer proof is king.** One named reference customer in their industry is worth more than any feature comparison.

4. **Respect the process.** 招投标 and approval chains exist for reasons. Work within them, don't try to shortcut.

5. **Build the ecosystem.** Partnership with 集成商 and complementary vendors is essential for deal flow.

6. **Local presence is non-negotiable.** Chinese-speaking support, local data centers, on-site implementation capability.

7. **Think in 5-year cycles.** 五年规划 thinking means CIOs plan in long arcs. Initial deal may be small; relationship value is in the 3–5 year expansion.

8. **Title doesn't equal power.** A 信息中心主任 at a 央企 may control ¥500M+ annual IT budget. Don't judge by title hierarchy.

---

*End of persona document.*
