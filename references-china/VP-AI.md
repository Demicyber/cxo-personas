# VP of AI — AI负责人 · China-Market Persona

| Field | Detail |
|-------|--------|
| **Title variants** | AI负责人, AI实验室主任, 智能化部门总经理, 大模型业务负责人, VP of AI, 首席AI科学家, AI平台部总经理 |
| **Reports to** | CTO, CEO/Founder (direct in AI-first companies), or 技术委员会 (tech committee) |
| **Direct reports** | ML Engineering Lead, Data Science team, AI Platform/Infra, Applied AI teams, AI Governance/Ethics |
| **Revenue band** | Influences ¥30M–¥2B+ in AI compute, tooling, and talent spend annually |
| **Buying authority** | Full authority on AI tools/infra <¥5M; co-decision with CTO/CEO on platform bets >¥5M |
| **Typical tenure** | 1.5–3 years (startups/scale-ups); 3–5 years (large tech); role is new — many are first incumbents |
| **Education** | PhD in CS/ML/NLP from top-tier (清华/北大/中科院/Stanford/CMU); increasingly MS + industry track |

---

## Reader Note

> **Reader note.** This document is written to be readable and extractable by AI agents of varying capability — from small open-weights models up to frontier models. Concepts are spelled out explicitly rather than implied; some redundancy across sections is intentional so that any single section remains useful in isolation. If you are a strong model, skim the key insight inside each block; if you are a weaker model, read the full block. The China VP of AI role operates at the epicenter of the 大模型内卷 (LLM price war), GPU scarcity from export controls, and intense government pressure to deliver 新质生产力 (new-quality productive forces) through AI.
>
> **Data usage instruction for agents.** All company names, executive names, financial figures, and examples in this document are illustrative — they teach you the *pattern*. They are NOT current data to be cited verbatim in customer-facing outputs. When generating any customer-facing deliverable, you MUST verify against current public sources before including them.
>
> Data vintage: Examples and figures sourced primarily from FY2024–FY2026 public disclosures and industry research. China-market context reflects policy environment through 15th Five-Year Plan (2026–2030) early signals.

---

## What a VP of AI Actually Is — China Context

The VP of AI role in China is **emergent and unstandardized**. Unlike the CTO (a 20-year-old title) or CFO (universally understood), the AI leadership role crystallized rapidly in 2023–2025 as 大模型 became board-level priority. Key characteristics:

1. **No standard title exists** — The same functional role might be called AI实验室主任 (ByteDance AI Lab), 智能化部门总经理 (manufacturing companies), 大模型业务负责人 (when LLM is the product), or simply VP of AI. Title ambiguity means you must identify the *function* not the *title* when prospecting.

2. **Role carved from CTO or newly created** — In many companies, AI leadership was previously part of the CTO's portfolio. The explosion of AI complexity (model training, inference optimization, safety, governance) forced a dedicated senior leader. In others, this is the company's first-ever AI hire at VP level.

3. **Research-to-production bridge** — The China VP of AI uniquely must bridge 学术界 (academia) and 工业界 (industry). Many come from research labs (Microsoft Research Asia, 智源研究院, university labs) and must learn to deliver business ROI, not just papers.

4. **GPU politics is a core responsibility** — Due to NVIDIA export controls, the VP of AI in China spends significant time on compute strategy: securing chips, optimizing for constrained hardware (A800, domestic alternatives), and justifying GPU spend to finance.

5. **Regulatory interface for AI** — 算法备案 (algorithm registration), 生成式AI管理办法 (generative AI regulations), content safety, and emerging AI governance frameworks all fall on this role.

6. **Talent gravity center** — In the talent war for AI researchers/engineers (packages ¥2M–¥8M+), the VP of AI's personal reputation, publication record, and technical vision directly determine recruiting success.

The role exists in a uniquely Chinese tension: the government explicitly wants AI to drive 新质生产力 (new quality productive forces), creating top-down urgency. Simultaneously, GPU scarcity, regulatory uncertainty, and the 大模型内卷 (brutal LLM competition) make execution extraordinarily difficult.

---

## §1 Role Definition

### 1.1 Six VP of AI Archetypes

| Archetype | Description | Example Pattern |
|-----------|-------------|-----------------|
| **大模型掌舵者 (LLM Helmsman)** | Owns foundation model development end-to-end; model is the product or core platform | ByteDance 豆包/Doubao team; 智谱GLM; 月之暗面; MiniMax |
| **AI落地推动者 (AI Implementation Driver)** | Takes AI from demos to production ROI; measured on business metrics not model metrics | Shein demand prediction; Anker quality/design AI; 港交所 surveillance AI |
| **行业AI方案型 (Vertical AI Solutions)** | Builds industry-specific AI products/platforms; deep domain + AI intersection | 海康威视 industry vision AI; 理想 autonomous driving; 猎豹 robot intelligence |
| **AI平台架构师 (AI Platform Architect)** | Builds internal AI infrastructure — training platform, feature store, MLOps, model serving | ByteDance ML infra team; large companies needing to democratize AI internally |
| **AI治理合规型 (AI Governance & Compliance)** | Focuses on responsible AI, algorithm registration, safety, bias; emerging in regulated sectors | 港交所 AI governance; 腾讯 AI ethics; any company with public-facing generative AI |
| **全栈AI科学家 (Full-Stack AI Scientist)** | Research-to-deployment; common in smaller teams where one leader does everything | 猎豹 OrionStar (ASR/NLU/TTS full stack); Anker AI team; early-stage AI companies |

### 1.2 Diagnostic Table — Identifying the Archetype

| Signal | Likely Archetype |
|--------|-----------------|
| Company has published/launched its own 大模型 | 大模型掌舵者 |
| AI mentioned in earnings call as "productivity driver" | AI落地推动者 |
| Company sells AI-powered vertical products | 行业AI方案型 |
| Large engineering org; multiple AI teams need shared infra | AI平台架构师 |
| Regulated industry; recent 算法备案 filings | AI治理合规型 |
| Small-to-mid AI team (<100); leader has PhD + broad skills | 全栈AI科学家 |
| Multiple signals present | Blend — lead with dominant, acknowledge secondary |

### 1.3 Three Time Horizons

