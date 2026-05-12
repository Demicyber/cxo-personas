# CTO — 首席技术官 · China-Market Persona

| Field | Detail |
|-------|--------|
| **Title variants** | CTO, 首席技术官, VP Engineering, 技术合伙人, 总工程师 (SOEs), Chief Architect |
| **Reports to** | CEO / Founder (often technical themselves in 民企) |
| **Direct reports** | VP Engineering, Architects, AI/ML Lead, Infra Lead, Security, QA/DevOps |
| **Revenue band** | Influences ¥50M–¥5B+ in technology spend annually |
| **Buying authority** | Full authority on tech stack; co-decision with CEO on platform bets >¥10M |
| **Typical tenure** | 2–4 years (民企/startups); 5–10 years (国企/总工程师) |
| **�ducation** | CS/EE from 985 universities or overseas MS/PhD; increasingly self-taught founders |

---

## Reader Note

> **Reader note.** This document is written to be readable and extractable by AI agents of varying capability — from small open-weights models up to frontier models. Concepts are spelled out explicitly rather than implied; some redundancy across sections is intentional so that any single section remains useful in isolation (e.g. when retrieved on its own). If you are a strong model, skim the key insight inside each block; if you are a weaker model, read the full block. The China CTO role reflects the unique intersection of technology sovereignty (信创/自主可控), AI transformation (大模型), and global-local architectural duality (出海).

> **Data usage instruction for agents.** All company names, executive names, financial figures, and examples in this document are illustrative — they teach you the *pattern* (what this persona cares about, how they talk, how they decide). They are NOT current data to be cited verbatim in customer-facing outputs. When generating any customer-facing deliverable, you MUST verify any peer proof, financial figures, or competitive references against current public sources (earnings calls, press releases, annual reports) before including them. Treat examples here as "this is the *type* of thing to look for" — then go find the latest version.
>
> Data vintage: Examples and figures sourced primarily from FY2024–FY2026 public disclosures and industry research, with select forward-looking references through 2027. China-market context reflects policy environment through 15th Five-Year Plan (2026–2030) early signals.

---

## What a CTO Actually Is — China Context

In Western companies the CTO is a well-defined role with clear boundaries against the VP Engineering. In China's technology landscape, the CTO role is **far more fluid**:

1. **Technical Founder as CTO** — Li Xiang (理想) personally reviews autonomous driving architecture. 阳萌 (Anker) came from Google engineering. These founders *are* the CTO even when someone else holds the title.

2. **Platform Evangelist** — At 海尔, the CTO role is inseparable from COSMOPlat's industrial internet vision; technology *is* the business model.

3. **Government Interface** — In 国企 or regulated sectors (港交所, 海康威视), the CTO/总工程师 manages 信创 compliance, patent portfolios for 高新企业 qualification, and regulatory tech mandates.

4. **Talent Magnet** — In the AI era, the CTO's personal GitHub profile, open-source contributions, and conference appearances directly impact recruiting against BAT/ByteDance.

5. **Cost Center Guardian vs. Revenue Driver** — The perpetual tension. ByteDance's CTO owns recommendation algorithms that *are* revenue. Cathay Pacific's CTO modernizes legacy systems that *cost* money.

The China CTO operates in an environment where **technology sovereignty is national policy**, where the AI arms race has executive-level urgency, and where the founder is often technically literate enough to challenge architectural decisions directly.

---

## §1 Role Definition

### 1.1 Six CTO Archetypes

| Archetype | Description | Example Pattern |
|-----------|-------------|-----------------|
| **技术创始人型 (Technical Founder)** | Founder who retains hands-on tech authority; title may be CEO but functions as CTO | 李想 reviewing AD stack; 阳萌 setting Anker's IoT architecture; 周亦竞 at 禾观 |
| **平台架构师 (Platform Architect)** | Builds internal platforms that become competitive moats | 海尔 COSMOPlat; ByteDance's recommendation infrastructure; 港交所 Orion platform |
| **信创迁移型 (Localization Migration Lead)** | Focused on replacing Western stack with domestic alternatives under policy pressure | 海康威视 post-sanctions chip strategy; SOE IT leaders replacing Oracle/VMware |
| **AI 布道者 (AI Evangelist)** | Defines and executes 大模型 strategy; build vs. buy vs. fine-tune decisions | ByteDance 豆包(Doubao); 猎豹 OrionStar LLM integration; Shein demand prediction |
| **产品技术VP (Product-Tech Hybrid)** | Bridges engineering and product; common in consumer tech | WeBull mobile-first architecture; 腾讯游戏 engine decisions; Anker smart home |
| **稳态守护者 (Stability Guardian)** | Risk-averse, availability-first; regulatory-compliant architecture | 港交所 ultra-low-latency; Cathay Pacific safety-critical IT; WeBull regulatory compliance |

### 1.2 Diagnostic Table — Identifying the Archetype

