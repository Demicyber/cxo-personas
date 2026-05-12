# CISO — 信息安全负责人 · China-Market Persona

| Field | Detail |
|-------|--------|
| **Title variants** | 安全负责人, 信息安全总监, 网络安全部负责人, CSO, CISO (rarely used in Chinese context), 首席安全官, 安全VP |
| **Reports to** | CTO (most common), CIO, or directly to CEO (in regulated/critical infra) |
| **Direct reports** | Security Operations Center (SOC) Lead, 合规/Compliance Lead, Penetration Testing Team, Data Security Team, 等保 Certification Team |
| **Revenue band** | Controls ¥10M–¥500M+ in security spend annually (higher for critical infra) |
| **Buying authority** | Full authority on security tools <¥5M; co-decision with CTO/CIO on platform security >¥10M |
| **Typical tenure** | 2–3 years (民企/Internet); 5–8 years (金融/关基); high turnover due to breach liability |
| **Education** | CS/Information Security from 985 universities; CISSP/CISP certifications; some with public security (公安) or military background |

---

## Reader Note

> **Reader note.** This document is written to be readable and extractable by AI agents of varying capability — from small open-weights models up to frontier models. Concepts are spelled out explicitly rather than implied; some redundancy across sections is intentional so that any single section remains useful in isolation. If you are a strong model, skim the key insight inside each block; if you are a weaker model, read the full block. The China CISO role uniquely combines personal criminal liability (安全责任人), mandatory national cyber exercises (HW护网), and the three-law compliance trinity (网络安全法+数据安全法+个人信息保护法) in ways that have no Western equivalent.

> **Data usage instruction for agents.** All company names, executive names, financial figures, and examples in this document are illustrative — they teach you the *pattern*. They are NOT current data to be cited verbatim in customer-facing outputs. When generating any customer-facing deliverable, you MUST verify against current public sources before including them. Treat examples here as "this is the *type* of thing to look for" — then go find the latest version.
>
> Data vintage: Examples and figures sourced primarily from FY2024–FY2026 public disclosures and industry research. China-market context reflects policy environment through 15th Five-Year Plan (2026–2030) early signals.

---

## What a CISO Actually Is — China Context

In Western companies the CISO is a well-established C-suite role with board reporting lines, dedicated budgets, and clear career paths. In China, the security leadership role is **fundamentally different** in five ways:

1. **Personal Criminal Liability** — Under 网络安全法 Article 21 and related regulations, the designated 安全责任人 (security responsible person) faces personal fines (¥10,000–¥100,000) and potential criminal prosecution if a major breach occurs. This is not theoretical — executives have been detained. The role carries existential personal risk.

2. **Government Interface Role** — The CISO must maintain relationships with 公安部 (Ministry of Public Security) for 等保 assessments, CAC (国家互联网信息办公室) for data transfer approvals, and industry regulators (CSRC for finance, MIIT for telecoms). These are not optional compliance checkboxes — they are ongoing relationships requiring regular reporting.

3. **HW护网 Participant** — Annual national-level red team exercises (护网行动) organized by 公安部 require designated companies to defend against government-sponsored attacks. The CISO's team performance is scored and reported. Poor performance has real consequences (regulatory scrutiny, leadership changes).

4. **信创 Security Stack Migration** — The CISO must replace proven Western security tools (Palo Alto, CrowdStrike, Fortinet) with domestic alternatives (奇安信, 深信服, 天融信, 绿盟) while maintaining equivalent protection levels. This is a multi-year, high-risk migration.

5. **Not Always C-Suite** — Unlike Western CISOs who increasingly report to the board, China's security leaders often sit 1–2 levels below the C-suite, reporting to CTO or CIO. Budget authority and organizational influence vary dramatically by industry and company maturity.

The China CISO operates in an environment where **the state is simultaneously the biggest threat actor and the primary compliance authority**, where personal freedom is at stake in breach scenarios, and where the security tool landscape is undergoing forced domestic substitution.

---

## §1 Role Definition

### 1.1 Five CISO Archetypes

| Archetype | Description | Example Pattern |
|-----------|-------------|-----------------|
| **合规驱动型 (Compliance-Driven)** | Primary focus on meeting regulatory requirements (等保2.0, 三法合规, CAC assessments); security as checkbox exercise | SOEs, 港交所 regulatory compliance, financial institutions under CSRC oversight |
| **攻防实战型 (Red Team / Offensive)** | Background in penetration testing or military/公安; focuses on real attack surface reduction; HW护网 performance is personal pride | ByteDance security team, 海康威视 (defending against state-level threats), large Internet companies |
| **数据治理型 (Data Governance)** | Primarily concerned with data classification, cross-border transfer, PIPL compliance; emerged post-2021 regulation wave | Shein (multi-jurisdiction PII), WeBull (SEC+CSRC+PIPL), Cathay Pacific (passenger data post-breach) |
| **出海安全型 (Global Security)** | Managing security across China + international operations; dual compliance stacks; supply chain trust | ByteDance (TikTok data sovereignty), 海康威视 (Entity List + customer trust), Shein (global e-commerce) |
| **关基守护型 (Critical Infra Guardian)** | Protecting national critical infrastructure; highest regulatory burden; zero-tolerance for incidents | 港交所 (exchange infrastructure), energy/telecom companies, major financial platforms |

### 1.2 Diagnostic Table — Identifying the Archetype

| Signal | Likely Archetype |
|--------|-----------------|
| Company recently passed/failed 等保 assessment | 合规驱动型 |
| CISO has CTF/红队 background; company scored well in 护网 | 攻防实战型 |
| Recent CAC data transfer assessment or PIPL audit | 数据治理型 |
| Company operates in US/EU markets with China HQ | 出海安全型 |
| Company designated as 关键信息基础设施 (CIIO) | 关基守护型 |
| Company had a public breach in last 3 years | Likely transitioning to 攻防实战型 (post-crisis upgrade) |
| Multiple signals present | Blend — lead with dominant, acknowledge secondary |

### 1.3 Three Time Horizons

| Horizon | Timeframe | Focus | Example |
|---------|-----------|-------|---------|
| **H1: Defend and comply** | 0–6 months | 护网 preparation, 等保 assessment cycle, incident response, vulnerability patching | 港交所 preparing for annual 护网 scoring period |
| **H2: Architecture upgrade** | 6–18 months | 信创 security stack migration, Zero Trust implementation, SASE deployment, data classification | 海康威视 replacing foreign firewalls with domestic alternatives post-Entity List |
| **H3: Strategic security posture** | 18–36 months | Security-by-design in new products, AI-powered security operations, supply chain trust framework | ByteDance building privacy-by-design architecture for global operations |