| Horizon | Timeframe | Focus | Example |
|---------|-----------|-------|---------|
| **H1: Ship and optimize** | 0–6 months | Model performance tuning, inference cost reduction, safety guardrails, immediate ROI proof | Shein improving demand prediction accuracy by 3%; 港交所 reducing false positive rate in surveillance |
| **H2: Platform and scale** | 6–18 months | MLOps maturity, model governance, expanding AI use cases, team scaling | ByteDance scaling 豆包 to 100+ internal applications; 海康威视 edge-cloud AI pipeline |
| **H3: Next paradigm** | 18–36 months | Multimodal models, AI agents, on-device AI, new architectures (Mamba/SSM), AGI preparation | 理想 L4 autonomy; 腾讯 AI NPCs becoming persistent agents; embodied AI for robotics |

### 1.4 Four-Way Pull

The China VP of AI is pulled in four directions simultaneously:

```
                    CEO / Board
                    "大模型进展怎么样了?"
                    "竞品都发布AI产品了"
                    "新质生产力怎么落地?"
                         │
                         ▼
    Research ◄────── VP of AI ──────► Business Units
    "We need 6 more months         │    "When can we use
     and 1000 GPUs to              │     AI in production?"
     match SOTA"                   │    "ROI of AI spend?"
    "Our paper was rejected,       │    "Competitors already
     team morale is low"           │     have AI features"
                         │
                         ▼
              Regulators / Compute Constraints
              "算法备案 deadline approaching"
              "GPU allocation insufficient"
              "生成式AI管理办法 compliance"
              "Training data audit required"
```

**CEO/Board Pull** — The board sees AI as existential (for both opportunity and threat). They demand visible progress, competitive parity, and a narrative for investors/analysts. "What's our AI strategy?" is asked every board meeting.

**Research Pull** — AI researchers want to publish papers, pursue interesting problems, and access frontier compute. They threaten to leave for 智谱/月之暗面/ByteDance if projects become "just engineering."

**Business Unit Pull** — Product and revenue teams want AI features *now*. They don't understand why the model hallucinates, why inference costs are high, or why it takes 6 months from prototype to production.

**Regulatory/Compute Pull** — 算法备案 requires documentation and filing for any public-facing algorithm. GPU scarcity means constant negotiation for compute budget. 生成式AI管理办法 mandates content filtering, data provenance, and user consent for generative AI.

---

## §2 Strategic Priorities

### Priority 1: Build vs. Buy vs. Fine-tune (The Defining Decision)

Every China VP of AI faces the foundational question: *"我们的大模型怎么搞？自建、买还是微调？"*

**The decision matrix:**

| Approach | When Appropriate | Cost Estimate | Example |
|----------|-----------------|---------------|---------|
| **Build foundation model from scratch** | Only if: (1) 1000+ GPU cluster, (2) top-10 AI talent team, (3) model IS the business | ¥100M–¥1B+ per year | ByteDance 豆包; 百度文心; 阿里通义千问 |
| **Fine-tune open-source base model** | Most common: leverage Qwen/DeepSeek/GLM + domain data + RLHF for specific use case | ¥5M–¥50M per year | 猎豹 聚言大模型 (fine-tuned for robotics); vertical industry applications |
| **API integration (buy inference)** | Fast deployment, non-core AI features, cost-sensitive | ¥500K–¥10M per year | Small companies adding AI chat; non-tech companies adding AI features |
| **Hybrid (build core + buy periphery)** | Most sophisticated approach; build where differentiation matters, buy everywhere else | Varies widely | 海康威视 (own CV + external LLM); 腾讯游戏 (own game AI + partner for NPC dialogue) |

**China-specific considerations for this decision:**

- **Open-source ecosystem is strong**: Qwen (阿里), DeepSeek (幻方), GLM (智谱), Yi (零一万物) provide world-class base models for free
- **Compute constraint forces efficiency**: Cannot throw GPUs at problems; must be clever with architecture, quantization, distillation
- **Data is the real moat**: China companies often have massive proprietary datasets (Shein: fashion trends; 海康: video data; ByteDance: user behavior) — the model architecture is commoditizing, data is not
- **Inference cost matters enormously**: 大模型内卷 has driven API pricing to near-zero (豆包 pricing war with 通义千问) — the battlefield is shifting from model quality to deployment efficiency

### Priority 2: GPU Strategy & Compute Optimization

GPU scarcity is the **defining constraint** for China AI leaders. US export controls restrict access to NVIDIA A100/H100/B100. Available options:

| Compute Option | Performance | Availability | VP of AI Consideration |
|----------------|-------------|--------------|----------------------|
| **NVIDIA A800/H800** | ~80% of A100/H100 | Available but price-inflated | Current workhorse; stockpiling |
| **华为昇腾 (Ascend)** | 70–90% for training; improving | Government-promoted; ecosystem gaps | Must evaluate; political pressure to adopt |
| **海光/寒武纪/壁仞** | Varies; 50–80% | Limited supply; software ecosystem immature | Monitor; not yet production-ready for large training |
| **Cloud AI services** | Varies | Available (阿里云/百度智能云/华为云) | Good for inference; expensive for training at scale |
| **Efficiency techniques** | N/A | Always available | Quantization, distillation, MoE, FlashAttention — critical skills |

**Compute strategy decisions the VP of AI makes:**
- How many GPUs to stockpile vs. rent (cloud)
- 昇腾 adoption timeline (government pressure vs. ecosystem readiness)
- Training vs. inference budget split (training is episodic; inference is ongoing)
- Multi-chip training frameworks (handling heterogeneous compute)
- Model architecture choices driven by hardware constraints (smaller but better models)

### Priority 3: AI落地 (Landing AI in Production)

The gap between AI demo and AI in production is where most China AI initiatives fail. The VP of AI is measured on "落地" — actual deployment generating business value.

**The AI落地 maturity ladder:**