| Signal | Likely Archetype |
|--------|-----------------|
| Founder still reviews PRs / architecture docs | 技术创始人型 |
| Company has "XX Platform" as a product line | 平台架构师 |
| Recent 信创 procurement announcements | 信创迁移型 |
| Hiring heavily for ML/AI roles; published 大模型 strategy | AI 布道者 |
| CTO speaks at product launches, not just tech conferences | 产品技术VP |
| Industry is finance / aviation / critical infra | 稳态守护者 |
| Multiple signals present | Blend — lead with dominant, acknowledge secondary |

### 1.3 Three Time Horizons

| Horizon | Timeframe | Focus | Example |
|---------|-----------|-------|---------|
| **H1: Keep the lights on** | 0–6 months | Reliability, security patches, 信创 audit compliance, cost optimization | 港交所 maintaining 99.999% uptime during Orion migration |
| **H2: Platform evolution** | 6–18 months | Architecture modernization, AI integration, talent pipeline | 海康威视 building Edge AI chips after 海思 restrictions |
| **H3: Strategic bets** | 18–36 months | New technology paradigms, 出海 architecture, next-gen platforms | ByteDance global LLM infrastructure; 理想 L4 autonomy stack |

### 1.4 Four-Way Pull

The China CTO is pulled in four directions simultaneously:

```
                    CEO / 创始人
                    "我们的大模型策略是什么?"
                    "竞品已经上线了AI功能"
                         │
                         ▼
    Engineering ◄────── CTO ──────► Business / Product
    "We need 6 months       │        "Customers want it
     to do it right"        │         by next quarter"
     "996 is killing         │        "Can we buy instead
      retention"            │         of build?"
                         │
                         ▼
              Regulators / 信创 / 合规
              "Must use 国产数据库 by 2025"
              "Data must stay in China"
              "Patent count for 高新资质"
```

**CEO/Founder Pull** — In companies like 理想 or Anker, the founder is technical and will challenge choices. In others, the CEO demands AI strategy answers *now* because board/investors are asking.

**Engineering Pull** — Talent retention post-996 backlash. Engineers want modern stacks, interesting problems, and work-life balance. Losing a senior AI engineer to ByteDance is a 6-month setback.

**Business/Product Pull** — Revenue-side pressure to ship features. Shein's CTO must balance algorithmic accuracy with speed-to-market. 腾讯游戏 must ship titles on schedule.

**Regulatory/信创 Pull** — Government mandates on domestic technology adoption. 海康威视 had to rebuild chip dependencies. 港交所 must comply with HKMA/SFC technology guidelines. Patent generation for subsidies.

---

## §2 Strategic Priorities

### Priority 1: AI / 大模型 Strategy (The Inescapable Topic)

Every China CTO in 2024-2026 faces the same question from their CEO: *"我们的大模型策略是什么？"*

**The decision matrix:**

| Approach | When | Example |
|----------|------|---------|
| **Build foundation model** | Only if >1000 GPU cluster + top talent | ByteDance 豆包; extremely rare |
| **Fine-tune open-source** | Most common for tech-forward companies | 猎豹 using open models for OrionStar robots; 禾观 fine-tuning for e-commerce search |
| **API integration (buy)** | Fast time-to-market, less differentiation | Cathay Pacific using cloud AI services; WeBull integrating LLM for research summaries |
| **Hybrid** | Core capabilities built, periphery bought | 海康威视 own CV models + third-party LLM for text; 腾讯游戏 own engine + partner AI NPCs |

**China-specific AI considerations:**
- GPU access constrained (A100/H100 export controls) — must plan around A800/domestic alternatives
- 国产大模型 options: 百度文心, 阿里通义, ByteDance豆包, 智谱GLM, MiniMax, 月之暗面
- Data sovereignty: training data cannot leave China; inference for 出海 needs separate infrastructure
- Talent: top AI researchers have 5+ competing offers; comp packages ¥2M–¥8M+ for principals

### Priority 2: 信创 (IT Localization / Xinchuang)

信创 = 信息技术应用创新 — the national policy to replace Western technology with domestic alternatives.

**Replacement map affecting CTO decisions:**

| Western Stack | Domestic Alternative | Migration Pain |
|---------------|---------------------|----------------|
| Oracle DB | 达梦, OceanBase, TiDB, GaussDB | High — stored procedures, performance tuning |
| VMware | 华为FusionCompute, ZStack, 深信服 | Medium — API differences, ecosystem |
| Windows Server | 统信UOS, 麒麟OS | High — application compatibility |
| Intel/AMD chips | 鲲鹏, 飞腾, 龙芯, 海光 | Very High — performance gap, recompilation |
| AWS/Azure | 阿里云, 腾讯云, 华为云 | Medium — similar APIs, data migration |
| Cisco networking | 华为, 新华三(H3C), 锐捷 | Low–Medium |

