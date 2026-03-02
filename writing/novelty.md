# What Counts as Novelty in Academic Writing — and How It Is Achieved

**Course:** MCCP 6020 Research Writing  
**Date:** 22 February 2026  
**Purpose:** A reference document for PhD students on how to identify, construct, and communicate novelty in their Introduction and Literature Review sections.

---

## 1. Why Novelty Matters

Academic writing must do more than summarize existing knowledge — it must demonstrate that the proposed research *adds something new* to the field. In the CARS (Create a Research Space) model, novelty is the engine of Move 2 (Establishing a Niche) and Move 3 (Occupying the Niche). Without a clear novelty claim, a paper has no reason to exist.

But "novelty" does not mean inventing something from scratch. As the model papers in our course demonstrate, novelty takes many forms — from reframing a problem to combining existing ideas in new ways.

---

## 2. Types of Novelty (with Examples from Model Papers)

### Type 1: Novel Problem Formulation

**What it is:** Defining a new problem, or reframing an existing one so that new solutions become possible.

**Examples:**

- **COCO** (Sinha & Vaze, NeurIPS 2024 — [WYQ* folder](../../literature/WYQ*/COCO_Insights.md)): Generalizes standard Online Convex Optimization to adversarial constraints (COCO problem). The novelty is in the *formulation* — they didn't invent new math, they asked a new question:

  > "In this paper, we consider a generalization of the standard OCO framework."

  They then show that existing algorithms cannot handle this generalized version, creating space for their contribution.

- **COLDQ** (Wang et al., AAAI 2025 — [WYQ* folder](../../literature/WYQ*/COLDQ_Insights.md)): Frames the key question explicitly:

  > "Can a constrained OCO algorithm provide a dynamic regret bound and a constraint violation bound that smoothly approach to the best-known O(T^{1/2}) regret and O(1) violation, respectively, as the dynamics of the losses and constraints diminish? Our answer is yes."

  The novelty is in *asking the right question* — one that existing work had not addressed.

- **Benchmarking LLM Causal Reasoning** (Lee et al., 2025 — [YJY* folder](../../literature/YJY*/BenchmarkingLLMCausalReasoning_Insights.md)): Reframes the evaluation problem by insisting on scientifically validated causal relationships rather than synthetic data:

  > "Existing benchmarks... often rely on low-fidelity synthetic data, focus on narrow or biased domains, and reduce causality to simplistic cause-effect identification."

### Type 2: Novel Method or Framework

**What it is:** Introducing a new algorithm, architecture, or systematic approach.

**Examples:**

- **Kang et al. RecSys 2025** ([LK* folder](../../literature/LK*/KangPaper1_Insights.md)): Introduces SerenEva, a meta-evaluation framework:

  > "We propose SerenEva (serendipity evaluation framework), a novel meta-evaluation framework that measures the alignment between LLM evaluator ratings and human judgments."

- **Cai et al. SIGIR 2025** ([LK* folder](../../literature/LK*/KangPaper2_Insights.md)): Introduces AFL (Agentic Feedback Loop):

  > "To this end, we introduce the **A**gentic **F**eedback **L**oop (AFL) modeling. AFL simultaneously constructs both a recommendation agent and a user agent, using textual communication to simulate the feedback loop."

- **CHASE-SQL** (Pourreza et al., ICLR 2025 — [JXJ* folder](../../literature/JXJ*/CHASE-SQL_Insights.md)): Multi-path candidate generation + trained selection agent:

  > "We propose three distinct candidate generation approaches, each capable of producing high-quality responses."

- **FedSum** (Ma et al., AAAI 2025 — [ZPL* folder](../../literature/ZPL*/FedSumInsights.md)): Depth + breadth extensions for data-scarce federated learning:

  > "We propose FedSum which extends the standard FL framework from depth and breadth to further extract prime and diversified knowledge."

### Type 3: Novel Perspective or Theoretical Lens

**What it is:** Applying a new theoretical perspective to an existing problem, revealing aspects that previous approaches could not see.

**Examples:**

- **Kang Li's draft** (our student): Proposes applying cognitive science to serendipity modeling in recommender systems. This is a *perspective novelty* — the problem (serendipity evaluation) is known, but the lens (cognitive science) is new to this context.