| Level | Description | Metric | Example |
|-------|-------------|--------|---------|
| L0: Exploration | Research POCs; no production impact | Paper count, benchmark scores | University partnerships; hackathon projects |
| L1: Single use case | One AI feature in production | Feature-specific metrics | 港交所: one surveillance model live |
| L2: Multiple use cases | Several AI features deployed | Count of production models | Anker: quality prediction + design AI + customer insight |
| L3: AI-first workflow | Business processes redesigned around AI | Process efficiency gains | Shein: demand prediction drives entire supply chain |
| L4: AI platform | Democratized AI across organization | # of teams using AI platform | ByteDance: recommendation AI in every product |
| L5: AI-native business | AI IS the business model | Revenue directly from AI | 海康: AI vision solutions sold to customers |

**Common 落地 failure modes:**
- "Demo陷阱" (demo trap): Impressive POC but can't handle production edge cases
- "数据断层" (data disconnect): Model trained on clean data; production data is messy
- "工程欠账" (engineering debt): No MLOps; manual model deployment; no monitoring
- "组织隔阂" (organizational gap): AI team disconnected from business teams who should use AI

### Priority 4: AI Talent Strategy

AI talent in China is in extreme scarcity. The VP of AI spends 30–40% of time on talent.

| Talent Tier | Package Range (Annual) | Supply | VP of AI Strategy |
|-------------|----------------------|--------|-------------------|
| **顶级研究员** (Top researcher, publication record) | ¥3M–¥8M+ | <200 in China | Personal network; conference recruitment; equity-heavy |
| **高级算法工程师** (Senior ML engineer, 5+ years) | ¥1.5M–¥3M | Scarce | Compete with ByteDance/BAT; offer technical challenge + scope |
| **AI工程师** (ML engineer, 2–5 years) | ¥600K–¥1.5M | Moderate | University pipeline; internal training; open-source community |
| **AI产品经理** (AI PM, understands both sides) | ¥800K–¥2M | Very scarce | Cross-train from product or engineering background |
| **数据工程师** (Data engineer for AI pipelines) | ¥400K–¥800K | Available | Often overlooked but critical for 落地 success |

**China-specific talent dynamics:**
- ByteDance is the "talent black hole" — offers highest comp + most interesting problems
- 大模型创业潮 (LLM startup wave) pulls senior people out of large companies
- 海归 (returnees from US labs) face re-adjustment but bring global perspective
- "35岁焦虑" (age-35 crisis) creates perverse incentive: senior researchers fear being laid off
- Open-source contributions and paper publications are recruiting currency

### Priority 5: 算法备案 & AI Governance

Regulatory compliance for AI is a growing burden unique to China's market:

| Regulation | Scope | VP of AI Action Required |
|------------|-------|--------------------------|
| **算法备案 (Algorithm Registration)** | Any public-facing recommendation/generative algorithm | File with CAC; maintain documentation; subject to audit |
| **生成式AI管理办法** | Generative AI services available to public | Content filtering; training data records; user consent; labeling |
| **数据安全法 + 个保法** | AI training data collection and usage | Data provenance tracking; consent management; cross-border restrictions |
| **AI伦理治理** (emerging) | Bias, fairness, transparency | Internal governance frameworks; impact assessments |
| **行业监管** (sector-specific) | Finance (CSRC), automotive (MIIT), healthcare (NMPA) | Sector-specific AI safety and testing requirements |

**Governance organizational patterns:**
- Small companies: VP of AI handles governance personally (or delegates to one person)
- Large companies: Dedicated AI ethics/governance team reporting to VP of AI
- Regulated sectors: AI governance board with cross-functional membership (legal, AI, product, compliance)

### Priority 6: AI Safety & Content Security

For any company deploying generative AI to users, content safety is existential:

| Risk | Consequence | Mitigation |
|------|-------------|-----------|
| Political sensitivity | Service shutdown; corporate penalty; personal liability | Multi-layer content filtering; red-team testing with sensitive topics |
| Hallucination in high-stakes domains | Financial loss; medical harm; legal liability | RAG architectures; confidence scoring; human-in-the-loop for critical decisions |
| Data leakage via model | Training data extracted through prompts | Differential privacy; data sanitization; output monitoring |
| Deepfake/misinformation | Brand risk; regulatory action | Watermarking; provenance tracking; usage monitoring |

---

## §3 Key Performance Indicators

### 3.1 Model Performance KPIs

| KPI | Target Range | Context |
|-----|-------------|---------|
| Model accuracy on core task | Top-3 on industry benchmark or +X% vs. baseline | Shein: demand prediction MAPE; 海康: mAP on detection; 港交所: precision/recall on fraud |
| Inference latency (P99) | <100ms (real-time consumer); <500ms (batch acceptable) | 腾讯游戏 AI NPC responses; ByteDance recommendation |
| Model size / efficiency ratio | Smaller model matching larger model's quality | Critical under GPU constraints; distillation success metric |
| Training cost per experiment | Decreasing trend | GPU hours × price; compute efficiency improving |
| Hallucination rate | <1% (high-stakes); <5% (general) | Measured via red-team evaluation and production monitoring |

### 3.2 Business Impact KPIs

| KPI | Target Range | Context |
|-----|-------------|---------|
| AI-attributed revenue/savings | ¥10M–¥500M+ annually | Shein: supply chain savings from prediction; ByteDance: ad revenue from recommendation |
| AI feature adoption rate | >60% of target users actively using | Internal AI tools; customer-facing AI features |
| Time from POC to production | <3 months (simple); <9 months (complex) | Measures 落地 speed |
| Number of production AI models | Increasing; 5–50+ depending on company scale | Platform maturity indicator |
| AI cost per unit of business value | Decreasing | ¥ of AI infra spend per ¥ of attributed value |

### 3.3 Operational KPIs

| KPI | Target Range | Context |
|-----|-------------|---------|
| Model drift detection time | <24 hours | Production model degradation caught early |
| Model retraining frequency | Weekly to monthly | Fresh models on fresh data; automated pipeline |
| GPU utilization rate | >70% average | Expensive resource must be well-utilized |
| ML pipeline reliability | >99% successful runs | Training and inference pipeline uptime |
| 算法备案 compliance | 100% of in-scope algorithms registered | Zero regulatory violations |

### 3.4 Team & Talent KPIs