**Who is most affected:**
- 国企 and government-adjacent: mandatory timelines
- 海康威视: directly sanctioned, must self-build
- 港交所: Hong Kong SAR has softer requirements but political pressure
- Private companies (Shein, ByteDance): pragmatic — comply where needed, optimize elsewhere

### Priority 3: Architecture Modernization

| Pattern | Driver | Example |
|---------|--------|---------|
| Monolith → Microservices | Scale, team autonomy | Cathay Pacific legacy airline systems |
| On-prem → Cloud-native | Agility, cost | 海尔 manufacturing IT to COSMOPlat |
| Single-region → Global | 出海 expansion | ByteDance (global + China dual stack), Shein, WeBull |
| Batch → Real-time | User experience, AI | Shein real-time demand prediction; 港交所 Orion low-latency |
| Proprietary → Open-source | Cost, talent, 信创 alignment | TiDB adoption, Kubernetes everywhere |

**Dual-stack architecture for 出海 companies:**
Companies like ByteDance, Shein, WeBull, and Anker must maintain:
- China stack: 国产云, compliant data residency, 信创-aligned where needed
- Global stack: AWS/GCP, GDPR-compliant, low-latency regional deployment
- Shared: Core algorithms, development tooling, CI/CD (but separate data planes)

### Priority 4: Security & Compliance

- **数据安全法 (Data Security Law)** and **个人信息保护法 (PIPL)** — direct CTO responsibility
- Cross-border data transfer assessments (especially for 出海 companies)
- 等保2.0 (Classified Protection 2.0) — mandatory security certification levels
- Supply chain security post-SolarWinds awareness
- Gaming: 防沉迷 (anti-addiction) technical implementation (腾讯游戏)
- Financial: real-time risk monitoring, regulatory reporting (WeBull, 港交所)

### Priority 5: Talent Strategy

The China tech talent landscape in 2024-2026:

| Challenge | CTO Response |
|-----------|--------------|
| AI engineer shortage | Open-source contributions as recruiting tool; 产学研合作 with universities |
| Post-996 expectations | Flexible hours, remote options, project-based intensity |
| BAT/ByteDance comp wars | Equity-heavy packages; mission-driven narrative; technical challenge differentiation |
| 35岁危机 (age-35 crisis) | Creating IC (individual contributor) career ladders |
| Overseas talent return | Leveraging 海归 for global architecture decisions |

**Example:** 海康威视 maintains 10,000+ R&D engineers by positioning as an "AI company that happens to make cameras" — the tech narrative matters for recruitment.

### Priority 6: Open Source Strategy

Open source in China is simultaneously:
- **Recruiting tool** — Engineers want to work on visible projects
- **信创 alignment** — Open source satisfies "not dependent on foreign vendors"
- **Reputation builder** — PingCAP (TiDB), Ant (OceanBase), ByteDance (CloudWeGo) examples
- **Cost optimization** — Reduce licensing costs
- **Risk** — Governance, security vulnerabilities, maintenance burden

### Priority 7: Cost Optimization & FinOps

- Cloud spend under scrutiny as growth slows in many sectors
- GPU compute costs for AI training/inference are explosive
- 信创 migration often *increases* short-term costs (lower efficiency, dual-running)
- Board pressure: "Unit economics of AI features — when does it pay back?"

---

## §3 Key Performance Indicators

### 3.1 Operational KPIs

| KPI | Target Range | Context |
|-----|-------------|---------|
| System availability | 99.9%–99.999% | 港交所 demands five-nines; SaaS companies target three-nines |
| Deployment frequency | Daily–Weekly | ByteDance: thousands/day; 港交所: monthly release windows |
| Mean time to recovery (MTTR) | <15 min (critical) | Directly impacts revenue for trading platforms, e-commerce |
| P99 latency | <50ms (trading); <200ms (consumer) | 港交所 Orion targeting microsecond-level; WeBull <100ms |
| Security incidents (P0) | 0 | Any breach is career-ending in regulated sectors |

### 3.2 Strategic KPIs

| KPI | Target Range | Context |
|-----|-------------|---------|
| AI model accuracy / business lift | +5–20% on core metric | Shein: demand prediction accuracy; ByteDance: recommendation CTR |
| 信创 migration progress | Per government timeline | % of systems on domestic stack |
| Engineering velocity (features/sprint) | Improving trend | Measured against headcount growth |
| Talent retention (senior engineers) | >85% annual | Losing <15% of senior staff |
| Patent filings | 50–200+/year | Required for 高新企业 certification (¥ millions in tax benefits) |
| Tech debt ratio | Decreasing | Ratio of maintenance to feature work |
| Cloud cost per transaction | Decreasing | FinOps maturity indicator |
| Open-source contributions | Increasing | GitHub stars, community engagement as proxy |

### 3.3 Business-Linked KPIs

