# CCO · 首席合规官 — China-Market Persona Reference

| Field | Detail |
|-------|--------|
| **Title variants** | 合规总监, 合规部负责人, 首席合规官 (CCO), 合规副总裁, 总法律顾问兼合规负责人, 风控合规部总经理 |
| **Reports to** | CEO (民企), Board / 合规委员会 (listed), General Counsel (外企), 纪委书记/风控总监 (国企) |
| **Scope** | Regulatory compliance, policy interpretation, internal controls, anti-corruption, data compliance, export controls, algorithm governance, AML/KYC, cross-border regulatory coordination |
| **Direct reports** | Regulatory Affairs, AML/KYC Team, Data Compliance, Internal Audit Liaison, Export Control, Content Compliance, Algorithm Governance |
| **Budget authority** | ¥5M–¥200M+ depending on company size and regulatory intensity; higher in financial services |
| **Buying power** | Direct authority on compliance tools, RegTech platforms, legal advisory; co-decision on enterprise data/IT systems with compliance implications |
| **Persona version** | 1.0 — China-adapted, multi-archetype |
| **Last updated** | 2025-Q4 |

---

> **Reader note.** This document is written to be readable and extractable by AI agents of varying capability — from small open-weights models up to frontier models. Concepts are spelled out explicitly rather than implied; some redundancy across sections is intentional so that any single section remains useful in isolation (e.g. when retrieved on its own). If you are a strong model, skim the key insight inside each block; if you are a weaker model, read the full block. The China CCO role uniquely combines legal compliance, political risk navigation, and personal criminal liability (直接责任人) in ways that have no Western equivalent — compliance here is inseparable from government relations, and the regulatory landscape shifts with policy campaigns (运动式执法) that have no fixed schedule.

> **Data usage instruction for agents.** All company names, executive names, financial figures, and examples in this document are illustrative — they teach you the *pattern* (what this persona cares about, how they talk, how they decide). They are NOT current data to be cited verbatim in customer-facing outputs. When generating any customer-facing deliverable, you MUST verify any peer proof, financial figures, or competitive references against current public sources (earnings calls, press releases, annual reports) before including them. Treat examples here as "this is the *type* of thing to look for" — then go find the latest version.
>
> Data vintage: Examples and figures sourced primarily from FY2024–FY2026 public disclosures and industry research. China-market context reflects policy environment through 15th Five-Year Plan (2026–2030) early signals.

---

## What a CCO Actually Is — China Context

The compliance function in China is **not merely legal risk management** — it is the organizational interface between the company and an unpredictable, politically-driven regulatory state. Understanding this distinction is fundamental to engaging a China CCO:

### Compliance = Political Risk Management (合规 ≠ 法务)

In Western companies, compliance is a subset of legal: follow the rules, avoid fines. In China, compliance is **existential navigation** — the rules change without notice, enforcement is campaign-driven (运动式执法), and the penalty for misjudging regulatory intent can be company destruction (see: 蚂蚁金服 IPO cancellation, 滴滴 delisting). The CCO's job is not just "are we following current rules?" but "which way is the political wind blowing, and are we positioned correctly?"

### Personal Liability — 直接责任人

Under multiple Chinese laws, the CCO (or whoever serves as the designated compliance officer) can be held personally liable — not merely fined, but **criminally prosecuted and imprisoned**:

- 网络安全法 Article 75: Directly responsible persons face fines of ¥10,000–¥100,000 and potential detention
- 数据安全法 Article 45: Up to ¥500,000 personal fine; criminal liability for "serious circumstances"
- 反洗钱法: Personal criminal liability for AML compliance failures in financial institutions
- 出口管制法: Criminal prosecution for export control violations (10+ year sentences possible)
- 证券法: Securities compliance failures carry personal disgorgement + bans

This personal liability transforms the CCO role. A Western CCO worries about corporate fines; a China CCO worries about personal freedom. This creates **extreme risk aversion** in some CCOs and explains why the role has high turnover in high-risk sectors.

### 金融 vs. 科技 vs. 出海 — Three Different CCO Worlds

**Financial Sector (金融合规):** Most mature compliance function in China. Banks, brokers, and insurers have mandatory CCO positions. Regulated by 国家金融监督管理总局 (NFRA, formed 2023 from 银保监会+部分央行职能). WeBull-style multi-jurisdiction broker-dealers face the most complex compliance matrix (SEC + CSRC + MAS + local regulators simultaneously).

**Technology Sector (科技合规):** Newer, less formalized. Emerged rapidly post-2021 when 反垄断 crackdown, algorithm governance regulations, and data protection laws all landed simultaneously. ByteDance-style companies went from "move fast, break things" to building 500+ person compliance teams in 18 months. The CCO here is often elevated from Legal or Public Affairs.

**出海 (Going-Global) Companies:** Simultaneous compliance with Chinese laws AND foreign jurisdiction requirements. Shein must satisfy GDPR + PIPL + CPRA + product safety regulations across 150+ markets. 海康威视 must manage US Entity List restrictions while maintaining China export control compliance. These CCOs need genuine multi-jurisdictional expertise.

### The Regulatory Landscape — 监管格局

| Regulator | Abbreviation | Domain | CCO Touchpoints |
|-----------|-------------|--------|-----------------|
| 国家互联网信息办公室 | CAC/网信办 | Internet content, data, algorithms | 算法备案, data transfer assessments, content rules |
| 国家金融监督管理总局 | NFRA/金监总局 | Banking, insurance, non-bank finance | Capital adequacy, consumer protection, AML |
| 中国证监会 | CSRC | Securities, futures | Disclosure, insider trading, listing compliance |
| 国家市场监督管理总局 | SAMR/市监总局 | Antitrust, product safety, advertising | 反垄断, unfair competition, false advertising |
| 商务部 | MOFCOM | Export control, foreign investment | 出口管制, unreliable entity list, technology transfer |
| 公安部 | MPS | Cybersecurity enforcement, data crimes | 等保 enforcement, cybercrime investigation |
| 国家保密局 | — | State secrets | 涉密信息系统 for SOEs / defense-adjacent |
| 各地方监管 | — | Local enforcement of national laws | Province/city-level interpretations and campaigns |

**Key insight:** Unlike Western compliance where rules are clear and enforcement is consistent, China's regulatory system features **overlapping jurisdictions**, **campaign-style enforcement** (突击检查, 专项整治), and **regulatory signaling** (领导讲话, 行业座谈会) that the CCO must interpret before formal rules are published.

---

## §1 Role Definition

### 1.1 Six CCO Archetypes