| KPI | Target Range | Context |
|-----|-------------|---------|
| Senior AI talent retention | >80% annual | In a market where competitors poach aggressively |
| Internal AI literacy (non-AI staff) | Increasing via training programs | Measures AI democratization success |
| Publications / patents | 10–50+ per year (large teams) | Recruiting signal + 高新企业 certification |
| Open-source contributions | Active maintenance of 1–3+ projects | Community reputation building |
| Time-to-fill for AI roles | <60 days (senior); <30 days (junior) | Recruiting pipeline health |

---

## §4 Pain Points

### 4.1 The 大模型内卷 Pressure

| Pain | Manifestation |
|------|---------------|
| "Everyone has a 大模型 now" | ByteDance/Baidu/Ali/智谱/MiniMax all offering competitive models; differentiation unclear |
| Pricing race to zero | API prices collapsing (豆包 pricing war); hard to justify internal model costs |
| FOMO-driven strategy | Board wants "our own 大模型" without clear use case; prestige project risk |
| Open-source makes building look easy | "Qwen is free, just fine-tune it" — ignores infrastructure, data, and operational costs |
| Moving target | New model releases every month invalidate previous technical decisions |

**Verbatim-style pain statement:** *"老板看到DeepSeek又发新模型了，问我为什么我们的模型效果还不如人家开源的。但人家烧了几十亿，我们全年AI预算才5000万。"*

### 4.2 GPU Scarcity & Compute Anxiety

| Pain | Manifestation |
|------|---------------|
| Cannot access frontier chips | H100/B100 export-banned; A800 supply tight and expensive |
| 昇腾 adoption pressure | Government wants domestic chip adoption; ecosystem immature; framework porting painful |
| Training budget blown on failed experiments | Each training run costs ¥500K–¥5M; failed experiments burn budget fast |
| Inference cost explosion | Model in production serving millions of users; inference GPU cost grows linearly |
| Compute hoarding vs. sharing | Teams stockpile GPU allocations; utilization drops; finance complains |

**Verbatim-style pain statement:** *"A800买不到足够的卡，昇腾的生态还不成熟，训练一次模型花几百万但效果不确定。我每天都在算GPU的账。"*

### 4.3 AI落地 Gap (Demo to Production)

| Pain | Manifestation |
|------|---------------|
| "90% accuracy sounds great until it's not" | 10% error rate in production = angry customers, brand damage |
| Production data ≠ training data | Model performs well on benchmarks, fails on real messy data |
| No MLOps infrastructure | Manual model deployment; no A/B testing; no monitoring; no rollback |
| Business teams don't trust AI output | "The model said X but I don't believe it" — human override 80% of time |
| ROI impossible to isolate | "Did revenue go up because of AI or because of the marketing campaign?" |

**Verbatim-style pain statement:** *"我们做了20个AI POC，真正上线产生价值的只有3个。老板开始质疑AI团队的ROI了。"*

### 4.4 Talent War

| Pain | Manifestation |
|------|---------------|
| ByteDance offers 2x compensation | Top researchers leave for ¥5M+ packages at ByteDance/startups |
| 大模型创业潮 pulls senior people | Best people leave to start/join LLM startups with equity upside |
| Research vs. engineering culture clash | Researchers want papers; engineers want production; VP must bridge both |
| Burnout from pace of change | AI moves so fast that teams feel perpetually behind; morale suffers |
| PhD students going directly to startups | Pipeline from 清华/北大/中科院 dries up as startups offer more exciting work |

### 4.5 Regulatory Uncertainty

| Pain | Manifestation |
|------|---------------|
| 算法备案 is operationally heavy | Documentation, filing, maintaining records; slows deployment |
| Rules change fast | 生成式AI管理办法 evolved rapidly; hard to build for moving target |
| Content safety is infinite scope | Cannot guarantee LLM won't produce problematic output; political risk is asymmetric |
| Cross-border AI restrictions | Model cannot be easily deployed globally; separate versions needed |
| Personal liability fear | Regulations increasingly hold individuals (not just companies) responsible |

### 4.6 Organizational Positioning

| Pain | Manifestation |
|------|---------------|
| "AI team vs. product team" turf war | Product teams want to own AI features; AI team wants end-to-end ownership |
| CTO relationship tension | AI splitting from CTO org creates political friction |
| Budget justification constant | "How much revenue did AI generate?" is asked every quarter |
| Centralized vs. embedded debate | Central AI team vs. AI engineers embedded in business units — both models have problems |
| CEO's AI literacy varies | Some CEOs are AI-savvy (ByteDance); others just want "magic" without understanding constraints |

---

## §5 Objection Patterns

### Objection 1: "我们有自己的AI团队" (We Have Our Own AI Team)

**Why they say it:**
- Technical pride — especially 大模型掌舵者 and 全栈AI科学家 archetypes
- Internal team's territory protection
- Belief that AI is core differentiation that must stay in-house
- Past experience: external AI solutions didn't work with their data

**Frequency:** 80%+ of conversations with companies that have >20 AI engineers

**Counter-framework:**

| Angle | Approach |
|-------|----------|
| **Layer separation** | "Your team builds the AI models. We provide the infrastructure/tooling layer beneath. Different layers, complementary" |
| **Opportunity cost** | "Your AI scientists cost ¥2M+ each. Are they spending time on MLOps/infrastructure or on model innovation? We free them to focus on differentiation" |
| **Scale challenge** | "Building training infra for 10 models is different from 100. We've solved the scale problems you'll hit in 6 months" |
| **Speed** | "Your team can build this platform in 18 months. We get you there in 3. What's 15 months of competitive advantage worth?" |

### Objection 2: "开源方案够用了" (Open-Source Is Sufficient)

**Why they say it:**
- Qwen/DeepSeek/GLM are genuinely excellent and free
- Team prefers tools they can modify/understand internals
- Cost pressure — "why pay when free exists?"
- Community reputation from contributing to OSS

**Counter-framework:**

| Angle | Approach |
|-------|----------|
| **Production gap** | "Open-source gives you the model. Who gives you serving at scale, monitoring, A/B testing, rollback, and 99.9% SLA?" |
| **TCO honesty** | "Running Qwen-72B in production: GPU cost, engineering time for optimization, safety filters, monitoring — calculate the real annual cost" |
| **Complement, don't replace** | "We love that you use DeepSeek. Our platform makes deploying and managing it in production 10x easier" |
| **Enterprise features** | "算法备案 documentation, audit trails, content safety filters, access control — the 20% that takes 80% of engineering time" |