| KPI | Connection |
|-----|-----------|
| Time-to-market for AI features | Competitive response speed |
| Platform uptime during 双十一/大促 | Direct revenue protection (Shein, e-commerce) |
| Autonomous driving miles without intervention | 理想 L4 progress |
| Robot task completion rate | 猎豹 OrionStar service quality |
| Trading system throughput (orders/sec) | 港交所 market capacity |
| Concurrent users supported | 腾讯游戏 peak capacity |

---

## §4 Pain Points

### 4.1 The AI Pressure Cooker

| Pain | Manifestation |
|------|---------------|
| "Everyone wants AI, nobody has clear ROI" | CEO asks for 大模型 strategy; board wants AI narrative for valuation; actual use cases are fuzzy |
| GPU scarcity | Cannot access top NVIDIA chips; must optimize around A800 or domestic alternatives |
| Build vs. buy paralysis | Building is slow and expensive; buying creates dependency; fine-tuning is the compromise |
| AI talent auction | Senior ML engineers command ¥3–5M packages; still lose them to ByteDance/startups |
| Hallucination liability | Deploying LLMs in production (customer-facing) carries brand/legal risk |

**Verbatim-style pain statement:** *"CEO看到竞品发布了AI功能，问我为什么我们还没有。但我们连GPU都不够，人也招不到，而且这个功能的ROI根本算不清楚。"*

### 4.2 信创 Migration Nightmare

| Pain | Manifestation |
|------|---------------|
| Performance regression | Domestic databases 30–50% slower on complex queries; need architecture redesign |
| Ecosystem gaps | No equivalent to Oracle RAC or VMware vMotion in domestic stack |
| Dual-running costs | Must maintain both stacks during migration (2–3 year window) |
| Skills shortage | Team knows Oracle; retraining on 达梦/OceanBase takes time |
| Vendor immaturity | Domestic vendors' enterprise support is weaker; documentation sparse |

### 4.3 Technical Debt vs. Innovation Tension

| Pain | Manifestation |
|------|---------------|
| Legacy system lock-in | Cathay Pacific: decades of airline IT spaghetti; 海尔: factory systems from different eras |
| Refactoring gets no budget | "That doesn't ship features" — CEO won't fund unless system is failing |
| Talent won't work on legacy | Senior engineers leave if asked to maintain old Java/C++ monoliths |
| Migration risk | Rewriting working systems introduces new bugs in production |

### 4.4 Talent & Organizational Pain

| Pain | Manifestation |
|------|---------------|
| Competing with BAT for AI talent | ByteDance offers ¥4M+ for senior ML; smaller companies can't match |
| 35岁焦虑 in the team | Experienced engineers fear being replaced; junior developers lack depth |
| Remote/hybrid friction | Post-COVID: engineers want flexibility; security concerns with remote access |
| Founder override | Technical founder (理想/Anker pattern) reverses CTO decisions → team confusion |

### 4.5 出海 Architectural Complexity

| Pain | Manifestation |
|------|---------------|
| Dual compliance | GDPR + 个保法; different data residency rules per market |
| Network latency | China ↔ Global backbone is unreliable; need redundant paths |
| Stack divergence | China uses 阿里云; global uses AWS; two teams, two deployments |
| Vendor relationships | Some vendors can't operate in China; some China vendors can't serve global |

### 4.6 Regulatory Whiplash

| Pain | Manifestation |
|------|---------------|
| Algorithmic regulation (算法备案) | Must register recommendation algorithms with CAC — ByteDance, Shein affected |
| Gaming restrictions | 腾讯游戏: anti-addiction tech requirements change frequently |
| Financial compliance | WeBull/港交所: new requirements with short implementation timelines |
| AI regulation (生成式AI管理办法) | Must filter outputs, maintain training data records, accept audits |

---

## §5 Objection Patterns

### Objection 1: "我们自己能做" (We Can Build It Ourselves)

**Why they say it:**
- Technical pride — especially 技术创始人型 and 平台架构师 archetypes
- Fear of external dependency (heightened by 信创 experience with vendor lock-in)
- Belief that core differentiation must be built in-house

**Frequency:** 70%+ of initial conversations with tech-forward CTOs

**Counter-framework:**

| Angle | Approach |
|-------|----------|
| **Time-to-value** | "Your team *could* build this in 18 months. What's the cost of 18 months of delay versus competitors shipping now?" |
| **Opportunity cost** | "Your AI engineers cost ¥3M each. Building infrastructure vs. building differentiating features — which creates more value?" |
| **Maintenance burden** | "Building is 20% of the cost. Maintaining, patching, scaling is 80%. Do you want to own that forever?" |
| **Hybrid positioning** | "Build your core IP on top of our platform. We handle the undifferentiated heavy lifting." |

**Example:** 海康威视 builds core CV models in-house but uses external platforms for non-core functions like internal IT. The key is knowing where the differentiation boundary lies.

