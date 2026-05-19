---
name: chen-jing-analysis
description: Apply Chen Jing's (风云学会陈经) distilled analytical framework to analyze complex topics — economics, geopolitics, markets, and technology. Use this skill whenever the user asks to analyze a market, asset price, geopolitical situation, technology competition, or any complex multi-factor problem — even if they don't explicitly say "陈经" or "analysis framework". Also use when the user mentions "蒸馏分析", "用陈经方法", "分析走势", "利益地图", or asks for structured reasoning on economic or geopolitical topics. Uses 6 core methods: data verification (数据打假), interest mapping (利益地图), structural analysis (结构分析), historical analogy (历史类比), multi-factor synthesis (多因素综合), and game theory perspective (博弈视角).
---

# 陈经分析法 (Chen Jing Analysis Framework)

A distilled analytical methodology based on ~169 articles from Chinese macro-analyst **陈经 (Chen Jing)** of 风云学会. Apply this framework to analyze any complex topic — markets, geopolitics, technology, or social trends.

## When to use

Invoke this skill when the user asks to:
- Analyze a market, asset price, or economic trend
- Evaluate a geopolitical situation or country's prospects
- Assess a technology competition or industry shift
- Break down a complex multi-factor problem with a structured framework
- Apply "陈经方法论" or "distilled analysis" to any topic

## The 6-Layer Analysis Framework

Apply these six layers **sequentially**, each building on the last.

---

### Layer 1: 数据打假 — Data Verification

**Core question:** Is the data real? Who published it? What is their incentive?

Steps:
1. Identify the primary claims or data points being presented
2. Check: Who collected this data? What is their interest?
3. Find a **cross-validating indicator** that should correlate — does it?
4. Strip out one-time items, accounting tricks, or statistical biases
5. State the **adjusted real figure**

**Red flags to watch for:**
- Sample selection bias (e.g., OpenRouter ≠ global AI token market)
- Accounting techniques (e.g., capex capitalization inflating net margins)
- Institutional estimates based on adversarial sources (e.g., US defense estimates of North Korean military)
- Conflating long-term targets with current state

---

### Layer 2: 利益地图 — Interest Mapping

**Core question:** Who benefits? Who loses? What drives each actor's behavior?

Steps:
1. List all key actors involved
2. For each actor, identify:
   - **Face needs** (political/social narrative they must maintain)
   - **Real needs** (economic/strategic actual interests)
   - **Loss tolerance** (what would they sacrifice vs. never sacrifice)
3. Classify actors: structural (price-insensitive, long-term) vs. cyclical (price-sensitive, short-term)
4. Identify **asymmetries**: who has more staying power?

---

### Layer 3: 结构分析 — Structural Analysis

**Core question:** What are the underlying production/competitive forces?

The central axiom: **Whoever can produce more, cheaper, and better wins in the long run.**

Apply:
- **The "Solar Panel Path":** Large-scale investment → cost collapse → pricing power destruction → winner-takes-all
  - Ask: Is any player following this path in this domain?
- **Moat analysis:** What protects current leaders? How durable is it?
- **Bottleneck identification:** What is the single constraint blocking the challenger? (e.g., EUV lithography machines)
- **Timeline estimation:** When will the bottleneck break? What are the signals?

---

### Layer 4: 历史类比 — Historical Analogy

**Core question:** What is the closest historical precedent? What can we learn from it?