| Archetype | Description | Example Pattern |
|-----------|-------------|-----------------|
| **金融合规型 (Financial Compliance)** | Mature compliance function in regulated financial institution; AML/KYC, investor protection, capital adequacy; multiple licenses to maintain | WeBull (multi-jurisdiction broker), 港交所 (exchange operator + regulator), bank/insurance compliance |
| **数据合规型 (Data & Privacy)** | Emerged post-2021; focused on 三法合规 (网络安全法+数据安全法+个保法); cross-border data transfer; consent management | ByteDance (algorithm + data), Shein (multi-market consumer data), Cathay Pacific (passenger data governance) |
| **出口管制型 (Export Control & Sanctions)** | Managing Entity List consequences, dual-use technology restrictions, China's own export control law compliance | 海康威视 (Entity List since 2019), semiconductor companies, AI chip companies under US restrictions |
| **出海多法域型 (Multi-Jurisdiction 出海)** | Simultaneous compliance with China + 2–5 foreign jurisdictions; SEC/GDPR/MAS/etc. | WeBull (SEC+CSRC+MAS), Shein (EU+US+PIPL), ByteDance/TikTok (global content + data) |
| **平台治理型 (Platform Governance)** | Content moderation, algorithm governance, 算法备案, anti-monopoly platform rules | ByteDance (content + algorithm), e-commerce platforms, social media companies post-2021 |
| **产业合规型 (Industry/Safety Compliance)** | Product safety, supply chain labor standards, environmental compliance, aviation safety, manufacturing standards | Shein (supply chain labor + product safety), Cathay Pacific (aviation safety + data), manufacturing exporters |

### 1.2 Diagnostic Table — Identifying the Archetype

| Signal | Likely Archetype |
|--------|-----------------|
| Company holds financial licenses (券商/银行/保险/基金) | 金融合规型 |
| Recent CAC enforcement or data-related fine | 数据合规型 |
| Company on US Entity List or facing export restrictions | 出口管制型 |
| Company listed on US exchange AND operates from China | 出海多法域型 |
| Company is a platform with UGC or algorithmic recommendation | 平台治理型 |
| Company manufactures / has supply chain controversies | 产业合规型 |
| Company recently fined by SAMR for 反垄断 | Blend: 平台治理型 + political navigation |
| Multiple signals present | Blend — lead with dominant, acknowledge secondary |

### 1.3 Three Time Horizons

| Horizon | Timeframe | Focus | Example |
|---------|-----------|-------|---------|
| **H1: Survive current cycle** | 0–6 months | Respond to active enforcement campaigns; pass upcoming audits; address regulatory inquiries; maintain licenses | WeBull preparing for CSRC inspection cycle; ByteDance filing quarterly 算法备案 updates |
| **H2: Build compliance infrastructure** | 6–18 months | Deploy RegTech/合规科技 systems; formalize policies; train workforce; establish regulator relationships; remediate gaps | Shein building global product safety database; 海康威视 establishing export control classification system |
| **H3: Compliance as strategic advantage** | 18–36 months | Proactive regulatory engagement (参与立法); compliance-enabled market entry; certifications as competitive moat; industry standard-setting | 港交所 shaping ESG disclosure rules it will enforce; ByteDance turning algorithm transparency into a trust differentiator |

### 1.4 Four-Way Pull

The China CCO is pulled in four directions simultaneously:

```
                    Regulators / 监管
                    "反垄断罚单来了"
                    "CAC约谈了"
                    "算法备案要更新"
                         │
                         ▼
    Business ◄────── CCO ──────► Legal / 法务
    "合规流程太慢了"       │        "这个规定还没细则"
    "竞争对手都在做"      │        "法律风险可控"
    "错过窗口期了"        │        "需要外部律所意见"
                         │
                         ▼
                  Board / Investors
                  "IPO合规Ready吗?"
                  "ESG评分怎么样?"
                  "上次罚款怎么回事?"
```

**Regulatory Pull** — The most powerful and unpredictable force. When CAC 约谈 (summons for a "talk"), everything else stops. When a 专项整治 (special rectification campaign) launches, the CCO has days to respond, not months. Regulatory pull is amplified by personal liability — the CCO's personal freedom is at stake.

**Business Pull** — Revenue teams see compliance as friction. "Competitors are already doing this" (竞争对手都在做) is the most common pressure phrase. Product launches delayed by compliance review create tension with CEO/founder. The business frames compliance cost (合规成本) as pure overhead.

**Legal Pull** — The General Counsel and external law firms often provide conservative interpretations that conflict with business speed. But law is written in ambiguity (模糊地带) in China — the CCO must decide how to interpret gray areas when legal counsel says "it's unclear."

**Board/Investor Pull** — Particularly acute for listed companies and IPO-track companies. Investors demand compliance maturity (SOC2, ISO certifications), ESG scores, and zero regulatory incidents — while also demanding revenue growth that often creates compliance tensions.

### 1.5 合规成本 vs. 违规成本 Framework

The CCO's most important internal persuasion tool:

| Category | 合规成本 (Compliance Cost) | 违规成本 (Non-Compliance Cost) |
|----------|--------------------------|-------------------------------|
| **Direct financial** | Team headcount, tools, advisors: ¥10M–¥100M/year | Fines: ¥1M–¥8B+ (反垄断); ¥100M+ (data violations) |
| **Operational** | Process delays: weeks per approval | Business suspension: months/years (滴滴 2-year app ban) |
| **Strategic** | Market entry delayed | Market access revoked (licenses cancelled) |
| **Reputational** | — | Brand damage, customer trust collapse (Cathay Pacific breach) |
| **Personal** | Career opportunity cost | Criminal prosecution, detention, industry bans |
| **Capital markets** | IPO preparation costs | IPO blocked (蚂蚁金服), forced delisting (滴滴 from NYSE) |

**Ratio the CCO uses internally:** "Our annual compliance budget is ¥50M. The 阿里 antitrust fine was ¥18.2B. That's 364 years of compliance budget in one fine."

---

## §2 Strategic Priorities

### Priority 1: 三法合规 (Three-Law Data Compliance Trinity)

The foundational data compliance framework since 2021:

| Law | Effective | Core Requirements | CCO Actions |
|-----|-----------|-------------------|-------------|
| **网络安全法** | June 2017 | Network security obligations; data localization for CIIOs; incident reporting | Designate 安全责任人; implement 等保; report incidents within 24hrs |
| **数据安全法** | Sept 2021 | Data classification (一般/重要/核心); important data catalog; cross-border restrictions | Build data asset inventory; classify all data; restrict important data export |
| **个人信息保护法 (PIPL)** | Nov 2021 | Consent-based processing; data minimization; DPO appointment; cross-border transfer mechanism | Consent management platform; privacy impact assessments; transfer mechanism selection |

**Cross-border data transfer — the CCO's biggest operational headache:**