### Objection 2: "开源替代方案就够了" (Open-Source Alternative Is Sufficient)

**Why they say it:**
- 信创 alignment (open source = not dependent on foreign commercial vendor)
- Cost consciousness
- Engineering team prefers open tools they can modify
- Community credibility / recruiting benefit

**Counter-framework:**

| Angle | Approach |
|-------|----------|
| **TCO reality** | "Open-source is free like a puppy is free. Who maintains it? Who's on-call at 3AM for a Kafka bug?" |
| **Enterprise features gap** | "The gap between open-source and enterprise: SSO, audit logs, compliance reports, SLA guarantees" |
| **Acknowledge and complement** | "We love open source too. Our product *extends* [specific OSS project] with enterprise features your team shouldn't build" |
| **Support risk** | "When 双十一 traffic spikes and the OSS community is asleep, who do you call?" |

### Objection 3: "信创合规要求我们用国产" (Xinchuang Compliance Requires Domestic)

**Why they say it:**
- Genuine regulatory mandate (especially 国企, government-adjacent)
- Sometimes used as polite rejection ("regulations won't allow it")
- Fear of audit risk

**Counter-framework:**

| Angle | Approach |
|-------|----------|
| **Clarify scope** | "Which systems are in-scope for 信创? Core production or all IT? We often find non-core systems have flexibility" |
| **Partnership model** | "We partner with [domestic vendor]. Our technology runs on their certified infrastructure" |
| **Hybrid reality** | "For 出海 workloads, 信创 doesn't apply. Your global architecture still needs best-of-breed" |
| **Compliance certification** | Show 等保/信创 certifications if you have them |

### Objection 4: "集成太复杂" (Integration Is Too Complex)

**Why they say it:**
- Burned by past vendor integrations that took 6 months and failed
- Complex existing architecture (especially legacy + cloud hybrid)
- Limited integration engineering bandwidth

**Counter-framework:**

| Angle | Approach |
|-------|----------|
| **Proof via POC** | "Let's prove integration in 2 weeks on a non-critical system. If it works, we expand" |
| **Reference architecture** | "Here's how [similar company] integrated in [X] weeks. Architecture diagram attached" |
| **API-first design** | "We're API-first, Kubernetes-native. Your team already knows these patterns" |
| **Professional services** | "Our SA team handles integration. Your engineers stay focused on features" |

### Objection 5: "现在不是时候" (Now Is Not the Right Time)

**Why they say it:**
- Genuinely overloaded (信创 migration + AI strategy + daily fires)
- Budget cycle misalignment
- Waiting for internal strategy clarity

**Counter-framework:**

| Angle | Approach |
|-------|----------|
| **Competitor pressure** | "Your competitor [X] went live last quarter. Every month of delay is market share risk" |
| **Start small** | "We don't need a big commitment. A 30-day pilot with 2 engineers. No procurement process needed" |
| **Align to their cycle** | "When does your next planning cycle start? Let's prepare the business case now for inclusion" |
| **Cost of delay calculation** | Quantify what delayed delivery means in revenue/efficiency terms |

---

## §6 Buying Dynamics

### 6.1 Decision Process

```
Trigger Event (competitor ships AI feature / CEO mandate / system failure)
         │
         ▼
Internal Assessment (CTO + architects, 2-4 weeks)
"Can we build it? What's the gap?"
         │
         ▼
Market Scan (architects research, 2-4 weeks)  
"Who's in the market? Open source options? 信创-compliant?"
         │
         ▼
Technical Evaluation (POC/benchmark, 4-8 weeks)
"Does it actually work in our environment?"
         │
         ▼
Business Case (CTO + Finance, 2-4 weeks)
"ROI, TCO, build-vs-buy comparison"
         │
         ▼
Approval (CEO/Board for >¥5M; CTO autonomous for <¥5M)
         │
         ▼
Procurement (采购, legal review, 4-8 weeks — can be months in 国企)
         │
         ▼
Implementation (phased rollout, 3-12 months)
```

### 6.2 Buying Committee

| Role | Influence | Concern |
|------|-----------|---------|
| **CTO** | Decision maker (tech) | Architecture fit, integration, team capability |
| **CEO/Founder** | Veto power; often triggers the initiative | Strategic value, competitive advantage, speed |
| **Chief Architect / 架构师** | Key evaluator | Technical depth, API quality, scalability |
| **VP Engineering** | Implementation owner | Team bandwidth, learning curve, maintenance burden |
| **CISO / Security** | Gate-keeper | Compliance, data residency, vulnerability |
| **CFO / Finance** | Budget holder | TCO, payment terms, ROI timeline |
| **Procurement (采购)** | Process owner (esp. large companies/国企) | Vendor qualification, contract terms, 信创 checklist |

### 6.3 Influence Map — By Archetype