### 1.4 Four-Way Pull

The China CISO is pulled in four directions simultaneously:

```
                    Regulators / 监管
                    "等保必须过"
                    "护网扣分了"
                    "跨境数据传输要评估"
                         │
                         ▼
    Business ◄────── CISO ──────► CTO / Engineering
    "安全流程太慢了"       │        "安全工具影响性能"
    "上线不能等"          │        "信创替换进度如何?"
    "客户要SOC2报告"      │        "漏洞修复排期冲突"
                         │
                         ▼
                  Threat Actors / 威胁
                  "APT攻击不等人"
                  "勒索软件升级了"
                  "0day在野利用"
```

**Regulatory Pull** — The most powerful force. Failure to comply carries personal criminal liability. 等保 deadlines are hard deadlines. 护网 scoring is public within government circles. CAC can block business operations (cross-border data transfer denial = revenue stop).

**Business Pull** — Security is seen as friction. Product teams want fast releases. Sales teams need compliance certifications (SOC2, ISO27001) to close deals. International customers demand security attestations that domestic-focused teams struggle to produce.

**CTO/Engineering Pull** — Security tools slow down CI/CD pipelines. 信创 security products have compatibility issues. Vulnerability patching competes with feature development sprints. Performance overhead of encryption/monitoring is resisted.

**Threat Actor Pull** — China-based companies face sophisticated state-level attacks (from multiple nation-states), advanced cybercrime, and insider threats. The threat landscape doesn't pause for compliance timelines or budget cycles.

---

## §2 Strategic Priorities

### Priority 1: 三法合规 (Three-Law Trinity Compliance)

The foundational regulatory framework every China CISO must master:

| Law | Effective | Core Requirement | CISO Impact |
|-----|-----------|------------------|-------------|
| **网络安全法 (Cybersecurity Law)** | June 2017 | Network security protection obligations; 等保 classification; incident reporting | Must implement 等保2.0, designate 安全责任人, report incidents within 24hrs |
| **数据安全法 (Data Security Law)** | Sept 2021 | Data classification; important data catalog; cross-border restrictions | Must classify all data assets; important/core data cannot leave China without assessment |
| **个人信息保护法 (PIPL)** | Nov 2021 | Consent-based processing; data minimization; cross-border transfer rules | Must implement consent management, DPO equivalent role, impact assessments |

**Practical compliance actions:**