### Objection 3: "GPU太贵了/预算不够" (GPUs Too Expensive / Budget Insufficient)

**Why they say it:**
- AI compute costs are genuinely shocking to finance teams
- ROI of AI investment is hard to prove upfront
- Competing with other business units for capital
- GPU scarcity makes pricing unpredictable

**Counter-framework:**

| Angle | Approach |
|-------|----------|
| **Efficiency = cost reduction** | "Our optimization reduces your inference cost by 40%. That's ¥X million saved per year — we pay for ourselves" |
| **GPU utilization** | "Your current GPU utilization is likely 30–50%. We get it to 80%+. That's like getting 60% more GPUs for free" |
| **Phased investment** | "Start with inference optimization (immediate savings). Fund training investments from the savings" |
| **Business case support** | "Let us help you build the ROI case for the CFO. Here's how [similar company] justified their AI budget" |

### Objection 4: "合规风险太大" (Compliance Risk Too High)

**Why they say it:**
- 生成式AI管理办法 creates genuine uncertainty
- Content safety failures could shut down the service
- Personal liability concerns for AI leaders
- Regulatory landscape changing rapidly

**Counter-framework:**

| Angle | Approach |
|-------|----------|
| **Compliance built-in** | "Our platform includes 算法备案 documentation generation, content safety filters, and audit trail — compliance by default" |
| **Risk reduction** | "Deploying without proper guardrails is the real risk. We provide the safety infrastructure your compliance team needs" |
| **Reference customers** | "Here's how [regulated-industry customer] passed their AI audit using our governance tools" |
| **Incremental deployment** | "Start with internal use cases (no 算法备案 needed). Prove value, build confidence, then extend to public-facing" |

### Objection 5: "我们还在探索阶段" (We're Still in Exploration Phase)

**Why they say it:**
- Genuinely haven't decided on AI strategy yet
- Overwhelmed by options (dozens of 大模型 to choose from)
- Waiting for the market to consolidate
- Internal alignment not yet achieved

**Counter-framework:**

| Angle | Approach |
|-------|----------|
| **Exploration accelerator** | "We help you evaluate faster. POC in 2 weeks instead of 2 months. Explore more options in less time" |
| **Competitor urgency** | "Your competitors moved past exploration 6 months ago. [Competitor X] is already in production. Exploration has a shelf life" |
| **Low-risk start** | "Exploration ≠ commitment. A 2-week technical evaluation costs nothing but gives you data for the real decision" |
| **Framework, not answer** | "We don't prescribe your strategy. We give you the infrastructure to execute *whatever* strategy you choose" |

---

## §6 Buying Dynamics

### 6.1 Decision Process

```
Trigger Event (CEO asks "where's our AI?", competitor launches AI, board pressure)
         │
         ▼
AI Strategy Formulation (VP of AI + CTO, 4-8 weeks)
"Build vs. buy vs. fine-tune? Which use cases first?"
         │
         ▼
Technical Landscape Assessment (AI team researches, 2-4 weeks)
"What models? What infra? Open-source vs. commercial?"
         │
         ▼
POC / Benchmark (AI engineers, 4-8 weeks)
"Does it work on our data? What's the performance? Cost?"
         │
         ▼
Production Readiness Evaluation (AI + Engineering, 2-4 weeks)
"Can it scale? Is it reliable? Compliance-ready?"
         │
         ▼
Business Case & Approval (VP AI + CTO + CFO, 2-4 weeks)
"ROI projection, TCO, strategic value narrative"
         │
         ▼
Procurement (采购 for >¥5M; VP AI autonomous for <¥5M)
         │
         ▼
Deployment & Integration (phased, 2-6 months)
```

### 6.2 Buying Committee

| Role | Influence | Concern |
|------|-----------|---------|
| **VP of AI** | Primary decision maker (technical + strategic) | Model quality, team productivity, production readiness, talent retention |
| **CTO** | Approval authority; architectural alignment | Fits overall tech strategy; doesn't create tech debt; 信创 alignment |
| **CEO/Founder** | Veto power; strategic direction setter | Competitive positioning; investor narrative; speed |
| **AI Team Lead / Chief Scientist** | Key evaluator (hands-on testing) | Technical depth; benchmark results; ease of use |
| **CFO / Finance** | Budget holder | TCO; ROI timeline; cost predictability |
| **Legal / Compliance** | Gate-keeper for regulated use cases | 算法备案; data usage rights; liability |
| **Business Unit Head** | Demand-side requester | "When can I have AI in my product?" |

### 6.3 Influence Map — By Archetype

| VP of AI Archetype | Key Influencer to Also Engage |
|-------------------|-------------------------------|
| 大模型掌舵者 | Chief Scientist / Research Lead — they'll run deep technical evaluation |
| AI落地推动者 | Business Unit Head — they define "success" in business terms |
| 行业AI方案型 | Domain experts (e.g., 自动驾驶 lead at 理想; vision algorithm lead at 海康) |
| AI平台架构师 | Infrastructure/DevOps team — they'll evaluate operational burden |
| AI治理合规型 | Legal + Government Affairs team — compliance is their north star |
| 全栈AI科学家 | The VP of AI IS the evaluator — convince them technically and it's done |

### 6.4 Budget Patterns

| Company Type | AI Budget Range | Approval Speed | Notes |
|--------------|----------------|----------------|-------|
| AI-native startup (智谱, 月之暗面) | ¥100M–¥1B+ (VC-funded) | Days–weeks | Speed is everything; burn rate is expected |
| Large tech AI division (ByteDance, 腾讯) | ¥500M–¥5B+ | 2–4 weeks | Large budgets but bureaucracy; multiple approvals |
| Tech company AI team (Shein, 猎豹, Anker) | ¥20M–¥200M | 2–6 weeks | VP of AI has discretion for smaller items |
| Traditional company AI initiative (海尔-type) | ¥10M–¥100M | 4–12 weeks | ROI scrutiny is intense; new budget line item |
| Regulated/Exchange (港交所) | ¥50M–¥500M | 3–6 months | Extensive vendor assessment; board approval |