| CTO Archetype | Key Influencer to Also Engage |
|---------------|-------------------------------|
| 技术创始人型 | The CTO/Founder IS the decision maker — no one else needed initially |
| 平台架构师 | Chief Architect team — they'll evaluate deeply |
| 信创迁移型 | Procurement + Compliance team — they hold the 信创 checklist |
| AI 布道者 | AI/ML team lead — they'll run the benchmarks |
| 产品技术VP | Product Manager — they define requirements |
| 稳态守护者 | Security team + existing vendor relationship manager |

### 6.4 Budget Patterns

| Company Type | Budget Cycle | Approval Speed | Notes |
|--------------|-------------|----------------|-------|
| Startup (禾观) | Continuous / as-needed | Days–weeks | Founder decides instantly if convinced |
| Scale-up (WeBull, 猎豹) | Quarterly review | 2–4 weeks | CTO has discretionary budget |
| Large private (ByteDance, Shein) | Annual + quarterly adjustment | 4–8 weeks | Multiple approvals, but fast once aligned |
| Listed company (海康, 海尔) | Annual budget + exception process | 6–12 weeks | Board approval for large items |
| Regulated/Exchange (港交所) | Annual with strict governance | 3–6 months | Extensive vendor assessment process |
| SOE / Government-adjacent | Government fiscal year; 政府采购流程 | 6–12 months | Public tender may be required |

### 6.5 Vendor Selection Criteria (Ranked)

1. **Technical fit** — Does it solve the actual problem? Benchmark results.
2. **Integration complexity** — How much engineering effort to deploy?
3. **信创 compliance** — Is it on the approved list? Can it run on 国产 infrastructure?
4. **Team capability** — Can our engineers operate it? Documentation in Chinese?
5. **Vendor viability** — Will this company exist in 3 years? (especially for startups)
6. **Reference customers** — Who else in our industry uses it? (同行案例)
7. **Cost / TCO** — Not just license, but total 3-year cost including operations
8. **Data residency** — Can data stay in China? Separate deployment for global?
9. **Open-source strategy** — Is core open-source? Can we fork if vendor dies?
10. **Support quality** — Chinese-language support? Local team? Response SLA?

---

## §7 Discovery Questions

### 7.1 Opening Questions (Build Rapport + Understand Context)

| # | Question | What You Learn |
|---|----------|----------------|
| 1 | "您现在技术团队的核心架构是什么样的？国产化进展到什么程度了？" | Current stack, 信创 progress, pain points |
| 2 | "您的大模型策略确定了吗？是自建、微调还是调用API？" | AI maturity, budget allocation, build-vs-buy philosophy |
| 3 | "团队现在最大的技术挑战是什么？是人才、架构还是合规？" | Priority ranking, immediate pain |
| 4 | "出海的技术架构和国内是分开的还是统一的？" | Architecture complexity, dual-stack needs |
| 5 | "您在技术选型上，一般看重哪几个维度？" | Decision criteria, values alignment |

### 7.2 Pain-Probing Questions

| # | Question | Pain Point Targeted |
|---|----------|-------------------|
| 6 | "信创迁移过程中，最让您头疼的是哪个环节？性能、兼容性还是人才？" | 信创 pain specifics |
| 7 | "AI项目从POC到生产，您觉得最大的gap在哪里？" | AI deployment maturity |
| 8 | "您团队的AI工程师流失率怎么样？竞争对手挖人多吗？" | Talent pain, urgency |
| 9 | "双十一/大促期间，系统最脆弱的环节在哪里？" | Reliability concerns, scaling limits |
| 10 | "现有的技术债务对新功能开发影响大吗？大概占多少比例的工程资源？" | Tech debt severity |

### 7.3 Decision-Process Questions

| # | Question | What You Learn |
|---|----------|----------------|
| 11 | "这种技术选型，您自己能决定还是需要过会？" | Authority level, buying process |
| 12 | "您一般POC的标准是什么？跑多久算通过？" | Evaluation criteria, timeline |
| 13 | "之前有没有引入过外部技术方案的经验？流程大概多久？" | Historical buying pattern |
| 14 | "今年的技术预算是已经确定了还是还有调整空间？" | Budget availability, timing |
| 15 | "您团队里谁会具体评估技术方案？架构师还是AI团队？" | Key influencer identification |

### 7.4 Vision/Value Questions

| # | Question | What You Learn |
|---|----------|----------------|
| 16 | "三年后您希望技术架构是什么样的？" | Strategic direction, long-term alignment |
| 17 | "您怎么看开源在你们技术栈中的角色？" | Open-source philosophy |
| 18 | "您觉得AI会怎样改变你们的核心业务？" | AI vision, use case clarity |
| 19 | "技术团队的OKR里，今年最重要的是哪一项？" | Priority alignment opportunity |
| 20 | "如果资源不是问题，您最想解决的技术问题是什么？" | Dream state, aspiration |

---

## §8 Communication Style

### 8.1 General Preferences