Steps:
1. Identify **2-3 historical analogies** (prefer recent, prefer same domain)
2. For each analogy, state:
   - **Core similarities** (why it's comparable)
   - **Key differences** (where the analogy breaks down)
   - **The lesson** (what outcome followed, and why)
3. Weight the analogies by similarity score (★★★★★)
4. Extract the **calibrated baseline expectation**

---

### Layer 5: 多因素综合 — Multi-Factor Synthesis

**Core question:** What are ALL the forces at play, and how do they interact?

Steps:
1. List every relevant factor (aim for 5-8)
2. For each factor, assess:
   - **Direction** (bullish ↑ / bearish ↓ / neutral)
   - **Strength** (★ to ★★★★★)
   - **Variability** (Low / Medium / High)
3. Identify **resonance clusters**: which factors are currently amplifying each other?
4. Identify the **dominant factor** — the one that, if it changes, changes everything
5. State: what does a reversal of the dominant factor look like?

---

### Layer 6: 博弈视角 — Game Theory Perspective

**Core question:** If I stand in each player's position, what is their optimal move?

Steps:
1. For each key player, model their decision space
2. Find the solution that **satisfies each player's minimum requirements** simultaneously
3. Identify the **"face-saving deal"** structure: what lets each party claim victory publicly while accepting the real outcome privately?
4. Ask: Who has more **patience** (time preference)? That party has structural advantage.

---

## Output Format

Always structure the output as:

```
## [Topic] — 陈经式分析

### 当前基线（Data Verification）
[Verified facts, corrected figures]

### 利益地图
[Table of actors, their face needs, real needs]

### 结构力量
[Production logic, moat analysis, bottleneck]

### 历史类比
[Best analogy + similarity rating + lesson]

### 多因素评估
[Factor table: direction, strength, variability]
[Current resonance clusters]

### 博弈推演
[Each player's optimal move + most likely deal structure]

### 综合判断（Probabilistic）
**不能赌博式判断**:
- Path A [XX%]: [description + target]
- Path B [XX%]: [description + target]
- Path C [XX%]: [description + target]

### 关键监测信号
**向上修正的触发器:**
- [Signal 1]
- [Signal 2]

**向下修正的触发器:**
- [Signal 1]
- [Signal 2]
```

---

## Core Cognitive Principles (Meta-Rules)

These govern HOW to think, not just what to analyze:

1. **概率论 not 赌博论**: Never say "will definitely happen." Always assign probability ranges. Update them when signals change.

2. **自我纠错优先**: If previous analysis was wrong, explicitly state: what was wrong, why it was wrong, and what the updated model is. Never quietly abandon a wrong prediction.

3. **运气 vs 结构分离**: For any outcome, explicitly separate structural factors (repeatable, generalizable) from luck factors (non-repeatable, context-specific).

4. **数据驱动 not 立场驱动**: Seek disconfirming evidence. The goal is to track reality, not to defend a position.

5. **死局识别**: When every available option has severe costs, identify this as a "dead-end game" and focus on "least-bad" outcome rather than searching for a perfect solution.

---

## Examples

### Example: Analyzing a commodity price

**User:** "Analyze gold prices for the next 6 months using Chen Jing's method"

**Response structure:**
1. Data verification: Current price, ATH, correction %, who is publishing what forecasts
2. Interest map: Central banks (structural buyers, price-insensitive) vs. speculators (cyclical, price-sensitive)
3. Structural analysis: Gold = inverse of dollar credibility; USD credibility erosion thesis
4. Historical analogy: 2020 August ATH → 19% correction → recovery pattern
5. Multi-factor: Rate expectations, dollar index, central bank buying, geopolitics, ETF flows
6. Game theory: Fed's dead-end (cut = inflation, hold = recession, do nothing = bond market decides)
7. 3-path probabilistic output with trigger signals

### Example: Analyzing a technology competition

**User:** "Will China's AI catch up to the US in 2 years?"

Framework focus: Structural analysis (bottleneck = EUV lithography) + Historical analogy (solar panel path applied to semiconductors) + Multi-factor (DeepSeek algorithm efficiency vs. hardware gap) + Probabilistic paths

---

## Quality Assurance

After completing a full 6-layer analysis draft, read **`references/self-check.md`** and run through:
1. **Pre-flight checklist** — verify each layer meets quality standards before outputting
2. **Prediction tracker template** — fill in and save if the analysis contains time-bound predictions
3. **Post-mortem template** — use when a past prediction is proven wrong

The self-check reference also contains Chen Jing's own error correction case study as a model for how to handle wrong predictions.

---

## References

- `references/self-check.md` — Output quality checklist, prediction tracker, and post-mortem templates
- `examples/gold-price-analysis-example.md` — Full worked example: gold 6-month forecast
- `examples/methodology-reference.md` — Deep methodology reference with all 6 layers explained
- Original analysis source: 头条号「风云学会陈经」(~169 articles, May 2026)
- Distillation author: Antigravity AI (SharkTal), 2026-05-18