### 6.5 Vendor Selection Criteria (Ranked by VP of AI Priority)

1. **Technical performance** — Benchmark results on *their* data and use case (not generic leaderboards)
2. **Production readiness** — Not just a model, but serving, monitoring, safety, scalability
3. **Compute efficiency** — Runs well on available hardware (A800, 昇腾); doesn't require H100
4. **Integration effort** — Days not months; API-first; compatible with existing ML stack
5. **Team adoption** — Engineers like using it; good docs (Chinese language); active community
6. **Compliance support** — 算法备案 documentation; content safety; audit trail
7. **Vendor AI expertise** — Do they understand our domain? Can their team talk to our AI scientists?
8. **Cost structure** — Predictable pricing; scales economically; no GPU cost surprises
9. **Open-source alignment** — Core is inspectable/modifiable; not black-box dependency
10. **Roadmap alignment** — Where is this product going? Does it match our 18-month plan?

---

## §7 Discovery Questions

### 7.1 Opening Questions (Build Rapport + Understand Context)

| # | Question | What You Learn |
|---|----------|----------------|
| 1 | "您现在AI团队的组织架构是怎么样的？大概多少人？研究和工程怎么分？" | Team structure, maturity, research vs. engineering balance |
| 2 | "您的大模型策略是怎么定的？自建、微调还是调用？用的什么底座模型？" | Foundation model strategy, technical choices, build-vs-buy stance |
| 3 | "目前AI在业务中最成功的落地场景是什么？" | AI maturity level, proven value areas, what's working |
| 4 | "GPU资源现在够用吗？用的什么卡？昇腾有在考虑吗？" | Compute constraints, hardware strategy, domestic chip pressure |
| 5 | "您觉得AI团队现在最大的瓶颈在哪里？是算力、数据、人才还是落地？" | Core pain point identification |

### 7.2 Pain-Probing Questions

| # | Question | Pain Point Targeted |
|---|----------|---------------------|
| 6 | "从POC到生产上线，一般需要多长时间？有什么卡点？" | 落地 gap; MLOps maturity |
| 7 | "算法备案和合规这块，您团队花多少精力在上面？" | Regulatory burden quantification |
| 8 | "AI工程师的流失率怎么样？主要流向哪里？" | Talent pain; competition landscape |
| 9 | "训练一次模型的成本大概是多少？失败率呢？" | Compute cost pain; experimentation efficiency |
| 10 | "业务部门对AI的期望和实际交付之间，gap大吗？" | Organizational alignment; expectation management |

### 7.3 Technical Deep-Dive Questions

| # | Question | What You Learn |
|---|----------|----------------|
| 11 | "您现在的MLOps成熟度怎么样？模型从训练到上线的流程是全自动还是手动？" | Infrastructure maturity; automation level |
| 12 | "推理优化做到什么程度了？用了哪些技术？量化、蒸馏、MoE？" | Technical sophistication; efficiency focus |
| 13 | "数据飞轮建起来了吗？生产数据怎么回流到训练？" | Data infrastructure maturity; continuous improvement |
| 14 | "多模态（视觉+语言+语音）是分开的团队还是统一架构？" | Technical architecture; integration level |
| 15 | "模型安全和内容过滤是怎么做的？有专门的red team吗？" | Safety maturity; governance investment |

### 7.4 Decision-Process Questions

| # | Question | What You Learn |
|---|----------|----------------|
| 16 | "AI相关的技术选型，您自己能定还是需要CTO/CEO确认？" | Authority level; buying process |
| 17 | "之前有没有评估过外部AI平台/工具？什么因素最影响决策？" | Historical buying pattern; decision criteria |
| 18 | "AI预算是独立的还是在CTO预算里面？明年预算定了吗？" | Budget structure; timing |
| 19 | "POC的成功标准一般怎么定？谁来判断？" | Evaluation criteria; decision maker |
| 20 | "如果要引入新工具，您团队的评估流程大概多久？" | Timeline; process complexity |

---

## §8 Communication Style

### 8.1 General Preferences

| Dimension | China VP of AI Preference |
|-----------|--------------------------|
| **Depth** | Extremely technical; expects ML/AI-native conversation (discuss architectures, not just features) |
| **Language** | Heavy English technical vocabulary in Chinese conversation; "attention mechanism", "RLHF", "quantization" used directly |
| **Format** | Technical papers > slides; benchmark results > marketing claims; architecture diagrams > feature lists |
| **Meeting style** | Prefer technical depth with 1–2 people; hate being "sold to" — want peer-level technical exchange |
| **Communication channel** | 微信 for quick questions; 飞书/Slack for team coordination; technical docs shared via GitHub/飞书文档 |
| **Proof** | "Show me the benchmark on my data" / "Can I see the training curve?" / "What's the inference latency?" |
| **Decision pace** | Fast for tools <¥1M if technically convinced; slow for platform decisions (6+ months) |
| **Trust building** | Technical credibility is 90% of trust; published papers/open-source from your team matter enormously |

### 8.2 Archetype-Specific Communication

| Archetype | Preferred Approach |
|-----------|-------------------|
| **大模型掌舵者** | Discuss model architecture trade-offs; reference latest papers; speak about scaling laws and data quality |
| **AI落地推动者** | Lead with business metrics achieved; production case studies; ROI frameworks; time-to-value |
| **行业AI方案型** | Domain expertise required; understand their specific vertical deeply; industry benchmarks |
| **AI平台架构师** | System design conversation; distributed systems; MLOps architecture; scale challenges |
| **AI治理合规型** | Governance frameworks; compliance automation; risk quantification; regulatory roadmap |
| **全栈AI科学家** | Breadth + depth; be ready to discuss anything from data pipelines to transformer architecture |

### 8.3 What Works

| ✅ Do | Example |
|-------|---------|
| Demonstrate AI-native expertise | "We use grouped-query attention with 4-bit GPTQ quantization to achieve X tokens/sec on A800" |
| Bring reproducible benchmarks | "Here's our benchmark script. Run it on your cluster. We'll match or beat [competitor] on your workload" |
| Reference cutting-edge research | "Building on the insights from [recent paper], our approach to [problem]..." |
| Acknowledge compute constraints | "We designed this to run efficiently on A800. Here's performance on 昇腾 too" |
| Offer hands-on POC on their data | "Give us your evaluation dataset. We'll show results in 1 week. No commitment" |
| Connect to business metrics | "For [similar company], this translated to ¥XM in savings / Y% accuracy improvement" |
| Show your team's credentials | "Our chief scientist published at NeurIPS/ICML; our engineering team built [known system]" |