| Dimension | China CTO Preference |
|-----------|---------------------|
| **Depth** | Deep technical detail welcome — they can handle architecture diagrams, benchmarks, code samples |
| **Language** | Mixed Chinese-English; technical terms often in English (Kubernetes, latency, throughput) |
| **Format** | Architecture diagrams > slides; GitHub repos > brochures; benchmarks > marketing claims |
| **Meeting style** | Prefer 1:1 or small group (CTO + architect); dislike large sales teams |
| **Communication channel** | 微信 (WeChat) for relationship; 飞书/钉钉 for formal; email for documentation |
| **Proof** | "Show me the code" / "Show me the benchmark" — demo over deck |
| **Decision pace** | Fast for small decisions (<¥1M); methodical for large (¥5M+) |
| **Trust building** | Technical credibility first; relationship second; brand third |

### 8.2 Archetype-Specific Communication

| Archetype | Preferred Approach |
|-----------|-------------------|
| **技术创始人型** | Peer-to-peer technical dialogue; respect their depth; don't oversimplify |
| **平台架构师** | Architecture-level conversation; show how you fit in their platform vision |
| **信创迁移型** | Lead with compliance; show certification; offer migration playbook |
| **AI 布道者** | Latest research references; benchmark on their specific use case; GPU efficiency data |
| **产品技术VP** | User experience impact; time-to-market acceleration; A/B test results |
| **稳态守护者** | SLA guarantees; disaster recovery; case studies in regulated industries; zero-downtime migration |

### 8.3 What Works

| ✅ Do | Example |
|-------|---------|
| Lead with technical substance | "Here's our architecture: [diagram]. We process X events/sec at P99 <Y ms" |
| Reference similar companies | "ByteDance's team evaluated us for [use case] and found [result]" |
| Offer hands-on POC | "Give us a test environment and 2 weeks. No commitment" |
| Speak their stack language | Know whether they're on K8s, what cloud, what DB — and speak accordingly |
| Acknowledge build option | "Your team could definitely build this. Here's what we think we add beyond that..." |
| Share technical content | Whitepapers, engineering blog posts, GitHub repos, benchmark reports |
| Be direct about limitations | "We don't support [X] yet. Here's our roadmap" — builds trust |

### 8.4 What Doesn't Work

| ❌ Don't | Why |
|----------|-----|
| Lead with ROI slides before technical proof | They won't trust numbers without understanding the technology |
| Bring a large sales team to first meeting | Feels like a "pitch" not a "conversation" |
| Dismiss open-source alternatives | They know OSS well; dismissing it signals ignorance |
| Ignore 信创 reality | Even if your product isn't affected, showing awareness builds credibility |
| Use generic case studies from US companies | Need China / Asia references; ideally same industry |
| Push urgency without technical justification | "Limited time offer" is insulting to a CTO |
| Overclaim AI capabilities | CTOs will test your claims; hallucination or overstatement destroys credibility permanently |
| Skip the architect | CTO may nod but architect will veto if not technically convinced |

### 8.5 Meeting Cadence Preferences

| Stage | Preferred Format | Duration | Attendees |
|-------|-----------------|----------|-----------|
| Initial exploration | WeChat/飞书 text + async doc sharing | — | Sales Engineer ↔ CTO |
| Technical deep-dive | Video call or in-person | 60–90 min | SE + CTO + Architect |
| POC kickoff | In-person workshop | Half-day | Engineering teams both sides |
| POC review | Video + live demo | 60 min | CTO + team |
| Decision meeting | In-person (for large deals) | 30–60 min | CTO + CFO (if budget) |
| Ongoing | Quarterly business review + monthly tech sync | 30 min / 60 min | Account team ↔ Tech team |

### 8.6 Content That Resonates

| Content Type | Engagement Level | Notes |
|--------------|-----------------|-------|
| Engineering blog post (technical depth) | ⭐⭐⭐⭐⭐ | Best if from actual engineers, not marketing |
| Benchmark report (their workload type) | ⭐⭐⭐⭐⭐ | Must be reproducible |
| Architecture diagram / reference architecture | ⭐⭐⭐⭐⭐ | Visual, specific to their scale |
| Open-source contribution / GitHub activity | ⭐⭐⭐⭐ | Shows engineering culture |
| Case study (same industry, China) | ⭐⭐⭐⭐ | Must be technical, not just quotes |
| Conference talk / video | ⭐⭐⭐ | Good for awareness, not decision-stage |
| Product brochure / feature list | ⭐⭐ | Only useful as reference material |
| Generic ROI calculator | ⭐ | Viewed with skepticism |

---

## Appendix A: Account-Specific CTO Engagement Notes