Three mechanisms available (must choose one per data flow):
1. **CAC安全评估 (Security Assessment)** — Mandatory for CIIOs or >1M persons' data; takes 6–12 months; valid 2 years
2. **标准合同 (Standard Contractual Clauses)** — File with local CAC office; simpler but limited scenarios
3. **认证 (Certification)** — Third-party certification per CAC standards; least used

**Practical pain:** A company like Shein processing data from 150+ countries, with supply chain data flowing between China factories and global logistics, must map every cross-border data flow and select appropriate mechanisms. Missing one flow = violation.

### Priority 2: 反垄断/反不正当竞争 (Antitrust & Unfair Competition)

Post-2021 antitrust enforcement transformed CCO priorities for all platform/tech companies:

| Enforcement Wave | Key Cases | CCO Learning |
|-----------------|-----------|--------------|
| 2021 Platform Economy | 阿里 ¥18.2B, 美团 ¥3.4B | "二选一" (exclusive dealing) is fatal; preemptive self-correction required |
| 2021–2022 M&A | Multiple retroactive gun-jumping fines | Report ALL acquisitions including VIE restructuring |
| 2022–2023 Data-related | 滴滴 ¥8B+, 知网 ¥ 8.8M | Data-as-market-power is a competition concept; data compliance = antitrust compliance |
| 2024+ "常态化监管" | Lower fines but broader reach | "Normalized regulation" — every company, not just giants |

**CCO antitrust compliance program requirements:**
- Competition compliance training for all business teams (annual, documented)
- Merger filing review process (assess EVERY investment, even minority stakes)
- 算法合规 — algorithmic pricing must not constitute price-fixing
- Data interoperability requirements (platform must not block competitors)
- Self-assessment program with annual compliance report to board

### Priority 3: 出口管制 (Export Control Compliance)

Dual-dimensional challenge — China's own export control law (2020) AND foreign export control compliance:

**China's Export Control Law (出口管制法, effective Dec 2020):**

| Element | Requirement | CCO Implication |
|---------|-------------|-----------------|
| 管制物项 | Items on control list + catch-all provision | Must screen ALL exports against evolving control lists |
| 最终用户/最终用途 | End-user and end-use verification | Know-your-customer for export transactions |
| 出口经营者 | Establish internal compliance program (内部合规制度) | Formal compliance system is mandatory for exporters |
| 域外适用 | Extraterritorial application possible | China can penalize foreign entities assisting circumvention |

**US Export Control (Entity List / EAR / CHIPS Act):**
- 海康威视 pattern: Added to Entity List 2019; must ensure NO US-origin components above de minimis threshold in products
- Compliance architecture: Dual product lines (US-component vs. US-free), supplier audits, technology origin tracking
- Penalty: US secondary sanctions can cut off from global financial system

**The CCO's export control matrix:**
```
                     Exporting FROM China         Importing INTO China
                     ─────────────────────        ────────────────────
China Law:           出口管制法 control list       反制裁法 (retaliation)
                     End-user verification         不可靠实体清单 compliance
                     
US Law:              EAR de minimis rule           Entity List restrictions
                     Direct product rule           FDPR (Foreign Direct Product Rule)
                     
EU Law:              EU dual-use regulation        EU sanctions compliance
                     Human rights due diligence    End-use certificates
```

### Priority 4: 算法备案与治理 (Algorithm Registration & Governance)

Unique to China — no Western equivalent at this regulatory maturity:

**算法推荐管理规定 (Algorithm Recommendation Regulations, effective March 2022):**
- All algorithmic recommendation services must register with CAC (算法备案)
- Must provide opt-out mechanism for users
- Must not use algorithms to engage in price discrimination (大数据杀熟)
- Must not use algorithms to harm worker rights (外卖配送算法)
- Must label algorithmically-generated content

**生成式AI管理暂行办法 (Interim Measures for Generative AI, effective Aug 2023):**
- Must register AI services; undergo security assessment before public launch
- Training data compliance (no IP infringement, no illegal content)
- Generated content must not subvert state power or promote separatism
- Must implement content filtering and review mechanisms

**CCO responsibilities:**
- Maintain 算法备案 registrations (quarterly updates when algorithm changes materially)
- Algorithm fairness audits (ensure no 大数据杀熟 patterns)
- AI content compliance review process
- Algorithm transparency reporting to regulators
- ByteDance pattern: 500+ content compliance staff; algorithm governance committee; regular CAC reporting

### Priority 5: AML/KYC & Financial Compliance (金融合规)

For financial sector CCOs (WeBull, 港交所, banks, payment platforms):

| Requirement | Standard | CCO System |
|-------------|----------|------------|
| 反洗钱 (AML) | 反洗钱法 + PBOC rules; FATF standards | Transaction monitoring, STR filing, customer due diligence |
| KYC/CDD | Enhanced for PEPs, high-risk customers | Tiered verification; ongoing monitoring; beneficial ownership |
| 反恐怖融资 | Counter-terrorism financing regulations | Sanctions screening; name matching; frozen assets compliance |
| 投资者适当性 | Suitability/appropriateness requirements | Product risk-rating; investor risk-profiling; suitability matching |
| 信息隔离墙 | Chinese wall requirements | System access controls; deal-team information barriers |

**Multi-jurisdiction financial compliance (WeBull pattern):**

```
US (SEC/FINRA)          China (CSRC/PBOC)       Singapore (MAS)
──────────────          ─────────────────        ───────────────
Reg SHO                 科创板交易规则            SFA compliance
AML/BSA                 反洗钱法                  CDSA/AML
Reg NMS                 融资融券管理办法          Securities & Futures Act
FINRA conduct rules     投资者适当性管理          MAS Notice on AML
SOX 404                 证券法信息披露            SGX listing rules

        ↓                       ↓                       ↓
        └───────────── ONE CCO team ─────────────────────┘
```

**港交所 unique position:** Acts as BOTH a commercial listed company AND a front-line regulator:
- As company: must comply with SFC oversight, listing rules as an issuer
- As regulator: enforces listing rules on ~2,600 listed companies
- CCO must manage inherent conflict of interest (commercial revenue vs. regulatory duty)
- Example: approving IPO applications (revenue-generating) while enforcing listing standards (revenue-restricting)

### Priority 6: 合规科技/RegTech (Compliance Technology)

The CCO's technology stack and emerging tools:

| Category | Function | China Market Leaders |
|----------|----------|---------------------|
| **AML Transaction Monitoring** | Screen transactions for suspicious patterns | 同盾科技, 百融云创, NICE Actimize (外资) |
| **KYC/Identity Verification** | Verify customer identity; facial recognition | 旷视科技, 商汤, 百融云创 |
| **Regulatory Change Management** | Track regulatory updates; assess impact | 威科先行 (Wolters Kluwer CN), 法大大, custom-built |
| **Data Compliance Platform** | Data mapping, consent management, DPIA | 安恒信息, 数据宝, 奇安信 data compliance module |
| **Contract Compliance** | Contract review for compliance clauses | 法大大, 上上签, AI-powered review tools |
| **Export Control Screening** | Screen parties against control lists | 中国出口管制信息网 + custom systems; Dow Jones (外资) |
| **Algorithm Audit** | Fairness testing; bias detection; 备案 support | Internal tools + academic partnerships; emerging market |
| **ESG Compliance Reporting** | Track ESG metrics; generate disclosures | 妙盈科技, 商道融绿, Wind ESG |

**CCO technology buying criteria:**
1. **本地化 (Localization)** — Must handle Chinese regulatory text, GB standards, Chinese names
2. **监管对接 (Regulatory Interface)** — Can it generate reports in regulator-required formats?
3. **数据安全 (Data Security)** — Compliance tools hold sensitive data; must not create new compliance risk
4. **跨境能力 (Cross-border)** — For 出海 companies: can it handle multi-jurisdiction simultaneously?
5. **AI能力 (AI Capability)** — Can it parse regulatory updates automatically? Predict enforcement trends?

---

## §3 Key Performance Indicators

### 3.1 Compliance Operations KPIs

| KPI | Target Range | Context |
|-----|-------------|---------|
| Regulatory inquiries responded on-time | 100% | Late response to 约谈 or investigation request = escalation |
| License/permit renewal success rate | 100% | Lapsed license = business interruption |
| Policy update response time | <72 hours for new regulation assessment | Time from publication to internal impact assessment |
| Training completion rate | >95% annually | Documented training is audited; gaps = personal liability |
| Internal compliance hotline reports resolved | >90% within 30 days | 举报 (whistleblower) channel effectiveness |
| Third-party compliance assessment pass rate | >95% | External audit results reported to board |
| Cross-border data transfer approval backlog | <30 days average | Business teams waiting = revenue delay = pressure |
| Regulatory fine amount (annual) | Zero (target); track trend | Any fine triggers board-level review |

### 3.2 Risk Management KPIs

| KPI | Target | Context |
|-----|--------|---------|
| Compliance risk incidents (material) | 0 per year | Any material incident = CCO career impact |
| Near-miss identification rate | Increasing trend | Shows proactive detection capability |
| Regulatory change coverage | 100% of applicable new regulations assessed | No surprises when enforcement begins |
| Compliance audit findings (repeat) | 0 repeat findings | Repeat findings indicate systemic failure |
| Employee compliance violations | Decreasing trend; 100% actioned | Show culture improvement; zero tolerance for serious violations |
| Export control screening hit rate / false positive | <5% false positive | Too many false positives = business friction = workarounds |
| Algorithm compliance audit frequency | Quarterly minimum | 算法备案 requires demonstrable ongoing governance |

### 3.3 Strategic/Business-Linked KPIs

| KPI | Connection |
|-----|-----------|
| IPO-readiness compliance score | Direct prerequisite for listing (Shein pattern) |
| Time from regulation publication to product compliance | Speed-to-market for regulated products/features |
| Compliance-enabled market entry (new licenses obtained) | Revenue enablement |
| Regulatory relationship quality (subjective, board-assessed) | Early warning access; favorable interpretation |
| ESG rating improvement | Investor attraction; index inclusion |
| Compliance cost as % of revenue | Efficiency metric; benchmark against peers |
| Regulatory examination outcomes (vs. peers) | Relative positioning signals regulator perception |
| Customer compliance questionnaire response time | Sales cycle support |

---

## §4 Decision-Making Framework

### 4.1 How the CCO Evaluates Compliance Investments

```
┌─────────────────────────────────────────────────────────┐
│              CCO Investment Decision Matrix               │
├──────────────────────┬──────────────────────────────────┤
│  REGULATORY MANDATE  │  HIGH: Must do. Budget secondary. │
│  (监管硬性要求)       │  Timeline = regulator's deadline  │
├──────────────────────┼──────────────────────────────────┤
│  ENFORCEMENT SIGNAL  │  MEDIUM-HIGH: Anticipatory spend  │
│  (执法信号/座谈会)    │  "They talked about it, so it's   │
│                      │   coming. Better prepared early."  │
├──────────────────────┼──────────────────────────────────┤
│  INDUSTRY BEST       │  MEDIUM: Competitive + risk        │
│  PRACTICE (行业惯例)  │  "If peers have it and we don't,  │
│                      │   we're the soft target."          │
├──────────────────────┼──────────────────────────────────┤
│  EFFICIENCY /        │  LOW-MEDIUM: ROI-driven           │
│  OPTIMIZATION (降本) │  "Saves headcount or time but      │
│                      │   not mandatory."                  │
└──────────────────────┴──────────────────────────────────┘
```

### 4.2 The CCO's Unique Decision Calculus

Unlike other CxOs who optimize for revenue or efficiency, the CCO optimizes for **risk-adjusted survival**:

**Question 1: "如果出事了，我会坐牢吗？" (If something goes wrong, will I go to prison?)**
- If yes → non-negotiable investment regardless of cost
- This is not hypothetical — compliance officers have been detained in China

**Question 2: "监管下一步会查什么？" (What will regulators check next?)**
- The CCO reads 领导讲话 (leadership speeches), 行业座谈会 (industry roundtables), 征求意见稿 (draft regulations) as **leading indicators**
- Spending against predicted enforcement > spending against current rules

**Question 3: "同行怎么做的？" (What are peers doing?)**
- If industry peers have invested and you haven't, you're the enforcement target
- 木秀于林 (tall poppy) works in reverse for compliance — laggards get cut

**Question 4: "这个能帮我拿到什么？" (What can this get me?)**
- Compliance as market access enabler (new license, new market, IPO qualification)
- CCO reframes compliance spend as revenue-enabling to get CEO buy-in

### 4.3 Vendor Evaluation Criteria

When the CCO evaluates compliance technology or advisory services:

| Criterion | Weight | Rationale |
|-----------|--------|-----------|
| Regulatory acceptance/recognition | 30% | "Will regulators accept this tool's output as compliant?" |
| Reference customers in same sector | 25% | "If my peer uses it and passed inspection, that's my evidence" |
| Local support & customization | 20% | "Can you respond when CAC gives us 72 hours to comply?" |
| Integration with existing systems | 15% | Data mapping tools must connect to actual data infrastructure |
| Cost | 10% | Least important — "合规无价" (compliance is priceless) when liability is personal |

### 4.4 Deal Breakers — What Kills a Vendor Engagement