### 8.4 What Doesn't Work

| ❌ Don't | Why |
|----------|-----|
| Talk only about model size / parameter count | VP of AI knows bigger ≠ better; they care about efficiency and task performance |
| Use generic AI marketing language | "AI-powered", "intelligent", "next-gen" — meaningless to someone who builds AI |
| Ignore their existing technical stack | They've already invested heavily; show how you complement, not replace |
| Dismiss open-source (Qwen/DeepSeek/GLM) | They likely use open-source already; you must articulate value *beyond* what's free |
| Bring non-technical salespeople to first meeting | They want to talk to your engineers/researchers, not account executives |
| Overclaim benchmark results | They will reproduce your benchmarks; any exaggeration destroys trust permanently |
| Ignore China-specific constraints (GPU, compliance) | Solutions requiring H100 or ignoring 算法备案 show ignorance of their reality |
| Present one-size-fits-all solutions | Their use case is specific; generic demos waste their time |

### 8.5 Meeting Cadence Preferences

| Stage | Preferred Format | Duration | Attendees |
|-------|-----------------|----------|-----------|
| Initial technical exchange | 微信/飞书 async; share technical doc or paper | — | Your AI engineer ↔ Their AI lead |
| Technical deep-dive | Video or in-person | 90–120 min | Your ML team ↔ Their ML team |
| Benchmark/POC setup | In-person workshop | Half-day | Engineering teams both sides |
| POC results review | Video + jupyter notebook walkthrough | 60 min | VP AI + team |
| Strategic alignment | In-person (for large deals) | 60 min | VP AI + CTO (your side: technical leader + account) |
| Ongoing | Bi-weekly technical sync + quarterly business review | 30/60 min | Account team ↔ AI team |

### 8.6 Content That Resonates

| Content Type | Engagement Level | Notes |
|--------------|-----------------|-------|
| Technical paper / research report | ⭐⭐⭐⭐⭐ | Especially if addressing their specific challenge |
| Benchmark comparison (reproducible) | ⭐⭐⭐⭐⭐ | Must include methodology; cherry-picked results backfire |
| Open-source project / GitHub repo | ⭐⭐⭐⭐⭐ | Shows engineering depth; they'll read the code |
| Architecture deep-dive blog post | ⭐⭐⭐⭐ | Written by engineers, not marketing |
| Case study with technical detail | ⭐⭐⭐⭐ | Must include architecture, metrics, lessons learned |
| Conference talk (technical) | ⭐⭐⭐ | Good for awareness; ACL/NeurIPS/ICML carry weight |
| Product demo video | ⭐⭐⭐ | Useful but they want to try themselves, not watch |
| Marketing brochure | ⭐ | Actively counterproductive for this audience |

---

## §9 Competitive Landscape Awareness

### 9.1 The 大模型内卷 Map (What the VP of AI Tracks Daily)

| Player | Model | Strength | VP of AI's View |
|--------|-------|----------|-----------------|
| **ByteDance** | 豆包/Doubao | Scale + integration + aggressive pricing | "They'll bundle free AI into everything" |
| **阿里** | 通义千问/Qwen (open-source) | Best open-source; full family (0.5B–110B) | "Why pay if Qwen is free and good?" |
| **百度** | 文心一言/ERNIE | First-mover; strong API ecosystem | "Good but losing lead; not open-source" |
| **智谱** | GLM/ChatGLM | Academic pedigree (清华); bilingual | "Solid for Chinese; good enterprise support" |
| **DeepSeek** | DeepSeek-V2/V3 | Efficiency (MoE); strong open-source | "Remarkable efficiency; setting new bar" |
| **月之暗面** | Kimi | Long context; consumer product | "Good product but narrow focus" |
| **MiniMax** | abab | Multimodal; creative applications | "Interesting for specific use cases" |
| **腾讯** | 混元/Hunyuan | Gaming AI; enterprise integration | "Gaming-strong; general capabilities catching up" |

### 9.2 What VP of AI Benchmarks Against

The VP of AI constantly compares their AI capabilities to peers:

- **Model quality**: "Are we matching Qwen-72B / DeepSeek-V2 on our domain?"
- **Inference efficiency**: "Are we achieving X tokens/sec/GPU like ByteDance claims?"
- **落地 breadth**: "How many production AI use cases do we have vs. competitors?"
- **Talent quality**: "Are we publishing at top venues? Can we attract from 智谱/月之暗面?"
- **Compute efficiency**: "Are we getting more FLOPS per yuan than industry average?"

---

## Appendix A: Account-Specific VP of AI Engagement Notes

| Account | VP of AI Archetype | Key AI Context | Engagement Angle |
|---------|--------------------|----------------|------------------|
| **ByteDance** | 大模型掌舵者 + AI平台架构师 | 豆包 foundation model; recommendation AI at massive scale; global AI research labs | They build everything; sell infra efficiency or niche capability they won't build |
| **海康威视** | 行业AI方案型 + AI平台架构师 | 10K+ AI engineers; edge AI; own chip design (海思); industry vision solutions | Understand edge constraints; complement (not compete with) their CV capabilities |
| **理想汽车** | 行业AI方案型 (autonomous driving) | Full-stack AD AI; 理想同学 AI assistant; manufacturing AI | Domain-specific conversation; safety-critical AI; real-time inference |
| **猎豹/OrionStar** | 全栈AI科学家 + 大模型掌舵者 | 聚言大模型; ASR/NLU/TTS full-stack; robot deployment at scale | Full-stack AI depth; robotics-specific (latency, embodied); edge inference |
| **Shein** | AI落地推动者 | Demand prediction; trend detection; supply chain optimization; at-scale ML | Business metrics obsessed; efficiency at scale; real-time prediction |
| **Anker** | AI落地推动者 + 全栈AI科学家 | Product design AI; customer insight; quality prediction; smaller AI team | Practical tools; immediate ROI; help small team punch above weight |
| **港交所** | AI治理合规型 + AI落地推动者 | Market surveillance AI; NLP for regulatory filings; fraud detection | Compliance-first; explainability; low false positive rate; governance tools |
| **腾讯游戏** | 大模型掌舵者 + AI平台架构师 | AI NPCs (Hunyuan LLM); GiiNEX AI game dev platform; anti-cheat ML | Real-time AI; massive concurrency; creative AI; game-specific benchmarks |