| Account | CTO Archetype | Key Technical Context | Engagement Angle |
|---------|---------------|----------------------|-----------------|
| **Anker** | 技术创始人型 + 产品技术VP | IoT/smart home; hardware-software integration; ex-Google DNA | Speak firmware+cloud; respect hardware constraints |
| **海康威视** | AI 布道者 + 信创迁移型 | 10K+ engineers; Edge AI; sanctioned → self-reliance | Understand their chip constraints; don't propose NVIDIA-dependent solutions |
| **海尔** | 平台架构师 | COSMOPlat industrial internet; smart manufacturing | Platform-level conversation; industrial IoT vocabulary |
| **理想汽车** | 技术创始人型 | Full-stack AD; 李想 personally involved; dual powertrain | Must pass founder-level scrutiny; autonomous driving specific |
| **Shein** | 平台架构师 + AI 布道者 | Real-time supply chain; recommendation; demand prediction | Scale + speed; global dual-stack architecture |
| **ByteDance** | 平台架构师 + AI 布道者 | Recommendation engine; 豆包 LLM; global infra | Massive scale; they likely already built something similar |
| **禾观** | 技术创始人型 + AI 布道者 | AI search ads; NLP/LLM for e-commerce; small team | Founder-direct; high tech density; fast decisions |
| **Cathay Pacific** | 稳态守护者 | Legacy aviation IT; Amadeus dependency; modernization | Risk-averse; prove stability; phased migration |
| **WeBull** | 产品技术VP + 稳态守护者 | Trading platform; low-latency; regulatory; mobile-first | Performance benchmarks; compliance; mobile UX |
| **港交所 (HKEX)** | 稳态守护者 + 平台架构师 | Orion (ultra-low-latency); FINI; DLT/Synapse | Five-nines; microsecond latency; long procurement cycles |
| **猎豹移动** | AI 布道者 + 产品技术VP | OrionStar robots; ASR/NLU/TTS; LLM integration | Full-stack AI conversation; robotics-specific challenges |
| **腾讯游戏** | 平台架构师 + AI 布道者 | Game engines; AI NPCs; anti-cheat ML; cloud gaming; massive concurrency | Engine-level depth; real-time systems; player experience |

---

## Appendix B: Seasonal Timing Guide

| Period | CTO Behavior | Sales Implication |
|--------|-------------|-------------------|
| **Q1 (Jan–Mar)** | New year budget confirmed; kicking off annual initiatives | Best time to start new evaluations |
| **Pre-618 (Apr–May)** | E-commerce CTOs in freeze mode (Shein, etc.) | Don't propose changes; focus on post-promotion optimization |
| **Summer (Jun–Aug)** | Internship management; lighter meeting load | Good for POCs and technical deep-dives |
| **Pre-双十一 (Sep–Oct)** | Code freeze for e-commerce/consumer tech | System stability priority; sell for post-peak implementation |
| **Q4 (Nov–Dec)** | Budget planning for next year; spending remaining budget | Critical window: get into next year's budget or use this year's surplus |
| **两会 period (Mar)** | Government/SOE cautious; 信创 policy may update | Monitor policy; pause aggressive SOE outreach |

---

## Appendix C: Glossary of Key Terms

| Term | Pinyin | English | Relevance |
|------|--------|---------|-----------|
| 信创 | Xìnchuàng | IT Application Innovation (localization) | Core CTO mandate in regulated sectors |
| 自主可控 | Zìzhǔ kěkòng | Self-reliant and controllable | Technology sovereignty doctrine |
| 大模型 | Dà móxíng | Large Language Model (LLM) | Every CTO's current strategic focus |
| 出海 | Chūhǎi | Going overseas (international expansion) | Drives dual-stack architecture needs |
| 国产云 | Guóchǎn yún | Domestic cloud | Aliyun, Tencent Cloud, Huawei Cloud |
| 等保 | Děngbǎo | Classified Protection (security standard) | Mandatory security certification |
| 高新企业 | Gāoxīn qǐyè | High-tech enterprise (certification) | Tax benefits; requires patent counts |
| 产学研 | Chǎn-xué-yán | Industry-academia-research collaboration | Talent pipeline strategy |
| 算法备案 | Suànfǎ bèi'àn | Algorithm registration | Required for recommendation/AI systems |
| 个保法 | Gè bǎo fǎ | Personal Information Protection Law (PIPL) | China's GDPR equivalent |
| 数据安全法 | Shùjù ānquán fǎ | Data Security Law | Cross-border data transfer rules |
| 防沉迷 | Fáng chénmí | Anti-addiction (gaming) | Technical compliance for game companies |
| 总工程师 | Zǒng gōngchéngshī | Chief Engineer | CTO equivalent title in SOEs |
| 民企 | Mínqǐ | Private enterprise | More agile, founder-driven decisions |
| 国企 | Guóqǐ | State-owned enterprise | Longer cycles, compliance-heavy |

---

*Last updated: 2025-01. Based on 12-account research across hardware, AI, automotive, e-commerce, fintech, gaming, aviation, and exchange sectors in Greater China.*