1. **Data mapping and classification** — Every data asset must be classified (一般/重要/核心). This is not optional and not a one-time exercise.
2. **Cross-border data transfer** — Any data leaving China requires one of: CAC security assessment (mandatory for CIIOs or >1M persons' data), standard contractual clauses, or certification. Processing time: 3–6 months minimum.
3. **Personal information impact assessment (个人信息保护影响评估)** — Required before processing sensitive personal information or transferring PI overseas.
4. **Incident reporting** — Must report to regulators within 24 hours of discovering a security incident. Unlike Western breach notification (which focuses on individuals), China requires *government* notification first.

### Priority 2: 等保2.0 (Classified Protection 2.0)

等保 (网络安全等级保护) is the mandatory security classification and assessment regime:

| Level | Description | Typical Entities | Assessment Frequency |
|-------|-------------|------------------|---------------------|
| Level 1 | Self-protection | Small internal systems | Self-assessment |
| Level 2 | Guided protection | Standard business systems | Every 2 years (third-party) |
| Level 3 | Supervised protection | Important business systems; most Internet companies | Annual (third-party) |
| Level 4 | Mandatory protection | Critical infrastructure; major financial systems | Semi-annual |
| Level 5 | Exclusive protection | National security systems | Classified |

**CISO responsibilities for 等保:**
- Determine correct level for each system (under-classification is a violation; over-classification wastes resources)
- Engage authorized assessment firms (等保测评机构)
- Remediate findings before re-assessment
- Maintain documentation for spot inspections
- Budget: Level 3 assessment costs ¥200K–¥800K per system; remediation ¥500K–¥5M+

**Example:** A company like WeBull with trading systems handling customer funds and personal data likely requires Level 3 for customer-facing systems and potentially Level 4 for core trading infrastructure under CSRC regulations.

### Priority 3: HW护网 (National Cyber Exercise)

护网行动 is China's annual national-level red team vs. blue team exercise:

**What it is:**
- Organized by 公安部 (Ministry of Public Security)
- Government-assembled red teams (攻击队) attack designated organizations
- Companies must defend (防守方) with their existing security posture
- Scored system: points deducted for successful breaches, added for detections
- Typically runs 2–3 weeks, usually in summer (varies by year)

**Why the CISO cares deeply:**
- Results are shared with company leadership and regulators
- Poor performance triggers regulatory scrutiny and potential penalties
- Budget justification: "We need ¥X to not fail 护网 next year" is highly effective
- Career impact: CISO reputation among peers is partially based on 护网 performance
- Some companies hire temporary "外援" (external support) teams for the exercise period

**Preparation cycle:**
- 3–6 months before: asset discovery, vulnerability scanning, network segmentation review
- 1–2 months before: penetration testing, attack surface reduction, staff training
- During: 24/7 SOC operations, all-hands defense, rapid response
- After: lessons learned, budget requests for gap remediation

**Budget implication:** 护网-related spending can consume 20–40% of annual security budget in the preparation year.

### Priority 4: 信创 Security Stack Migration

The CISO must replace proven Western security products with domestic alternatives:

| Western Product | Domestic Alternative | Migration Risk |
|----------------|---------------------|----------------|
| Palo Alto Networks (NGFW) | 奇安信, 天融信, 山石网科 | Medium — feature gaps in advanced threat prevention |
| CrowdStrike / Carbon Black (EDR) | 奇安信天擎, 深信服EDR, 安天 | High — detection rates vary; endpoint performance impact |
| Fortinet (UTM) | 深信服, 绿盟, 启明星辰 | Medium — manageable for SMB; enterprise features lag |
| Splunk (SIEM) | 奇安信态势感知, 绿盟NSFOCUS, 安恒 | High — log correlation rules must be rebuilt |
| Zscaler (SASE/ZTN) | 深信服零信任, 奇安信SASE | High — cloud-native architecture differs significantly |
| Tenable / Qualys (VM) | 绿盟, 安恒, 长亭科技 | Low–Medium — scanning capability comparable |
| Okta (IAM) | 竹云, 芯盾时代, 派拉软件 | Medium — integration ecosystem smaller |

**CISO challenges during migration:**
- **Detection gap** — During transition, neither old nor new system has full visibility
- **Staff retraining** — SOC analysts trained on Splunk must learn new interfaces
- **Vendor maturity** — Domestic vendors have smaller R&D teams; CVE response slower
- **Integration** — Domestic products integrate well with each other but poorly with remaining Western components
- **Performance baseline** — Must prove to auditors that security posture hasn't degraded

### Priority 5: Cross-Border Data Security (出海 companies)

For companies operating internationally (ByteDance, Shein, WeBull, 海康威视):

| Requirement | China Side | International Side | Conflict Point |
|-------------|-----------|-------------------|----------------|
| Data residency | Data must stay in China (default) | GDPR requires EU data in EU; some countries require local storage | Must maintain separate data stores per jurisdiction |
| Transfer mechanism | CAC security assessment or SCC | GDPR adequacy decision (China not recognized) or SCCs | Dual assessment processes; 6+ months each |
| Government access | Authorities can request data access | Foreign govts suspicious of China government access | TikTok/ByteDance pattern: must prove separation |
| Breach notification | 24hr to regulators | GDPR: 72hr to DPA; various state laws in US | Multiple parallel notification streams |
| Encryption | Must use 国密 (SM2/SM3/SM4) for classified/government | International standards (AES, RSA) expected globally | Dual crypto implementations |

**Architectural pattern for 出海 security:**
```
China Region (境内)              │  International (境外)
─────────────────────────────────│──────────────────────────
China SOC (奇安信/深信服 stack)   │  Global SOC (mixed stack)
国密 encryption (SM4/SM2)        │  AES-256 / RSA encryption
Data stays in CN (阿里云/腾讯云)  │  Data in local regions (AWS/GCP)
等保2.0 compliance               │  SOC2/ISO27001/GDPR compliance
CAC reporting                    │  DPA/regulatory reporting
                                 │
         ◄── Minimal data bridge (approved by CAC) ──►
              (aggregated, anonymized where possible)
```

### Priority 6: Supply Chain Security

Two dimensions of supply chain security for China companies:

**Inbound supply chain (供应链安全 — defensive):**
- Software Bill of Materials (SBOM) tracking for all third-party components
- Open-source vulnerability management (Log4j response was a wake-up call)
- Vendor security assessments (especially cloud/SaaS providers)
- 信创 vendor security maturity (newer vendors = less battle-tested)
- Hardware integrity for 国产 chips and devices

**Outbound supply chain (being trusted — offensive/reputation):**
- 海康威视 pattern: customers (especially Western governments) question whether Chinese-made devices have backdoors
- Must provide transparency: source code escrow, third-party audits, bug bounty programs
- ByteDance/TikTok: Project Texas (US data sovereignty) as a security trust-building exercise
- Certification arms race: CC (Common Criteria), FIPS 140-2, SOC2 Type II — to prove trustworthiness internationally

---

## §3 Key Performance Indicators

### 3.1 Operational KPIs

| KPI | Target Range | Context |
|-----|-------------|---------|
| Mean time to detect (MTTD) | <4 hours (advanced); <24 hours (standard) | 护网 scoring heavily weights detection speed |
| Mean time to respond (MTTR) | <1 hour (P0); <4 hours (P1) | Incident response SLA; regulatory reporting clock starts at detection |
| Vulnerability patch rate (critical) | 100% within 72 hours | Critical CVEs exploited in wild; 等保 auditors check patch compliance |
| 等保 assessment score | Pass with <3 non-conformities | Failed assessment requires re-assessment within 6 months |
| 护网 score | Top 30% of peer group | Relative performance matters; absolute scoring varies by year |
| SOC alert false positive rate | <30% | High false positives cause alert fatigue → missed real attacks |
| Security tool uptime | >99.9% | Security tools going down = blind spots = risk |
| Phishing simulation click rate | <5% (target); reality often 15–25% | Staff awareness indicator |

### 3.2 Compliance KPIs

| KPI | Target | Context |
|-----|--------|---------|
| Data classification coverage | 100% of identified assets | Regulators can spot-check; gaps = fines |
| Cross-border transfer approvals | All transfers documented and approved | One unapproved transfer = potential business shutdown |
| PIPL consent coverage | 100% of PI processing activities | Impact assessment completion rate |
| Incident reporting compliance | 100% within 24-hour window | Late reporting is independently punishable |
| 信创 migration % (security tools) | Per organizational timeline (often 50% by 2025, 80% by 2027) | SOEs have mandatory timelines; private sector has softer targets |
| Third-party security assessments | Annual for critical vendors | Supply chain risk management maturity |
| Security awareness training completion | >95% of staff annually | 等保 requirement; audited |

### 3.3 Business-Linked KPIs

| KPI | Connection |
|-----|-----------|
| Security certification obtained (SOC2/ISO27001) | Enables international sales; customer requirement |
| Mean time to customer security questionnaire response | Sales cycle acceleration |
| Security incidents impacting customers | Zero tolerance; brand/revenue impact |
| Regulatory fine avoidance | Direct financial + reputational |
| 护网 performance vs. budget invested | Security ROI proxy for leadership |
| Time to approve new product/feature security review | Developer experience; speed-to-market |
| Insurance premium trends (cyber insurance) | Risk quantification signal |

---

## §4 Pain Points

### 4.1 Personal Liability Pressure

| Pain | Manifestation |
|------|---------------|
| Criminal exposure | 安全责任人 designation means personal fines and potential detention if major breach occurs |
| Accountability without authority | Named as responsible person but lacks budget authority or organizational power to enforce |
| Scapegoat risk | When breach occurs, CISO is first person investigated regardless of root cause |
| Insurance gap | Cyber liability insurance for individuals is immature in China; D&O policies may not cover |
| Career fragility | One major incident = career over in regulated sectors |

**Verbatim-style pain statement:** *"我是法定的安全责任人，出了事我要承担刑事责任。但我的预算要CTO审批，业务部门可以拒绝我的安全要求，我连个VP title都没有。"*

### 4.2 护网 Anxiety

| Pain | Manifestation |
|------|---------------|
| Annual high-stakes test | 2–3 weeks of 24/7 stress; government red teams are extremely skilled |
| Budget surge pattern | 60% of remediation budget spent in 3 months before 护网; unsustainable |
| Temporary staff dependency | Must hire "外援" (consultants) to supplement defense; they leave after |
| Score politics | Poor score reflects on entire leadership; CTO/CEO blame CISO regardless of context |
| Attack surface anxiety | Every new system launched by business = new attack surface for 护网 |

**Verbatim-style pain statement:** *"护网前三个月我基本不睡觉。攻击队是国家级水平，我的团队只有20个人，预算还被砍了。去年被打穿一个系统，领导谈话了两小时。"*

### 4.3 信创 Migration Security Gaps

| Pain | Manifestation |
|------|---------------|
| Detection capability regression | Domestic EDR/SIEM miss threats that CrowdStrike/Splunk would catch |
| Transition blind spots | Old system decommissioned before new system fully tuned = visibility gap |
| Vendor support immaturity | Domestic vendors: slower CVE response, less threat intelligence, smaller research teams |
| Integration nightmares | Domestic products assume all-domestic ecosystem; hybrid environments poorly supported |
| Proving equivalence | Must demonstrate to auditors that protection hasn't degraded (hard to prove) |

### 4.4 Cross-Border Data Compliance Complexity

| Pain | Manifestation |
|------|---------------|
| CAC assessment timeline | 3–6+ months; business can't wait; pressure to transfer data before approval |
| Conflicting requirements | US SEC wants access to audit data; China says it can't leave; CISO caught in middle |
| Architecture cost | Maintaining fully separate data planes (China + international) doubles infrastructure cost |
| Ambiguity in "important data" | Regulation doesn't precisely define what counts; over-classifying blocks business; under-classifying risks penalty |
| Moving goalposts | Regulations still evolving; what was compliant last year may not be this year |

**Verbatim-style pain statement:** *"SEC要看我们的审计数据，CSRC说这些数据不能出境，CAC的评估已经提交三个月了还没批。业务说如果数据不能出去，美国上市资质会有问题。"*

### 4.5 Budget and Authority Deficit

| Pain | Manifestation |
|------|---------------|
| Security = cost center | No direct revenue attribution; first budget cut when times are tough |
| Reporting too low | Reports to CTO (who has competing priorities) not CEO/Board |
| "Nothing happened" paradox | If security works well, nothing visible happens → hard to justify increased budget |
| Quantification difficulty | ROI of security investment is inherently probabilistic; CFO wants deterministic numbers |
| Post-breach only | Major budget increases only come AFTER an incident (too late) |

### 4.6 Talent Shortage

| Pain | Manifestation |
|------|---------------|
| Market shortage | China has ~500K security professionals vs. estimated need of 1.5M+ |
| Compensation competition | 奇安信/ByteDance/Tencent pay ¥800K–¥2M for senior security engineers |
| Skill mismatch | Many certified (CISP) but lack practical attack/defense skills |
| Burnout/turnover | SOC analysts burn out from shift work + 护网 pressure; 18–24 month average tenure |
| Training investment loss | Train staff → they leave for higher-paying roles at BAT |

---

## §5 Decision-Making Framework

### 5.1 How the China CISO Evaluates Security Investments

```
Priority 1: Will this help us pass 等保 / avoid regulatory penalty?
    YES → High priority (compliance is non-negotiable)
    
Priority 2: Will this improve 护网 score?
    YES → Fund it (leadership visibility + personal reputation)
    
Priority 3: Does this reduce real attack surface?
    YES → Evaluate ROI vs. threat likelihood
    
Priority 4: Does this satisfy customer/international requirements?
    YES → Fund if sales deals depend on it (SOC2, ISO27001)
    
Priority 5: Is this "nice to have" security maturity improvement?
    → Deprioritize unless budget surplus (rare)
```

### 5.2 Vendor Selection Criteria

| Criterion | Weight | Reasoning |
|-----------|--------|-----------|
| 信创 compliance / domestic vendor | 30% | Mandatory for SOEs; strong preference elsewhere; political safety |
| Detection/protection capability | 25% | Must actually stop threats; 护网 performance depends on tool quality |
| 等保 assessment alignment | 15% | Tool must generate evidence for auditors |
| Ease of integration | 15% | Must work with existing (often hybrid) environment |
| Vendor support quality | 10% | 7×24 response; on-site support during 护网 |
| Price | 5% | Less price-sensitive than other IT purchases due to compliance necessity |

**Key insight:** Unlike Western CISOs who optimize for best-of-breed detection, China CISOs optimize first for **regulatory acceptance**, then for actual protection capability. A domestic product that passes 等保 audit is preferred over a superior foreign product that creates compliance questions.

### 5.3 The "Three Approvals" for Major Security Decisions

Most China CISOs need alignment from three parties before major initiatives:

1. **CTO/CIO** — Technical feasibility and integration with existing architecture
2. **Legal/Compliance (法务/合规)** — Regulatory requirement validation; liability assessment
3. **Finance (财务)** — Budget approval; often requires 3-year TCO justification

For 关基 (critical infrastructure) companies, add:
4. **Government liaison (政府关系)** — Informal approval from relevant regulatory contacts before formal submission

### 5.4 Budget Justification Patterns That Work

| Argument | When to Use | Effectiveness |
|----------|-------------|---------------|
| "等保不过会被罚" (We'll fail 等保 assessment) | Compliance deadline approaching | Very High — legal requirement |
| "护网打穿了怎么办" (What if we get breached in 护网) | 3–6 months before 护网 period | High — leadership embarrassment fear |
| "个人信息泄露的行政处罚" (PIPL violation penalties) | After industry peer receives fine | High — fresh example creates urgency |
| "客户要求有SOC2才能签约" (Customer requires SOC2 for contract) | Specific deal at stake | High — direct revenue linkage |
| "竞品出了安全事故" (Competitor had a breach) | After public industry breach | Medium-High — "could happen to us" |
| "最佳实践/行业标准" (Best practice / industry standard) | General maturity improvement | Low — not compelling without specific trigger |

---

## §6 Communication Patterns

### 6.1 Language and Terminology

The China CISO's vocabulary mixes Chinese regulatory terms with English security terminology:

**Internal communication (to leadership):**
- 等保几级？过了没有？ (What level? Did we pass?)
- 护网准备进度 (护网 preparation progress)
- 数据出境评估 (Cross-border data transfer assessment)
- 安全责任人变更 (Security responsible person change — when organizational restructuring)
- 攻击面收敛 (Attack surface reduction)
- 安全左移 (Shift-left security — increasingly adopted concept)

**External communication (to regulators):**
- 网络安全等级保护备案 (等保 filing/registration)
- 数据安全影响评估报告 (Data security impact assessment report)
- 个人信息保护影响评估 (Personal information protection impact assessment)
- 网络安全事件报告 (Cybersecurity incident report)
- 关键信息基础设施安全保护方案 (CIIO security protection plan)

**Vendor communication:**
- 态势感知 (Situational awareness — SIEM equivalent positioning in China)
- 零信任 (Zero Trust)
- 终端检测与响应 (EDR)
- 安全运营中心 (SOC)
- 威胁情报 (Threat intelligence)
- 攻防演练 (Attack-defense exercise — 护网 preparation)

### 6.2 Board/Leadership Reporting Style

China CISOs rarely get board time. When they do, the format is:

```
1. Compliance status: ✅等保通过 / ⚠️整改中 / ❌未通过
2. Incident summary: X incidents this quarter (0 P0, 2 P1)
3. 护网 readiness: Green/Yellow/Red
4. Key risk: [One sentence on biggest current risk]
5. Budget ask: [Only if needed; tied to specific compliance/threat]
```

Contrast with Western CISO board presentations (risk frameworks, heat maps, maturity models) — China leadership prefers binary (pass/fail, compliant/non-compliant) with specific action items.

### 6.3 Messaging That Resonates vs. Falls Flat

| Message That Works | Why |
|-------------------|-----|
| "This ensures we pass 等保/护网" | Compliance = non-negotiable |
| "Competitor X was fined ¥Y million for this exact gap" | Social proof + fear |
| "If breach occurs, 安全责任人 faces personal liability" | Personal risk for decision-makers |
| "International customers require this certification for contract" | Revenue linkage |
| "CAC may block our data transfer if we don't implement this" | Business continuity threat |

| Message That Falls Flat | Why |
|------------------------|-----|
| "Industry best practice recommends..." | No regulatory force; seen as gold-plating |
| "Our maturity score improved from 2.3 to 2.7" | Abstract; leadership doesn't understand frameworks |
| "Advanced persistent threats are evolving..." | Too abstract; "so what?" response |
| "We should adopt Zero Trust architecture" | Buzzword without compliance/business linkage |
| "Gartner says..." | Western analyst firms have less influence on China security decisions |

---

## §7 Organizational Dynamics

### 7.1 Reporting Structure Variations

| Company Type | CISO Reports To | Reason |
|-------------|----------------|--------|
| Large Internet (ByteDance, Tencent) | CTO or dedicated Security VP | Technical depth needed; large security org |
| Financial (港交所, banks) | CIO or Chief Risk Officer | Regulatory alignment; risk management framework |
| Manufacturing (海康威视) | CTO | Security embedded in product engineering |
| 出海 companies (Shein, WeBull) | CEO or COO | Cross-functional coordination; geopolitical sensitivity |
| SOEs (国企) | General Manager via IT Director | Lower organizational status; compliance-focused |
| Post-breach companies (Cathay Pacific pattern) | CEO/Board directly | Elevated after incident to demonstrate seriousness |

### 7.2 Key Internal Relationships

| Relationship | Nature | Tension Point |
|-------------|--------|---------------|
| CISO ↔ CTO | Closest ally or biggest blocker | Security slows engineering velocity; CTO controls security budget |
| CISO ↔ Legal/Compliance | Natural partners on regulation | Legal defines requirements; CISO implements; disagreements on interpretation |
| CISO ↔ Product | Adversarial by default | Security review gates slow product launches |
| CISO ↔ HR | Cooperation on insider threat | Background checks, access termination, security culture training |
| CISO ↔ Government Relations (政府关系) | Critical for regulated sectors | GR team manages regulator relationships that CISO depends on |
| CISO ↔ International teams | Complex for 出海 companies | Different security standards, tools, and compliance requirements |

### 7.3 Team Structure (Typical Large Enterprise)

```
CISO / 安全负责人
├── Security Operations (安全运营)
│   ├── SOC (7×24 monitoring)
│   ├── Incident Response (应急响应)
│   └── Threat Intelligence (威胁情报)
├── Security Engineering (安全工程)
│   ├── Infrastructure Security (基础设施安全)
│   ├── Application Security (应用安全/SDL)
│   └── Cloud Security (云安全)
├── Data Security & Privacy (数据安全与隐私)
│   ├── Data Classification (数据分类分级)
│   ├── Cross-border Compliance (跨境合规)
│   └── Privacy Engineering (隐私工程)
├── Compliance & Audit (合规与审计)
│   ├── 等保 Management
│   ├── Regulatory Reporting
│   └── Third-party Risk (供应链安全)
└── Red Team / Penetration Testing (攻防团队)
    ├── Internal Red Team
    └── 护网 Defense Coordination
```

**Team size benchmarks:**
- Small company (Series B–C): 5–15 people
- Mid-size (public company, ¥1–10B revenue): 30–80 people
- Large (BAT-tier, critical infra): 200–500+ people
- ByteDance security team: reportedly 500+ globally

---

## §8 Industry-Specific Variations

### 8.1 Financial Services (港交所, WeBull pattern)

| Factor | Specifics |
|--------|-----------|
| Regulatory bodies | CSRC, HKMA (for HK), SFC, PBOC |
| Key requirements | Real-time transaction monitoring; data localization; customer identity verification |
| 等保 level | Level 3–4 for trading systems |
| Unique challenges | Ultra-low-latency security (can't add >1ms); multi-jurisdiction compliance (SEC + CSRC + HKMA) |
| CISO focus | Availability first (exchange downtime = national news); regulatory reporting automation |
| Budget benchmark | 8–12% of IT budget on security (higher than cross-industry average) |

### 8.2 IoT / Hardware (海康威视 pattern)

| Factor | Specifics |
|--------|-----------|
| Unique challenges | Billions of deployed devices; firmware update logistics; Entity List restrictions limiting chip access |
| Supply chain pressure | Western customers demand proof of no backdoors; must do third-party code audits |
| Product security | Security IS the product for surveillance companies; any vulnerability = existential brand risk |
| Dual audience | Chinese government customers (关基) demand 国产 compliance; international customers demand Western certifications |
| CISO focus | Product security + corporate security (dual mandate); managing perception vs. reality of nation-state association |

### 8.3 Cross-Border E-Commerce (Shein pattern)

| Factor | Specifics |
|--------|-----------|
| Data volumes | Hundreds of millions of customers' PII across 150+ countries |
| Regulatory complexity | PIPL + GDPR + CCPA + dozens of national privacy laws simultaneously |
| Payment security | PCI-DSS compliance; payment fraud prevention |
| Supply chain data | Thousands of suppliers' data; trade secrets; manufacturing data |
| CISO focus | Multi-jurisdiction privacy compliance; PCI-DSS; fraud prevention; DLP for supply chain IP |

### 8.4 Social Media / Content Platform (ByteDance pattern)

| Factor | Specifics |
|--------|-----------|
| Scale | Billions of users; petabytes of daily data; real-time content moderation |
| Geopolitical sensitivity | TikTok data sovereignty debates; forced architectural separation |
| Data types | User behavioral data, biometric (face filters), location, contacts, content |
| Government scrutiny | Both China (内容审核/content moderation compliance) and foreign (data access concerns) |
| CISO focus | Data sovereignty architecture; proving separation between China and international data; content security (内容安全) |

### 8.5 Aviation / Transportation (Cathay Pacific pattern)

| Factor | Specifics |
|--------|-----------|
| Legacy factor | Decades of IT systems; PNR data; safety-critical systems |
| Post-breach reality | 2018 breach (9.4M passengers) reshaped entire security posture |
| Regulatory | CAD, ICAO cybersecurity requirements, multiple national aviation authorities |
| Unique data | Passport details, travel patterns, payment info — extremely sensitive |
| CISO focus | Rebuilding trust post-breach; legacy system modernization; aviation-specific standards (DO-326A) |

---

## §9 Technology Landscape

### 9.1 Domestic Security Vendor Ecosystem (信创安全生态)

| Category | Key Vendors | Market Position |
|----------|------------|-----------------|
| Comprehensive (综合安全) | 奇安信, 深信服, 启明星辰 | A-share listed; government relationships; full-stack offerings |
| Network Security (网络安全) | 天融信, 山石网科, 迪普科技 | Firewall/VPN heritage; transitioning to cloud |
| Endpoint (终端安全) | 奇安信, 安天, 微步在线 | EDR/AV; 护网 defense critical |
| Data Security (数据安全) | 美创科技, 安华金和, 炼石网络 | Growing rapidly post-数据安全法 |
| Cloud Security (云安全) | 青藤云, 默安科技, 长亭科技 | Cloud workload protection; container security |
| Identity (身份安全) | 竹云, 芯盾时代, 派拉软件 | IAM, Zero Trust access |
| Threat Intelligence (威胁情报) | 微步在线, 奇安信, 绿盟 | TI feeds; APT tracking |
| Security Operations (安全运营) | 安恒信息, 绿盟, 奇安信 | SIEM/SOAR; 态势感知 platform |

### 9.2 Technology Trends (2024–2027)

| Trend | China CISO Impact | Timeline |
|-------|-------------------|----------|
| AI-powered security operations (AIOps for security) | SOC automation; alert triage; threat hunting with LLM | Now–2025 |
| Zero Trust Architecture (零信任) | Network perimeter dissolution; identity-centric security | 2024–2027 |
| Data Security Posture Management (DSPM) | Automated data discovery and classification for compliance | 2025–2027 |
| Supply Chain Security (SBOM/软件供应链安全) | SCA mandates; domestic software provenance tracking | 2024–2026 |
| 国密 algorithm transition (SM2/SM3/SM4) | Replacing RSA/AES in government/financial systems | Ongoing, accelerating |
| Confidential Computing (机密计算) | Cross-border data processing without exposure; privacy-preserving analytics | 2025–2028 |
| Security for AI (AI安全) | LLM output safety; model poisoning defense; prompt injection prevention | 2024–2026 |

### 9.3 国密 (Chinese Cryptographic Standards)

Critical knowledge for China CISO — 国密 algorithms are increasingly mandatory:

| Algorithm | Equivalent | Use Case | Mandate Status |
|-----------|-----------|----------|----------------|
| SM2 | RSA/ECC | Digital signatures, key exchange | Mandatory for government; financial transitioning |
| SM3 | SHA-256 | Hashing | Mandatory for government systems |
| SM4 | AES-128 | Symmetric encryption | Mandatory for classified; financial required |
| SM9 | IBE (Identity-Based Encryption) | Identity-based crypto | Emerging for IoT/specific use cases |

**Practical impact:** All 等保 Level 3+ systems increasingly expected to use 国密. SSL certificates must support SM2. VPN must support 国密. This affects every security product purchase decision.

---

## §10 Peer Examples (Illustrative Patterns)

### Pattern A: Post-Breach Transformation (Cathay Pacific-style)

**Situation:** Major data breach (millions of records) exposed organizational deficiencies.
**CISO response pattern:**
1. Immediate: Crisis management, regulatory notification, customer communication
2. 6 months: Complete security posture assessment; CISO role elevated to C-suite
3. 12 months: Multi-year security transformation program (¥500M+ investment)
4. 24 months: Third-party attestation of improved posture; SOC2 Type II
5. Ongoing: Security becomes board-level topic; quarterly reporting

**Lesson for sellers:** Post-breach companies have budget, urgency, and executive attention. But they also have procurement fatigue (many vendors circling) and trust deficit (skeptical of vendor claims).

### Pattern B: Entity List / Sanctions Response (海康威视-style)

**Situation:** Company placed on US Entity List; can no longer purchase Western security tools.
**CISO response pattern:**
1. Immediate: Audit all Western security tools with expiring licenses/support
2. 3 months: Emergency procurement of domestic alternatives for critical gaps
3. 6–12 months: Systematic migration to all-domestic security stack
4. Ongoing: Build internal security R&D capability to reduce vendor dependency
5. International: Increase transparency (third-party audits, bug bounties) to rebuild customer trust

**Lesson for sellers:** Sanctioned companies are captive buyers of domestic products but demand higher quality (they've experienced Western product quality). Price sensitivity is lower; performance demands are higher.

### Pattern C: Multi-Jurisdiction Compliance (WeBull/Shein-style)

**Situation:** Company operates globally from China HQ; subject to China + multiple foreign regulatory regimes simultaneously.
**CISO response pattern:**
1. Build compliance matrix: map every data type × every jurisdiction × every requirement
2. Architecture: Separate data planes per jurisdiction; minimal cross-border flow
3. Team: Local security/compliance teams in key markets (US, EU, SEA)
4. Certification: Pursue ISO27001 + SOC2 (international) + 等保 (China) simultaneously
5. Vendor strategy: Different security stacks per region (domestic for China, mixed for international)

**Lesson for sellers:** These companies buy security products per-region. Don't assume a China sale extends globally or vice versa. The decision-maker may differ by region.

### Pattern D: 护网-Driven Security Maturity (Large Enterprise pattern)

**Situation:** Company performs poorly in 护网; leadership demands improvement.
**CISO response pattern:**
1. Post-护网 assessment: Identify all successful attack paths; root cause analysis
2. Budget approval: "We were breached in 护网" unlocks emergency budget (¥10–50M+)
3. Quick wins: Attack surface reduction (close unnecessary ports, decommission systems)
4. Platform investment: SIEM/SOC upgrade, EDR deployment, network segmentation
5. People: Hire experienced 红队 (red team) members to join blue team; retain external support

**Lesson for sellers:** 护网 season (typically March–May for preparation, June–August for execution) is prime selling season. Post-护网 debrief (September–October) is prime budget approval season.

### Pattern E: Data Sovereignty Architecture (ByteDance/TikTok-style)

**Situation:** Foreign government demands proof that China cannot access overseas user data.
**CISO response pattern:**
1. Architecture redesign: Physical and logical separation of data environments
2. Third-party oversight: Engage Western security firms (Oracle partnership pattern) for monitoring
3. Transparency: Open source code inspection, controlled access programs
4. Governance: Independent data governance board with external members
5. Ongoing: Continuous monitoring and attestation to satisfy political concerns

**Lesson for sellers:** Data sovereignty is both a technical and political problem. Solutions that provide auditable proof of separation (not just policy but technical enforcement) command premium pricing.

---

## §11 Selling to the China CISO

### 11.1 Discovery Questions

| Question | What It Reveals |
|----------|----------------|
| "贵司等保几级？上次测评什么时候？" | Compliance level and urgency of next assessment |
| "今年护网打算怎么准备？" | Budget availability and pain points from last exercise |
| "数据出境评估做了吗？" | Cross-border compliance maturity and urgency |
| "安全团队多少人？SOC是自建还是外包？" | Internal capability and outsourcing propensity |
| "信创替换进度怎么样？安全产品换了哪些？" | Migration status and remaining opportunities |
| "安全预算在IT预算中占比多少？" | Budget maturity (typical: 3–8% of IT; post-breach: 10–15%) |
| "出过安全事件吗？监管有要求整改吗？" | Pain history and compliance pressure |

### 11.2 Buying Triggers

| Trigger | Urgency | Budget Source |
|---------|---------|---------------|
| Upcoming 等保 assessment (3–6 months out) | High | Compliance budget (pre-allocated) |
| 护网 preparation season | Very High | Emergency/supplemental budget |
| Failed 护网 (just happened) | Critical | CTO/CEO-level emergency funding |
| CAC data transfer requirement | High | Cross-functional (legal + IT + security) |
| Industry peer breach (public) | Medium-High | "Same thing could happen to us" fear |
| New regulation effective date | High | Mandatory compliance spending |
| International customer security questionnaire | Medium | Sales-linked security investment |
| Board/investor inquiry about security posture | Medium | Governance-driven |
| Post-incident remediation | Critical | Unlimited (temporarily) |

### 11.3 Objection Handling

| Objection | Response Strategy |
|-----------|-------------------|
| "We already have domestic product X" | Focus on gaps product X doesn't cover; offer complementary positioning |
| "Budget already allocated this year" | Map to next fiscal year; or link to 护网 emergency budget |
| "Your product is foreign — we need 信创" | If foreign: emphasize China entity, local data processing, 国密 support. If domestic: lead with 信创 catalog listing |
| "Our team can build this internally" | Highlight time-to-compliance vs. build time; 护网 deadline pressure |
| "We need to evaluate 3+ vendors" | Expected; position for pilot/POC aligned with 护网 preparation |
| "CISO can't approve — need CTO/CFO" | Help CISO build internal business case; provide ROI materials |

### 11.4 Competitive Dynamics

| If Competing Against | Differentiate By |
|---------------------|------------------|
| 奇安信 | They're spread thin (too many products); depth in your specific area |
| 深信服 | Their strength is network/cloud; if you're endpoint/data, emphasize specialization |
| Foreign vendor (Palo Alto, CrowdStrike) | 信创 compliance; local support; 国密 support; political safety |
| Internal build | Time-to-value; ongoing maintenance burden; 等保 auditor recognition |
| Free/open-source | Enterprise support; compliance documentation; vendor accountability |

---

## §12 Regulatory Calendar & Timing

### 12.1 Annual Security Calendar (China CISO)

| Period | Activity | Vendor Opportunity |
|--------|----------|-------------------|
| Q1 (Jan–Mar) | Annual security planning; budget finalization; 护网 notification received | Strategic planning discussions; annual contract renewals |
| Q2 (Apr–Jun) | 护网 preparation intensifies; vulnerability remediation sprint; external assessment | Emergency procurement; consulting/services; red team testing |
| Q3 (Jul–Sep) | 护网 execution (varies); post-护网 debrief; gap analysis | Post-exercise remediation sales; next-year budget justification |
| Q4 (Oct–Dec) | 等保 annual assessment; budget planning for next year; year-end compliance reports | Assessment support; next-year project scoping; pilot programs |

### 12.2 Regulatory Milestones (2024–2027)

| Milestone | Impact on CISO |
|-----------|---------------|
| 网络数据安全管理条例 (effective Jan 2025) | Detailed implementation rules for data security; tightens enforcement |
| 等保2.0 continued evolution | Additional requirements for cloud, IoT, industrial control systems |
| 国密 algorithm transition deadlines | Financial sector: SM2/SM4 mandatory for new systems; existing systems transitioning |
| 关基 operator expanded list | More companies designated as CIIO; elevated security requirements |
| AI governance regulations | Security requirements for AI systems; algorithm registration; safety assessments |
| Cross-border data transfer enforcement | Increased CAC enforcement of unapproved transfers |

---

## §13 Career Path & Background

### 13.1 Typical China CISO Background

| Background | Percentage (est.) | Characteristics |
|-----------|-------------------|-----------------|
| Technical security (渗透测试/安全研发) | 40% | Deep technical skills; may lack business communication ability |
| IT operations → security | 25% | Broad IT knowledge; pragmatic; compliance-oriented |
| 公安/military (公安部/军队) | 15% | Government relationships; understanding of threat landscape; may lack enterprise IT depth |
| Audit/compliance | 10% | Strong on process/documentation; may lack technical depth |
| Consulting (四大/安全咨询) | 10% | Broad industry exposure; framework-oriented; may lack operational depth |

### 13.2 Certification Landscape

| Certification | Relevance in China |
|--------------|-------------------|
| CISP (注册信息安全专业人员) | Most recognized domestic certification; often required for 安全责任人 |
| CISSP | Valued for international credibility; less regulatory weight domestically |
| CISP-PTE (渗透测试) | Technical credibility; valued for 攻防 background |
| ISO 27001 Lead Auditor | Useful for compliance-oriented CISOs |
| CCSK/CCSP (Cloud Security) | Emerging value as cloud adoption grows |
| 等保测评师 | Deep specialization; usually not CISO but key team member |

### 13.3 Compensation Benchmarks (2024–2026)

| Company Type | CISO Compensation Range | Notes |
|-------------|------------------------|-------|
| Large Internet (BAT/ByteDance) | ¥2M–¥5M+ (cash + equity) | VP-level; significant equity component |
| Listed tech company | ¥1.5M–¥3M | Director/VP level; RSU grants |
| Financial institution | ¥1.2M–¥2.5M | Stable; bonus-heavy; title may be "部门总经理" |
| SOE (国企) | ¥600K–¥1.2M | Capped by SOE compensation policies; benefits/stability compensate |
| Series C–D startup | ¥1M–¥2M + options | Higher risk; potential upside from equity |
| Manufacturing/traditional | ¥800K–¥1.5M | Often less organizational power |

---

## §14 Emerging Themes (2025–2027)

### 14.1 AI Security (AI安全)

The China CISO must now address security OF AI systems and security BY AI:

**Security of AI (protecting AI systems):**
- Model poisoning / adversarial attacks on company ML models
- Training data security (massive datasets = massive attack surface)
- Prompt injection in customer-facing LLM applications
- AI-generated content compliance (深度伪造/deepfake risks)
- Algorithm registration with CAC (for recommendation algorithms)

**Security by AI (using AI to improve security):**
- LLM-powered SOC automation (alert triage, report generation)
- AI-driven threat hunting (pattern detection in logs)
- Automated vulnerability assessment and prioritization
- Intelligent access control (behavioral analytics)
- 护网 defense automation (faster response to red team tactics)

### 14.2 Privacy-Enhancing Technologies (PET / 隐私计算)

Growing importance for cross-border data challenges:
- Federated Learning (联邦学习) — train models without moving data
- Secure Multi-Party Computation (安全多方计算) — joint analysis without exposure
- Differential Privacy (差分隐私) — statistical queries without individual exposure
- Trusted Execution Environment (可信执行环境/TEE) — process sensitive data in hardware enclave

**Why China CISOs care:** PET potentially solves the cross-border data deadlock — enable international collaboration without triggering CAC cross-border data transfer requirements.

### 14.3 Automotive / IoT Security (车联网/物联网安全)

Rapidly growing domain as China leads in EVs and smart cities:
- Connected vehicle data security (位置/行为/车内摄像头)
- V2X (Vehicle-to-Everything) communication security
- Smart city infrastructure protection
- Industrial IoT (工业互联网) security for 中国制造2025

### 14.4 Quantum-Readiness (量子安全)

Early but on the radar for forward-thinking CISOs:
- China's quantum computing advances (九章/祖冲之)
- Post-quantum cryptography transition planning
- 国密 algorithm quantum resistance evaluation
- Timeline: awareness now; planning 2026–2028; implementation 2028+

---

## §15 Key Differences from Western CISO

| Dimension | Western CISO | China CISO |
|-----------|-------------|-----------|
| Reporting line | Increasingly board-level / CEO direct | Usually CTO/CIO; rarely board access |
| Personal liability | Civil (lawsuits, SEC fines) | Criminal (detention, personal fines) |
| Primary driver | Business risk management | Regulatory compliance + personal survival |
| Board engagement | Quarterly board presentations | Rare; communicates through CTO |
| Budget authority | Often independent budget | Usually under CTO/CIO budget |
| Breach response | Customer notification priority | Government notification priority (24hr) |
| Cyber exercise | Voluntary (tabletop exercises) | Mandatory (护网 — real attacks by government red teams) |
| Vendor choice | Best-of-breed globally | Domestic-first (信创); political safety matters |
| Encryption standards | NIST standards (AES, RSA, SHA) | 国密 mandatory (SM2/SM3/SM4) + NIST for international |
| Compliance framework | NIST CSF, ISO 27001 (voluntary) | 等保2.0 (mandatory), three-law trinity (mandatory) |
| Talent pool | Specialized security career path | Generalist IT → security transition common |
| Tool ecosystem | Mature, integrated, competitive | Developing, fragmented, government-influenced |

---

## §16 Quick-Reference Summary

**One sentence:** The China CISO is a compliance-first, personally-liable security leader navigating mandatory government cyber exercises, forced domestic tool migration, and criminal accountability in ways that have no Western parallel.

**Top 5 things to remember:**
1. **Personal criminal liability** — This person's freedom is at stake. Understand their risk calculus.
2. **护网 drives budget** — The annual government cyber exercise is the single biggest budget trigger.
3. **等保 is non-negotiable** — Classified Protection assessment is mandatory law, not voluntary framework.
4. **信创 reshapes vendor landscape** — Domestic security products are mandatory in many contexts.
5. **Three-law trinity** — 网络安全法 + 数据安全法 + 个人信息保护法 form the regulatory foundation.

**What the China CISO loses sleep over:**
- "Will we pass 护网 this year?"
- "Am I personally liable if this breach happens?"
- "Can the domestic security tools actually stop a real attack?"
- "How do I get data out of China legally for our international business?"
- "My team is too small and underpaid for the threats we face."

---

*End of document. Total sections: 16. Archetypes: 5. Designed for AI agent consumption at all capability levels.*