- **Binst et al. UMAP 2025** ([arXiv:2505.15440](https://arxiv.org/abs/2505.15440)): Uses *grounded theory* (a qualitative research method) to study serendipity in recommender systems — a field dominated by quantitative approaches:

  > "We conceptualize experienced serendipity as 'a user experience in which a user unintentionally encounters content that feels fortuitous, refreshing, and enriching.'"

  The novelty is methodological — they bring qualitative rigor to a quantitative field.

- **Foundation-Expert** (Li et al., Meta — [WJY* folder](../../literature/WJY*/FoundationExpertInsights.md)): Applies the foundation model paradigm (from NLP) to recommender systems:

  > "We propose the Foundation-Expert paradigm, an alternative to methods like SFT or knowledge distillation."

### Type 4: Novel Combination

**What it is:** Combining existing ideas, methods, or domains in ways that produce new capabilities.

**Examples:**

- **CHASE-SQL**: Combines three independent generation strategies (divide-and-conquer, query plan CoT, online synthetic examples) with a trained pairwise selection agent. No single component is entirely new, but the combination achieves state-of-the-art.

- **FedSum**: Combines data partitioning (hard sample mining) with multi-knowledge learning (prototypes, contrastive loss) in a federated setting. Each technique exists independently, but their combination for data-scarce federated summarization is new.

- **Kang et al. RecSys 2025**: Combines LLM evaluation with auxiliary psychological data (curiosity scores):

  > "Notably, incorporating curiosity significantly improved performance, achieving a Pearson correlation coefficient of 17.83%."

  The novelty is in combining *user psychology data* with *LLM evaluation* — two ideas from different traditions.

### Type 5: Novel Evaluation or Benchmark

**What it is:** Creating new ways to measure, evaluate, or benchmark existing phenomena.

**Examples:**

- **Kang et al. RecSys 2025**: The meta-evaluation framework itself (evaluating how well evaluators evaluate serendipity) is a novel evaluation approach.

- **Benchmarking LLM Causal Reasoning**: Creates a benchmark from peer-reviewed economics papers with scientifically validated causal relationships — a higher standard than synthetic benchmarks.

- **Foundation-Expert**: Introduces the "Transfer Ratio" metric:

  > "We define the Transfer Ratio (TR) between a pair of FMs for a given expert."

### Type 6: Incremental Innovation

**What it is:** Targeted improvement over the state-of-the-art — tighter bounds, better efficiency, fewer assumptions.

**Examples:**

- **AStar-BMao** (Chang et al., IEEE — [JJG* folder](../../literature/JJG*/AStarBMaoInsights.md)): Proposes a tighter lower bound for graph edit distance, then trades some tightness for efficiency:

  > "We formally prove the correctness of lbBMa and that lbBMa is tighter than lbLSa... However, due to the high time complexity... we then slightly loose the lower bound lbBMa into lbBMao..."

  The novelty is *incremental but rigorous* — they improve a specific technical property (bound tightness) while maintaining practical efficiency.

- **COCO**: Breaks a long-standing barrier:

  > "Our result breaks the long-standing O(T^{3/4}) barrier for the CCV."

- **COLDQ**: Achieves bounds that smoothly approach optimal as dynamics diminish — "for the first time."

---

## 3. How Novelty Is Signaled in Academic Writing

Identifying novelty is not enough — you must *communicate* it clearly. Here are the rhetorical strategies used across the model papers:

### Strategy 1: Gap-to-Solution Narrative

Every model paper follows this pattern: *existing approaches have specific limitations* → *our work addresses these limitations*. The gap IS the novelty claim.

| Paper | Gap Statement | Solution |
|-------|--------------|----------|
| Kang et al. (RecSys) | "The gap between these indirect measurements and actual user perceptions introduces bias" | SerenEva meta-evaluation framework |
| Cai et al. (SIGIR) | "Existing research primarily focuses on optimizing either the recommendation agent or the user agent separately" | AFL: simultaneous optimization |
| COCO (NeurIPS) | "None of the constraint violation bound recovers the best-known O(1) violation" | Surrogate cost function + blackbox reduction |
| CHASE-SQL (ICLR) | "A single prompt design might not fully unleash the extensive Text-to-SQL knowledge of LLMs" | Multi-path generation + selection |
| FedSum (AAAI) | "How to derive a well-behaved summarizer in data scarcity FL?" | Depth + breadth extensions |
| AStar-BMao (IEEE) | "Memory consumption of AStar-LSa increases very fast" | Tighter + more efficient lower bound |

### Strategy 2: Explicit Contribution Enumeration

Most papers enumerate contributions as a numbered or bulleted list in the Introduction. This makes novelty claims unmissable:

- **Cai et al.**: Three numbered contributions
- **COCO**: Five enumerated contributions
- **COLDQ**: Four bullet-point contributions
- **CHASE-SQL**: Four contributions with specific quantitative claims

### Strategy 3: Naming the Contribution

Creating a memorable name or acronym signals that the contribution is substantial enough to deserve one:

| Paper | Name | Formation |
|-------|------|-----------|
| Kang et al. | **SerenEva** | Serendipity Evaluation |
| Cai et al. | **AFL** | Agentic Feedback Loop |
| CHASE-SQL | **CHASE-SQL** | Multi-path reasoning + selection |
| FedSum | **FedSum** | Federated Summarization |
| COLDQ | **COLDQ** | Constrained Online Learning with Doubly-bounded Queue |
| Foundation-Expert | **TAE** | Target-Aware Embeddings |

### Strategy 4: Quantitative Claims

Specific numbers make novelty claims concrete and verifiable:

- "average improvement of 11.52%" (Cai et al.)
- "approximately 100% in Pearson correlation compared to the best proxy metric" (Kang et al.)
- "73.01% execution accuracy... outperforms all published and undisclosed methods" (CHASE-SQL)
- "breaks the long-standing O(T^{3/4}) barrier" (COCO)
- "deployed at Meta serving tens of billions of user requests daily" (Foundation-Expert)

### Strategy 5: "First to" and Superlative Claims

These are strong novelty signals, used when justified:

- "For the first time, the two bounds smoothly approach to the best-known..." (COLDQ)
- "outperforms all of the published and undisclosed methods on this benchmark, by a large margin" (CHASE-SQL)
- "breaks the long-standing barrier" (COCO)

### Strategy 6: Contrastive Positioning

Explicitly contrasting your approach with existing ones highlights what is new:

- "Unlike... we..." / "In contrast to..."
- "Existing research primarily focuses on X, overlooking Y" (Cai et al.)
- "Our work is orthogonal to these previous work" (Foundation-Expert)
- "None of the above... approaches to..." (COLDQ)

### Strategy 7: Research Question Formulation

Framing novelty as a research question makes the contribution clear and testable:

- "Can LLMs effectively simulate human users for serendipity evaluation?" (Kang et al.)
- "Can a constrained OCO algorithm provide..." (COLDQ)
- "Can contemporary LLMs understand and reason about complex, scientifically validated causal relationships?" (Benchmarking LLM)
- "Then a natural question is: How to derive a well-behaved summarizer in data scarcity FL?" (FedSum)

---

## 4. Common Pitfalls in Communicating Novelty

### Pitfall 1: Claiming Novelty Without Evidence
Saying "this is novel" without showing *why* it's novel or *what gap* it fills. Every novelty claim must be backed by a demonstrated limitation in existing work.

### Pitfall 2: Novelty by Omission
Failing to review relevant work and then claiming novelty because "nobody has done this." This is a literature review failure, not a genuine contribution.

### Pitfall 3: Vague Novelty Claims
"We propose a new approach" — but what specifically is new about it? Vague claims signal weak understanding of the field. Compare:
- Weak: "We propose a new method for evaluating serendipity."
- Strong: "We propose a meta-evaluation framework that measures alignment between LLM evaluator ratings and human judgments using correlation and error metrics across two domains."

### Pitfall 4: Confusing Novelty with Complexity
Adding more components or making things more complex does not make work novel. Some of the most impactful novelty is *simplification* — see COCO's "blackbox reduction" or AStar-BMao's trading tightness for efficiency.

### Pitfall 5: Not Distinguishing Types of Novelty
A paper can be novel in its problem formulation, its method, its evaluation, or its perspective — but the author must be clear about *which type* of novelty they claim. Kang Li's draft, for instance, claims perspective novelty (cognitive science) but needs to articulate exactly what this perspective enables that existing approaches cannot.

---

## 5. A Framework for Students: Identifying Your Own Novelty

Ask yourself these questions:

1. **What gap does my work fill?** Write one sentence describing what existing work cannot do.
2. **What type of novelty am I claiming?** (Problem formulation? Method? Perspective? Combination? Evaluation? Incremental improvement?)
3. **Can I name my contribution?** If you can give it a name or acronym, you probably understand it well enough.
4. **What is the quantitative or qualitative evidence?** How will readers verify your novelty claim?
5. **What existing work comes closest?** Identify the 2-3 most similar papers and articulate exactly how your work differs.

---

*This document draws on analyses of model papers across the MCCP 6020 course. See individual analysis files in the `literature/` folder for detailed structural breakdowns.*