- **Data sovereignty violation:** Compliance tool stores data offshore without proper mechanism → immediate rejection
- **No Chinese regulatory content:** Tool only covers GDPR/SOX but not Chinese regulations → not fit for purpose
- **No local entity/support:** Vendor has no China presence → cannot respond to regulatory urgency
- **Customer reference in same regulatory regime:** If no one in China financial services uses it, the financial CCO won't be first
- **Vendor's own compliance posture:** "If you can't demonstrate your own compliance, how do you help mine?"

---

## §5 Communication & Influence Patterns

### 5.1 Language and Framing

The China CCO speaks a specific dialect that blends legal, political, and business language:

| Context | CCO Language Pattern | Translation for Sales |
|---------|---------------------|----------------------|
| Regulatory urgency | "这是硬性要求，没有商量余地" (Hard requirement, non-negotiable) | Budget is available; close fast |
| Anticipatory compliance | "征求意见稿已经出了，正式稿随时发布" (Draft published, final imminent) | Window of opportunity before enforcement |
| Risk framing | "违规成本是合规成本的百倍" (Non-compliance costs 100x compliance) | Use this language back to them; it works on their CEO |
| Personal liability | "直接责任人制度下，这是我的个人风险" (Under personal liability rules, this is my personal risk) | Extremely motivated buyer; empathize with personal stakes |
| Political reading | "最近的座谈会信号很明确" (Recent roundtable signals are clear) | CCO is acting on anticipated enforcement, not published rules |
| Budget justification | "合规是底线，不是成本中心" (Compliance is the floor, not a cost center) | They need help reframing to CEO in business terms |

### 5.2 What the CCO Says to the Board

```
Board reporting structure (typical quarterly):

1. 监管环境更新 (Regulatory landscape update)
   - New regulations published / expected
   - Enforcement actions in industry
   - Regulatory relationship status

2. 合规指标 (Compliance metrics)
   - Training completion, audit results, incidents
   - License status, certification updates

3. 重大风险事项 (Material risk items)
   - Ongoing investigations or inquiries
   - Identified gaps with remediation timeline
   - Personal liability exposure assessment

4. 资源请求 (Resource requests)
   - Headcount, budget, tools
   - Always framed as: "This investment vs. this risk"
```

### 5.3 Interaction Map — Who the CCO Influences

| Stakeholder | CCO's Relationship | Interaction Pattern |
|-------------|-------------------|---------------------|
| **CEO/Founder** | Risk advisor; sometimes seen as "brake pedal" | Monthly 1:1; escalation on red-flag issues; must demonstrate business enablement not just risk blocking |
| **CFO** | Budget counterpart; aligned on risk | CCO provides risk quantification; CFO provides budget; alliance on "cost of non-compliance" narrative |
| **CTO/CPO** | Tension point; product vs. compliance speed | Compliance review gates in product development; negotiation on timelines; "compliance by design" advocacy |
| **CISO** | Close partner; overlapping in data/cyber | Shared ownership of 三法合规; CISO handles technical; CCO handles regulatory interface |
| **GC / 总法律顾问** | Reporting line or peer; legal interpretation source | GC provides legal opinion; CCO makes practical compliance decision; GC is conservative, CCO is practical |
| **External regulators** | The most critical relationship | Regular reporting; proactive engagement; 座谈会 participation; relationship maintenance |
| **Board / 审计委员会** | Accountability line | Quarterly reporting; risk escalation; independence protection |
| **HR** | Compliance training and culture partner | Training programs, compliance incentives, disciplinary actions |

### 5.4 Political Navigation Skills

The CCO in China must possess political reading ability (政治嗅觉) that has no Western equivalent:

**Signals the CCO monitors:**
- 新华社/人民日报 editorials mentioning industry sectors (tone = enforcement intent)
- 国务院常务会议 agenda items (State Council signals priority)
- 行业座谈会 invitations (being invited = you're noticed; topic = coming enforcement)
- Peer company enforcement actions (sector-wide or targeted?)
- 两会 (NPC/CPPCC sessions) proposals related to industry
- 领导批示 (leadership instructions) — often circulated informally

**CCO response patterns:**
- Signal detected → Internal assessment within 48 hours
- Assessment complete → Preemptive remediation or position paper
- Enforcement begins in sector → Demonstrate proactive compliance (evidence you moved BEFORE enforcement)
- The goal: **never be surprised** by regulatory action

---

## §6 Challenges & Pain Points

### 6.1 Structural Challenges

| Challenge | Description | CCO Response |
|-----------|-------------|--------------|
| **法规模糊性 (Regulatory ambiguity)** | Chinese laws are intentionally broad; detailed implementation rules come later (or never) | Must make compliance decisions in gray areas; "reasonable interpretation" based on regulatory signals |
| **运动式执法 (Campaign-style enforcement)** | Enforcement comes in waves, often triggered by political events; unpredictable timing | Maintain "always audit-ready" posture; continuous compliance not point-in-time |
| **多头监管 (Multi-regulator overlap)** | Multiple regulators claim jurisdiction over same activity; conflicting requirements possible | Relationship with ALL relevant regulators; prepare for most conservative interpretation |
| **合规人才稀缺 (Talent shortage)** | China CCO talent pool is shallow; especially for algorithm governance, export control | Over-invest in training; partner with academic institutions; higher compensation |
| **业务抵触 (Business resistance)** | Product/sales teams see compliance as blocker; founder may override CCO | Frame in business terms; demonstrate "compliance enabled this revenue"; build CEO trust |
| **国际标准冲突 (International standard conflicts)** | China requirements may conflict with GDPR, US rules (forced data disclosure vs. privacy) | Separate compliance stacks per jurisdiction; "legal conflict" defense documentation |

### 6.2 Sector-Specific Pain Points

**Financial Services CCO:**
- 一行三会 restructuring → 金监总局: Must rebuild ALL regulatory relationships
- Rapidly changing capital market rules (注册制 reform, 科创板 rules)
- Crypto/digital asset gray areas (blanket ban but enforcement edges unclear)
- Cross-border securities regulation (VIE structures under scrutiny)

**Technology Platform CCO:**
- 算法 governance is new; few precedents; regulators still learning too
- Content compliance at scale (millions of UGC posts/day)
- Generative AI compliance — rules are being written in real-time
- Minor protection (未成年人保护) — enhanced requirements for platforms

**出海 Company CCO:**
- US-China tensions create impossible compliance conflicts (e.g., China's 反制裁法 says don't comply with US sanctions; US says you must)
- IPO compliance readiness while managing daily operations (Shein pattern)
- Supply chain compliance across 3+ jurisdictions simultaneously
- Investor due diligence requirements growing more intrusive

**Manufacturing/Export CCO:**
- Entity List compliance requires full supply chain visibility (expensive)
- Dual-use classification is subjective — same product may or may not require license
- China's 不可靠实体清单 (Unreliable Entity List) creates retaliation risk
- Product safety standards differ by market (CE vs. CCC vs. UL)

### 6.3 The CCO's Worst Nightmares (By Archetype)

| Archetype | Nightmare Scenario | Real-World Precedent |
|-----------|-------------------|---------------------|
| 金融合规型 | AML failure leading to license revocation | Multiple small brokers lost licenses 2022–2024 |
| 数据合规型 | Unauthorized cross-border data transfer discovered by CAC | 滴滴: ¥8B+ fine, app banned for 2 years, personal liability for executives |
| 出口管制型 | US designates company on Entity List; or China enforcement for dual-use violation | 海康威视 Entity List 2019; multiple semiconductor companies since 2022 |
| 出海多法域型 | Forced to choose between China law and foreign law (impossible compliance) | TikTok facing simultaneous "give US data access" and "don't transfer data" demands |
| 平台治理型 | Algorithm causes viral harmful content; regulators hold CCO personally liable | Multiple platforms fined for content failures; 未成年人 content incidents |
| 产业合规型 | Supply chain labor violation exposed internationally before IPO | Shein facing labor practice allegations; multiple companies during IPO roadshow |

---

## §7 Buying Behavior & Engagement Model

### 7.1 Budget Cycle

| Quarter | Focus | Buying Behavior |
|---------|-------|-----------------|
| **Q1** | Annual compliance plan approval; regulatory landscape assessment | Large strategic purchases (RegTech platforms, advisory retainers) |
| **Q2** | Mid-year audit preparation; 护网 related (if CISO overlap) | Tactical tools; consulting for specific compliance gaps |
| **Q3** | Regulatory inspection season; half-year compliance reporting | Remediation purchases (post-audit findings); urgent advisory |
| **Q4** | Next-year budget planning; compliance review | Budget commitment for next year; multi-year contracts |

**Unplanned spending triggers:**
- New regulation published with compliance deadline → immediate budget allocation
- Peer company fined/sanctioned → "Could this happen to us?" emergency assessment
- CAC/regulator 约谈 → Whatever it costs to remediate, authorized immediately
- IPO timeline set → Compliance readiness budget unlocked (often ¥10M–¥50M+)
- International expansion decision → Multi-jurisdiction compliance buildout

### 7.2 What the CCO Buys

| Category | Examples | Budget Range | Decision Speed |
|----------|----------|-------------|----------------|
| **Legal/regulatory advisory** | Law firm retainers, regulatory specialists | ¥2M–¥20M/year | Fast (relationship-based) |
| **RegTech platforms** | AML monitoring, data compliance, regulatory change management | ¥5M–¥50M | Medium (6–12 month evaluation) |
| **Compliance training** | E-learning platforms, in-person training, certification programs | ¥500K–¥5M | Fast |
| **Audit & certification** | SOC2, ISO27001, ESG ratings, product certifications | ¥1M–¥10M | Medium |
| **Consulting** | Big 4 compliance advisory, specialist firms, regulatory strategy | ¥3M–¥30M | Varies by urgency |
| **Export control tools** | Screening platforms, classification databases, trade compliance | ¥2M–¥10M | Medium |
| **Data compliance infrastructure** | Consent management, data mapping, DPIA tools | ¥5M–¥30M | Medium-slow (IT integration) |

### 7.3 Engagement Playbook for Vendors

**DO:**
- Lead with regulatory requirement (which law/rule does your solution address?)
- Show reference customers in same regulatory regime
- Demonstrate regulator acceptance/recognition of your approach
- Quantify 违规成本 that your solution prevents
- Understand and reference the specific archetype's pain points
- Offer rapid deployment — compliance deadlines are real

**DON'T:**
- Lead with technology features (CCO cares about compliance outcomes, not tech specs)
- Compare to Western-only solutions without China contextualization
- Dismiss personal liability concerns as "unlikely" — it's existential for them
- Promise "full compliance" — experienced CCOs know this is impossible to guarantee
- Ignore the political dimension of compliance decisions
- Push multi-year contracts without regulatory change flexibility

**Engagement sequence:**
1. **Initial hook:** "We help [specific archetype] companies address [specific regulation] requirement"
2. **Credibility:** "Here's how [peer company in same sector] achieved compliance using our approach"
3. **Risk framing:** "Without this, the exposure under [specific law Article X] is [fine range + personal liability]"
4. **Speed:** "We can have you compliant before the [specific deadline] enforcement date"
5. **Expansion:** Once initial compliance win demonstrated, expand to adjacent compliance areas

---

## §8 Organizational Positioning

### 8.1 Team Structure (Typical Large Enterprise)

```
                         CCO / 合规总监
                              │
         ┌──────────┬────────┼────────┬──────────┬──────────┐
         │          │        │        │          │          │
    监管事务     数据合规   反洗钱    出口管制   内容合规    合规科技
    Regulatory  Data      AML/     Export    Content    RegTech/
    Affairs    Compliance  KYC     Control   Compliance  Systems
    (5-15)     (10-30)   (10-50)  (3-10)   (50-500+)  (5-15)
         │
    Regional compliance officers (if multi-location)
```

**Note on Content Compliance (内容合规):** For platform companies like ByteDance, the content compliance team can be the LARGEST team — hundreds of moderators, AI-assisted review, 24/7 operations. This may report to CCO or have its own VP-level leader.

### 8.2 CCO Reporting Line Variations

| Company Type | Reporting Line | Rationale |
|-------------|----------------|-----------|
| Listed financial institution | Board 合规委员会 (Compliance Committee) | Regulatory requirement for independence |
| Internet/tech company | CEO or COO directly | Elevates compliance voice; post-2021 urgency |
| SOE | 纪委书记 (Discipline Secretary) or Board | Party governance integration |
| 外企 China operations | Regional GC or Global CCO | Matrix structure; dual reporting |
| Pre-IPO company | CEO + Board (dotted to lead underwriter) | IPO readiness demands direct access |
| Early-stage startup | No dedicated CCO; Legal/Finance wears the hat | Cannot afford dedicated function yet |

### 8.3 CCO's Relationship with the Board

**What boards expect from the CCO:**
- No surprises (zero tolerance for "we didn't know")
- Quarterly compliance posture reporting
- Clear risk-rated escalation framework
- Recommendation on compliance investments (not just problem identification)
- Relationship quality with regulators (subjective but critical)

**What CCOs need from the board:**
- Authority to block non-compliant business activities
- Budget commensurate with regulatory burden
- Protection from business pressure to "just approve it"
- Clear escalation pathway when CEO/founder overrides compliance advice
- Board-level championship when investing in proactive compliance

---

## §9 Industry-Specific Deep Dives

### 9.1 WeBull Pattern — Multi-Jurisdiction Broker-Dealer

**Context:** Chinese-origin fintech operating as broker-dealer in US (SEC/FINRA), China (CSRC), and Singapore (MAS). Completed SPAC listing.

**CCO complexity factors:**
- Must maintain FINRA-registered CCO in US (personal qualification requirements)
- CSRC compliance for any China-directed activities
- MAS licensing compliance in Singapore
- AML/KYC across three jurisdictions with different standards
- SPAC listing created additional disclosure compliance requirements
- Customer data flows between jurisdictions require multi-regime data compliance

**CCO operating model:**
- Three jurisdiction-specific compliance leads reporting to global CCO
- Unified compliance technology platform with jurisdiction-specific rule engines
- "Highest common denominator" approach where possible (apply strictest standard globally)
- Separate data environments per jurisdiction (no China customer data to US systems)

### 9.2 港交所 Pattern — Dual Role (Regulator + Commercial)

**Context:** Hong Kong Exchanges and Clearing Limited is a commercial listed entity that simultaneously functions as a front-line securities regulator.

**CCO unique challenges:**
- Managing inherent conflict between commercial interests (IPO fees, trading volume) and regulatory duty (listing standards enforcement)
- SFC oversight of exchange's regulatory function
- Must comply with HK law while facilitating mainland companies' listings (understanding both systems)
- 互联互通 (Stock Connect, Bond Connect) requires compliance with both HK and mainland rules
- ESG disclosure requirements that 港交所 both develops and enforces

**CCO operating model:**
- Strict organizational separation between commercial and regulatory functions
- Compliance serves the regulatory function while separately ensuring commercial operations comply
- Policy advocacy role: CCO helps shape listing rules that the exchange will enforce
- Unique position: the CCO IS the regulator for 2,600+ listed companies

### 9.3 Shein Pattern — 出海 E-commerce IPO-Track

**Context:** China-origin fast-fashion e-commerce selling to 150+ countries. IPO readiness compliance across multiple potential listing jurisdictions.

**CCO compliance domains:**
- **Labor/supply chain:** Supplier audits for labor practices; Western media/NGO scrutiny; ESG due diligence
- **Product safety:** CE marking (EU), CPSC (US), chemical compliance (REACH), textile regulations per market
- **Data privacy:** PIPL (China suppliers), GDPR (EU customers), CPRA (California), and 150+ local laws
- **IPO readiness:** Whichever jurisdiction chosen (London/NYSE/HKEX), full disclosure compliance buildout
- **Advertising/content:** Country-specific advertising standards, influencer disclosure, claim substantiation
- **Trade compliance:** Import duties, tariff classification, origin marking, trade sanctions

**CCO operating model:**
- Market-by-market compliance mapping (priority markets get dedicated compliance leads)
- Supplier compliance audit program (hundreds of factories)
- IPO compliance workstream running parallel to operational compliance
- External advisory heavy (Big 4 + specialist firms for each domain)
- "Compliance narrative" building for IPO roadshow (showing maturation story)

### 9.4 ByteDance Pattern — Platform + Algorithm + Global

**Context:** Operates 抖音 (China) and TikTok (global) with distinct compliance regimes. Subject to algorithm governance, content regulation, data compliance, and cross-border tensions.

**CCO compliance domains:**
- **算法备案:** Registered recommendation algorithms with CAC; ongoing disclosure
- **Content compliance:** 24/7 content moderation (AI + human); 未成年人保护 (minor protection); 正能量 (positive energy) requirements
- **Data compliance:** Strict separation between 抖音 and TikTok data; Project Texas-style data sovereignty
- **Antitrust:** Post-crackdown self-monitoring for anti-competitive behavior
- **Cross-border:** Managing US political scrutiny AND Chinese data sovereignty simultaneously
- **Generative AI:** 豆包/Doubao AI compliance under 生成式AI暂行办法

**CCO operating model:**
- Massive compliance org (1000+ if including content moderation)
- Separate compliance structures for 抖音 (China) and TikTok (global)
- Algorithm governance committee with technical + legal + policy representation
- Proactive regulatory engagement (参与标准制定)
- Real-time compliance monitoring (content violations detected in minutes not days)

### 9.5 海康威视 Pattern — Export Control Under Pressure

**Context:** World's largest video surveillance company. On US Entity List since 2019. State-owned (CETC subsidiary). Subject to technology export control from both China and US perspectives.

**CCO compliance domains:**
- **US Entity List:** Cannot procure US-origin components/technology; must verify entire supply chain
- **China 出口管制法:** Must control export of surveillance technology (dual-use)
- **Human rights compliance:** Under scrutiny for products used in Xinjiang; Western customer due diligence
- **国密/encryption:** Products contain encryption; export requires Chinese government approval
- **Data security:** Products process massive video data; PIPL compliance for any PII processed
- **SOE compliance:** SASAC oversight, 三重一大 decision-making, Party committee integration

**CCO operating model:**
- Dedicated export control team with component-level supply chain tracking
- Dual product architecture (US-component-free product lines for sanctioned markets)
- Human rights impact assessment framework (defensive positioning)
- Regular SASAC compliance reporting alongside commercial compliance
- Western-standard certifications (CC, NDAA-compliant configurations) for accessible markets

### 9.6 Cathay Pacific Pattern — Aviation Safety + Data + Cross-Border

**Context:** HK-based airline with cross-border operations. Experienced major data breach (2018: 9.4M passenger records). Aviation safety regulation + data compliance + multi-jurisdiction operations.

**CCO compliance domains:**
- **Aviation safety:** CAD (HK), CAAC (mainland), FAA/EASA (international) compliance; safety is non-negotiable
- **Data privacy:** Post-breach compliance overhaul; PDPO (HK), PIPL (mainland routes), GDPR (EU routes)
- **Competition/antitrust:** Oneworld alliance compliance; route/slot allocation rules
- **AML:** Passenger screening (sanctions lists); cargo compliance (dual-use goods)
- **Cross-border operations:** 40+ countries' aviation regulations simultaneously
- **ESG:** Carbon emissions compliance (CORSIA); sustainable aviation fuel mandates

**CCO lessons from 2018 breach:**
- Personal accountability established (PCPD investigation; leadership changes)
- Invested ¥500M+ in post-breach remediation
- Compliance function elevated in organizational hierarchy
- "Breach response readiness" became permanent compliance program
- External trust rebuilding: 3+ years of enhanced disclosure and third-party audits

---

## §10 Emerging Trends & Future State

### 10.1 Regulatory Trajectory (2025–2030)

| Trend | Direction | CCO Impact |
|-------|-----------|------------|
| **AI governance** | Increasingly specific rules for foundation models, AGI risk, AI-generated content | New compliance domain; dedicated AI compliance sub-team needed |
| **ESG mandates** | Moving from voluntary to mandatory disclosure (HKEX, SSE, SZSE) | ESG compliance becoming CCO responsibility (not just IR/sustainability) |
| **Cross-border data** | Gradual loosening for 自由贸易区 but tightening for "important data" | Complexity increases; more granular data classification required |
| **算法 transparency** | Moving toward explainability requirements (算法解释权) | Must build audit trails for ALL algorithmic decisions |
| **Antitrust "常态化"** | Normalized, predictable enforcement replacing campaign-style | Ongoing compliance programs replace crisis response |
| **Export control expansion** | Both China and US expanding controlled items lists | More products caught; more compliance screening needed |
| **Personal liability expansion** | More roles designated as 直接责任人; lower thresholds | CCO must ensure clear responsibility allocation (and protect self) |
| **合规科技 maturation** | RegTech becoming a mature product category in China | Better tools available; more vendor choice; integration expectations higher |

### 10.2 The CCO's Evolving Role

**From: 风险管控者 (Risk Controller)** — Reactive, focused on avoiding penalties
**To: 合规战略师 (Compliance Strategist)** — Proactive, using compliance as competitive weapon

Key shifts:
1. **From cost center to value creator:** Compliance certifications win customers; regulatory relationships enable market entry
2. **From legal expert to technology leader:** 合规科技 adoption means CCO must be tech-savvy
3. **From domestic focus to global:** Even purely domestic companies face extraterritorial regulation (US sanctions, EU CBAM)
4. **From reactive to predictive:** AI-powered regulatory intelligence; scenario planning for regulatory change
5. **From individual to ecosystem:** Industry compliance alliances; shared compliance infrastructure; standard-setting participation

### 10.3 AI Impact on CCO Function

| AI Application | Current State | 2027 Projection |
|---------------|---------------|-----------------|
| Regulatory change monitoring | Semi-automated; human review | Fully automated with impact scoring |
| Contract compliance review | AI-assisted; human decision | AI-first with human exception handling |
| AML transaction monitoring | Rule-based + ML models | Fully adaptive AI; near-zero false positives |
| Content moderation | AI + human review at scale | AI-primary with human escalation only |
| Export control screening | Database matching + manual review | Knowledge graph + NLP for complex supply chains |
| Compliance training | E-learning modules | Personalized adaptive learning; simulation-based |
| Regulatory filing preparation | Manual with templates | Auto-generated drafts from compliance data |

---

## §11 Engagement Quick Reference

### By Archetype — Opening Hooks

| Archetype | Opening Hook | Avoid |
|-----------|-------------|-------|
| **金融合规型** | "How are you handling the 金监总局 consolidation impact on your reporting requirements?" | Don't mention "fintech disruption" — they see it as compliance risk not opportunity |
| **数据合规型** | "What's your current timeline for resolving cross-border data transfer assessments?" | Don't trivialize data classification — "just tag your data" ignores massive complexity |
| **出口管制型** | "How deep into your supply chain can you currently verify component origin?" | Don't assume they want to avoid US rules — they may need compliant access to US tech |
| **出海多法域型** | "Which jurisdiction's requirements are creating the most friction with your China operations?" | Don't suggest "just follow the strictest rule everywhere" — conflicts exist where NO answer satisfies all |
| **平台治理型** | "How are you preparing for the next round of 算法 transparency requirements?" | Don't compare to EU AI Act only — China's approach is fundamentally different |
| **产业合规型** | "What's your current visibility into Tier 2/3 supplier compliance status?" | Don't lead with Western ESG framing — frame as "avoiding IPO/market access blockers" |

### CCO Persona Summary Card

```
┌─────────────────────────────────────────────────────────────┐
│                    CHINA CCO — AT A GLANCE                    │
├─────────────────────────────────────────────────────────────┤
│ Core motivation: Personal survival + company survival        │
│ Biggest fear: 监管约谈 (regulatory summons) with no answer   │
│ Decision driver: Regulatory mandate > enforcement signal >   │
│                  peer practice > efficiency                   │
│ Budget trigger: New regulation + deadline = instant budget    │
│ Trust builder: Same-sector reference customer + regulator     │
│                acceptance                                     │
│ Time horizon: Reactive (H1) moving to strategic (H3)         │
│ Key phrase: "合规是底线" (Compliance is the floor/baseline)   │
│ Internal ally: CFO (risk quantification), CISO (data/cyber) │
│ Internal tension: Product/Sales (speed vs. compliance)       │
│ Unique China factor: Political reading ability (政治嗅觉)    │
└─────────────────────────────────────────────────────────────┘
```

---

## §12 Glossary of Key Terms

| Term | Pinyin | English | Relevance |
|------|--------|---------|-----------|
| 合规 | héguī | Compliance | Core function |
| 直接责任人 | zhíjiē zérèn rén | Directly responsible person | Personal criminal liability designation |
| 三法合规 | sān fǎ héguī | Three-law compliance | 网络安全法+数据安全法+个保法 |
| 反垄断 | fǎn lǒngduàn | Antitrust | Post-2021 major enforcement area |
| 出口管制 | chūkǒu guǎnzhì | Export control | Dual US-China dimension |
| 算法备案 | suànfǎ bèi'àn | Algorithm registration | Unique China requirement |
| 运动式执法 | yùndòng shì zhífǎ | Campaign-style enforcement | Unpredictable enforcement waves |
| 约谈 | yuē tán | Regulatory summons/interview | Informal but serious regulatory engagement |
| 征求意见稿 | zhēngqiú yìjiàn gǎo | Draft for comment | Leading indicator of coming regulation |
| 合规科技 | héguī kējì | RegTech | Compliance technology |
| 违规成本 | wéiguī chéngběn | Cost of non-compliance | Key persuasion framework |
| 常态化监管 | chángtài huà jiānguǎn | Normalized supervision | Post-campaign stable enforcement |
| 金监总局 | jīn jiān zǒng jú | NFRA | Financial super-regulator (2023) |
| 不可靠实体清单 | bù kěkào shítǐ qīngdān | Unreliable Entity List | China's retaliation mechanism |
| 座谈会 | zuòtán huì | Roundtable discussion | Regulatory signal-gathering venue |
| 内控 | nèi kòng | Internal controls | Foundation of compliance program |
| 合规文化 | héguī wénhuà | Compliance culture | Organizational embedding of compliance |

---

*End of document. This persona reference should be used as a foundation for understanding the China CCO role. Always verify specific regulatory details against current sources — China's regulatory landscape changes rapidly.*