---

## Appendix B: Seasonal Timing Guide

| Period | VP of AI Behavior | Sales Implication |
|--------|-------------------|-------------------|
| **Q1 (Jan–Mar)** | New year AI strategy finalized; kicking off major training runs; hiring plans confirmed | Best time to engage on platform/infra decisions for the year |
| **Post-两会 (Mar–Apr)** | New AI policy signals from government; 新质生产力 directives clarify | Reference new policy to create urgency; align with government direction |
| **Conference season (May–Jul)** | ICML, ACL prep; team distracted by submissions/travel; hiring from graduates | Technical content marketing peaks; sponsor/attend conferences |
| **H2 planning (Jul–Aug)** | Mid-year AI strategy review; adjust plans based on H1 results | Re-engage on tools/platforms that address H1 gaps |
| **NeurIPS/AAAI prep (Sep–Oct)** | Research teams focused on submissions; applied teams on Q4 delivery | Engage applied/落地 teams (research teams distracted) |
| **Budget season (Nov–Dec)** | Planning next year's AI budget; justifying GPU spend; headcount requests | Critical: get into next year's AI budget; help build ROI case |
| **大模型 release cycles (ongoing)** | Every major model release triggers "should we switch?" evaluation | Time outreach around major releases (Qwen update, DeepSeek release, etc.) |

---

## Appendix C: Glossary of Key Terms

| Term | Pinyin | English | Relevance |
|------|--------|---------|-----------|
| 大模型 | Dà móxíng | Large Language Model (LLM) / Foundation Model | Core of VP of AI's strategic responsibility |
| 大模型内卷 | Dà móxíng nèijuǎn | LLM price/quality war | Competitive pressure from dozens of Chinese LLM providers |
| AI落地 | AI luòdì | AI implementation / landing in production | The #1 metric: moving from demos to business value |
| 算法备案 | Suànfǎ bèi'àn | Algorithm registration (with CAC) | Regulatory requirement for public-facing AI algorithms |
| 新质生产力 | Xīnzhì shēngchǎnlì | New-quality productive forces | Government policy explicitly prioritizing AI adoption |
| 算力 | Suànlì | Compute power | GPU/AI chip resources; strategic constraint |
| 昇腾 | Shēngténg | Huawei Ascend (AI chips) | Domestic alternative to NVIDIA; adoption pressure |
| 智算中心 | Zhì suàn zhōngxīn | Intelligent computing center | Government-backed AI compute infrastructure |
| 生成式AI管理办法 | Shēngchéngshì AI guǎnlǐ bànfǎ | Generative AI management measures | Regulation governing generative AI services |
| AI治理 | AI zhìlǐ | AI governance | Emerging framework for responsible AI deployment |
| 微调 | Wēi tiáo | Fine-tuning | Adapting base models to specific tasks/domains |
| 蒸馏 | Zhēngliù | Knowledge distillation | Making smaller models learn from larger ones |
| 量化 | Liànghuà | Quantization | Reducing model precision for efficiency (INT8/INT4) |
| 推理 | Tuīlǐ | Inference | Running trained models in production |
| 训练 | Xùnliàn | Training | Building/updating models (high GPU cost) |
| 数据飞轮 | Shùjù fēilún | Data flywheel | Virtuous cycle: product → data → better model → better product |
| 产学研 | Chǎn-xué-yán | Industry-academia-research collaboration | Talent pipeline; co-funded research |
| 开源生态 | Kāiyuán shēngtài | Open-source ecosystem | Qwen, DeepSeek, GLM, Yi — China's vibrant open-source AI |
| 海归 | Hǎiguī | Overseas returnee | AI talent returning from US/UK labs |
| 信创 | Xìnchuàng | IT localization (Xinchuang) | Domestic technology adoption mandate; affects AI infra choices |

---

## Appendix D: The VP of AI's Decision Framework for Build vs. Buy

This mental model governs how the VP of AI evaluates any external AI tool, platform, or service:

```
                    ┌─────────────────────────────────────┐
                    │ Is this CORE AI differentiation?     │
                    │ (what makes our AI better than       │
                    │  competitors' AI)                    │
                    └──────────┬────────────┬─────────────┘
                               │            │
                          YES  │            │  NO
                               ▼            ▼
                    ┌──────────────┐  ┌──────────────────┐
                    │ BUILD        │  │ Is it available   │
                    │ in-house     │  │ as quality        │
                    │ (protect IP) │  │ open-source?      │
                    └──────────────┘  └───┬─────────┬────┘
                                          │         │
                                     YES  │         │  NO
                                          ▼         ▼
                               ┌──────────────┐ ┌────────────────┐
                               │ USE OPEN-    │ │ BUY if:        │
                               │ SOURCE +     │ │ • Saves >6mo   │
                               │ customize    │ │ • Team can't   │
                               │              │ │   maintain      │
                               │ (If team can │ │ • Vendor adds   │
                               │  maintain)   │ │   10x value    │
                               └──────────────┘ └────────────────┘
```

**Examples of "core differentiation" by company:**
- ByteDance: Recommendation algorithm = build. MLOps tooling = could buy.
- 海康威视: Computer vision models = build. Data labeling platform = could buy.
- Shein: Demand prediction models = build. Model serving infrastructure = could buy.
- 港交所: Market surveillance logic = build. NLP model for filings = fine-tune/buy.

**Key insight for sellers:** Position below the differentiation line. You provide infrastructure, tooling, or peripheral AI capabilities — not the core model that makes their product special.

---

*Last updated: 2025-01. Based on research across AI-native companies, tech companies with AI divisions, and traditional companies building AI capabilities in Greater China. Role boundaries are evolving rapidly as 大模型 matures from hype to production.*
