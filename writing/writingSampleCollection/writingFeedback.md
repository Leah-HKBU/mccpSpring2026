# Writing Feedback — KANG Li (康莉)

KANG Li (康莉) Student ID: 25481533 Email: 25481533@life.hkbu.edu.hk Programme: PHD COMP | Group: week6 GitHub: https://github.com/Leah-HKBU/mccpSpring2026/tree/main/writing/writingSampleCollection

--- commentKang.md ---
Feedback on Kang Li's First Draft: Introduction and Literature Review
Student: Kang LiTopic: Cognitive Science-Grounded Serendipity Modeling in Recommender SystemsDate: 22 February 2026Reviewer: Simon Wang (with AI-assisted analysis)

Your draft: writing/writingSampleCollection/firstDraft.mdYour reflection: writing/writingSampleCollection/reflection.mdAssessment rubric: writing/assessment/writing_instructions_formatted.md

Model papers analysed for this feedback:

Model Paper 1 (your own RecSys 2025): Full paper HTML | Macro-level structural analysis | ACM link
Model Paper 2 (Cai et al. SIGIR 2025): Full paper HTML | Macro-level structural analysis | ACM link
Binst et al. (2025) — "What Is Serendipity?": arXiv full text | arXiv abstract


Overall Assessment
Your draft demonstrates solid technical knowledge of serendipity in recommender systems and a clear sense of your research direction. You already have the core ingredients for a strong paper — a genuine research gap (misalignment between algorithmic metrics and subjective user experience) and a promising solution (cognitive science perspective). However, the current draft reads more like a technical summary than a well-structured academic argument. The key areas for improvement are: (1) building the Introduction into a full three-move argument with citations, (2) deepening the Literature Review with critical analysis rather than description, and (3) strengthening the connection between cognitive science and your proposed approach throughout.

Estimated current level: Satisfactory (6–7 range) — The gap identification is sound and writing is generally clear, but the draft needs significant structural and content development to reach Excellent.


Part 1: Introduction Feedback
What Works Well
Your opening sentence effectively establishes the importance of serendipity-oriented recommender systems
The gap identification (discrepancy between algorithmic optimization and actual user experience) is genuine and well-targeted
The research direction (cognitive science perspective) is clearly stated
Issue 1: Missing Title
Your draft has no title. A strong title signals your specific contribution and helps readers immediately understand your focus.

Suggestion: Consider something like:

"Modeling Serendipity Perception in Recommender Systems: A Cognitive Science Approach"
"Beyond Objective Metrics: A Cognitive Science Framework for Serendipity in Recommender Systems"
Issue 2: No In-Text Citations or References
The entire draft contains zero citations. This is a critical gap — academic writing requires evidence-based claims. Every factual assertion needs support.

Your sentence: "Serendipity-oriented recommender systems play a pivotal role in enhancing user satisfaction and engagement..."

What your own RecSys 2025 paper does (see KangPaper1_Insights.md, Move 1 section):

"Serendipity plays a pivotal role in enhancing user satisfaction within recommender systems by mitigating the effects of the information cocoon and filter bubble issues from traditional recommendation methods."

This claim is supported by multiple citations in the full paper. Notice how even in the opening sentence, the published version connects serendipity to specific problems (information cocoon, filter bubble) — making the claim verifiable.

What Binst et al. (2025) does in their Introduction:

"Serendipity has been associated with numerous benefits in the context of recommender systems, e.g., increased user satisfaction (Pastukhov et al., 2022), stimulation of long-tail item consumption (Sá et al., 2022), support for users in achieving self-actualization (Graus et al., 2018; Sullivan et al., 2019; Knijnenburg et al., 2016), and mitigation of the overspecialization problem (Stitini et al., 2022)."

Notice how they attach a specific citation to each claimed benefit. This is the standard you should aim for.

Action: Add citations throughout. Key references you should consider:

Kotkov et al. (2016) — foundational survey on serendipity in RS
Kotkov et al. (2024) — overview of serendipity definitions and operationalizations
Ziarani & Ravanmehr (2021) — comprehensive survey of serendipity approaches
De Gemmis et al. (2015) — beyond-accuracy metrics
Binst et al. (2025) — conceptualizing experienced serendipity (fortuitous + refreshing + enriching)
Your own Kang et al. (2025) RecSys paper — LLM-based serendipity evaluation
Issue 3: Introduction Is a Single Paragraph — Needs Three CARS Moves
Your Introduction compresses everything into one paragraph (~130 words). The assignment requires three distinct moves, each deserving its own paragraph(s). The current structure jumps too quickly from territory to gap to solution.

Move 1 — Establishing Territory (currently underdeveloped):

Your opening assumes readers already understand serendipity in recommender systems. Many readers — even in CS — may not know why serendipity matters or how it differs from novelty/diversity. You need to:

Define what serendipity means in the context of recommender systems
Explain why it matters (user satisfaction, filter bubble mitigation, self-actualization)
Summarize the current state of research with citations

How Binst et al. (2025) does Move 1: They spend three paragraphs establishing territory — first explaining that content is increasingly recommended (not searched for), then introducing beyond-accuracy metrics, and finally defining serendipity with its associated benefits. Here is how they gradually narrow the focus:

"Much of the content users encounter online is not actively searched for but recommended. Popular platforms like YouTube, Spotify, and Instagram all present users with automatically suggested content."

"RecSys can also support users in exploring the item space, introducing them to new and unexpected content. In these cases, beyond-accuracy metrics become essential, serendipity in particular (De Gemmis et al., 2015; Ge et al., 2010; McNee et al., 2006)."

"Serendipity, in the context of RecSys, captures the idea of desirable exploration within the item space (De Gemmis et al., 2015)."

This gradual narrowing guides readers who may not be specialists.

How your own RecSys 2025 paper does Move 1 (see KangPaper1_Insights.md, "Move 1: Establishing Territory"):

The paper uses evaluative language ("pivotal role," "significant challenges," "inherently subjective") and establishes practical significance through filter bubbles and user satisfaction. This works because a RecSys conference audience already has context — but for this assignment's broader academic audience, you need more setup.

Suggestion for Move 1 (2–3 paragraphs, ~200 words):

Paragraph 1: Why recommender systems matter; the problem of filter bubbles and homogeneous recommendations
Paragraph 2: Serendipity as a solution — define the concept, cite its benefits, show growing research interest
Paragraph 3: Current approaches to modeling serendipity (objective metrics, LLM-based) — this bridges to Move 2

Move 2 — Establishing a Niche (partially present but underdeveloped):

You mention that approaches "frequently fail to align with users' subjective perceptions." This is your gap, but it needs more development:

What specifically fails to align? Give examples of where metrics disagree with users
Why does this misalignment happen? (Because serendipity is inherently a cognitive/emotional experience that cannot be captured by item-level features alone)
What have others tried? Acknowledge attempts to address this gap (user studies, qualitative approaches like Binst et al.'s grounded theory work)

How Binst et al. (2025) establishes their niche:

"Despite its potential advantages, the concept of serendipity remains conceptually ambiguous in the context of RecSys (Ziarani and Ravanmehr, 2021; Kotkov et al., 2024). This conceptual ambiguity led researchers to adopt diverse approaches to operationalize the concept, resulting in inconsistent metrics of serendipity, which complicate the synthesis of findings across studies."

"While several have tried to address this research gap... none have focused their attention on understanding users' subjective experiences of serendipity with RecSys."

This is exactly the "conceptualization-operationalization gap" that your work also addresses. Reference this.

How your RecSys paper does Move 2 (see KangPaper1_Insights.md, "Move 2: Establishing Niche"):

"The gold standard for user-centered evaluation involves carefully designed user studies that directly capture user feedback, which, however, are costly in practice. As a result, many researchers rely on predefined proxy metrics... Nonetheless, the gap between these indirect measurements and actual user perceptions introduces bias into serendipity research."

The gap is framed as a cost-accuracy tradeoff — specific and actionable. Your draft should similarly frame the gap in concrete terms rather than just saying approaches "fail to align."

Move 3 — Occupying the Niche (present but needs expansion):

Your final sentence states the research direction but is too brief. Move 3 should:

Clearly state your research question or purpose
Briefly outline your approach (cognitive science framework — which specific theories?)
Preview what you achieve or find (even preliminary results)
Indicate the structure of the paper

How Cai et al. (SIGIR 2025) does Move 3:

"To this end, we introduce the Agentic Feedback Loop (AFL) modeling. AFL simultaneously constructs both a recommendation agent and a user agent, using textual communication to simulate the feedback loop."

They introduce their framework acronym, state specific quantitative contributions ("average improvement of 11.52%"), and enumerate numbered contributions — giving readers a concrete preview. See the full analysis in KangPaper2_Insights.md, "Move 3: Occupying Niche" section.

How your RecSys paper does Move 3 (from KangPaper1_Insights.md):

"The emergence of large language models (LLMs) has revolutionized evaluation methodologies across human annotation tasks, showcasing remarkable potential in user simulation and automatic assessment. This breakthrough motivates our key research question: Can LLMs effectively simulate human users for serendipity evaluation?"

Notice the bold formatting for emphasis and the clear research question. Your draft should similarly state a crisp research question.
Issue 4: Cognitive Science Perspective Not Explained
You mention "a cognitive science perspective" without explaining what this means. Readers need to understand:

Which cognitive theories or frameworks inform your approach?
How does cognitive science explain serendipity perception differently from current RS approaches?
What specific cognitive processes are involved? (e.g., surprise detection, relevance evaluation, value assessment)

Relevant research to draw on:

Curiosity-driven models: A recent paper (arXiv:2504.06633, 2025) models user curiosity — epistemic curiosity (desire for knowledge) vs. perceptual curiosity (stimulated by sensory ambiguity) — as a driver of serendipity preference, connecting psychological constructs to computational models.

Binst et al.'s three-component framework (arXiv:2505.15440): They define experienced serendipity as requiring three components — fortuitous, refreshing, and enriching. These implicitly map to cognitive processes:

Fortuitous relates to expectation violation
Refreshing relates to novelty detection
Enriching relates to value appraisal

"We conceptualize experienced serendipity as 'a user experience in which a user unintentionally encounters content that feels fortuitous, refreshing, and enriching'. We find that all three components — fortuitous, refreshing and enriching — are necessary and together are sufficient to classify a user's experience as serendipitous."

The RecSys vs. User serendipity distinction: Kotkov et al. (2024) distinguishes "RecSys serendipity" (system-side metric) from "user serendipity" (actual human perception) — this is fundamentally a cognitive science question.


Part 2: Literature Review Feedback
What Works Well
Clear two-category organization (objective metrics vs. LLM-based)
Specific author names mentioned (Zhang et al., Li et al., Kotkov et al., Fu et al.)
The summary paragraph identifies genuine limitations
Writing is generally clear and grammatically sound
Issue 5: Limited Connection Between Introduction and Literature Review
The Introduction ends with "this study adopts a cognitive science perspective" but the LR never discusses cognitive science perspectives on serendipity. The LR only reviews computational approaches. This creates a disconnect.

Suggestion: Add a third category or thread in your LR that reviews cognitive/psychological perspectives on serendipity:

How serendipity has been studied in cognitive science and information science — Makri & Blandford (2012) proposed a process model of serendipity through grounded theory
The role of curiosity, surprise, and value in serendipitous experiences — see arXiv:2504.06633
Attempts to bridge cognitive theories with computational models
Issue 6: LR Move 1 (Thematic Overview) — Missing Context and Definitions
Your LR jumps straight into "quantifying a serendipity score" without first:

Defining serendipity for the reader (the concept is contested — Kotkov et al. (2016) identified at least 6 different definitions)
Explaining why quantification is the dominant paradigm
Setting up the scope of your review

How Binst et al. (2025) handles this: Their Related Work section begins with a subsection "Conceptualizing Serendipity" that traces the evolution of the concept:

"In 2012, Makri and Blandford described a process model of serendipity, where an individual makes a new connection due to a mix of unexpected circumstances triggering a moment of insight, which is subsequently exploited, leading to a valuable unanticipated outcome."

"Smets (2022) contributes to the conceptualization of serendipity by positing it is a value that can be designed for. She distinguishes between three levels of serendipity: Intended serendipity (why design for it?), Afforded serendipity (how to stimulate it?), and Experienced serendipity (what characterizes the experience?)."

This gives readers a conceptual map before diving into specific approaches. Your LR should similarly start by mapping the conceptual landscape.
Issue 7: LR Move 2 (Critical Analysis) — Descriptive Rather Than Critical
Your review of the first category (objective metrics) is largely descriptive: "Zhang et al. do X, Li et al. do Y, Kotkov et al. do Z." The rubric requires you to critique methodologies and findings, show connections between studies, and synthesize rather than list.

Your current text: "Zhang et al. measure unexpectedness via category and content differences between candidates and user history, while Li et al. calculate it as the weighted distance between a candidate item and the clusters of user interests."

What this should become (with critical analysis):

What assumption do both share? Both treat unexpectedness as a measurable distance in item feature space — but this assumes items can be objectively compared, ignoring that the same item may be expected by one user and completely surprising to another depending on their background knowledge and cognitive state.
What's the limitation of this assumption? These distance-based metrics cannot capture the subjective, context-dependent nature of surprise — what cognitive science calls "expectation violation" depends on the individual's mental model, not just their click history.
How do they relate to each other? Show progression, contradiction, or complementarity between studies.

A model for critical synthesis from your own RecSys 2025 paper (see KangPaper1_Insights.md, RQ2 section):

"Notably, incorporating curiosity significantly improved performance, achieving a Pearson correlation coefficient of 17.83%. This is intuitive, as curiosity influences user perceptions of serendipity: more curious users are more inclined to explore items with lower relevance but higher unexpectedness."

This excerpt from your own paper shows exactly the kind of cognitive insight your LR should incorporate — connecting user psychology (curiosity) to system behaviour (metric performance).
Issue 8: Second Category (LLM-Based) — Too Brief
The LLM-based category paragraph is only 3 sentences. Given that your own published work (Kang et al., RecSys 2025) is a major contribution to this category, you have deep knowledge to draw on. This section should discuss:

The promise of LLMs (semantic understanding, simulation of user perspectives)
Specific approaches (Fu et al.'s "unexpected but relevant" definition, your own SerenEva framework)
Limitations: LLMs as black boxes, the correlation ceiling with human judgments, domain-specific variations

From your own paper's findings (see KangPaper1_Insights.md, RQ1 section):

"In zero-shot settings, LLMs such as Qwen2.5-14B and GPT-4 surpass conventional metrics across both datasets by approximately 100% in Pearson correlation compared to the best proxy metric (SOG)."

This is powerful evidence that LLMs outperform traditional metrics — but the correlation with human judgment is still modest, leaving room for your cognitive science approach.

The conceptual question: Are LLMs truly modeling user cognition, or just pattern-matching on training data?
Issue 9: Missing Citations Throughout the LR
Like the Introduction, the LR mentions authors by name but lacks proper citation formatting. "Zhang et al." and "Li et al." need full citations with years and reference list entries. The current draft has no reference list at all.
Issue 10: LR Move 3 (Research Gaps) — Present But Needs Sharpening
Your "significant limitations persist" paragraph identifies gaps but could be more precise:

Your text: "Objective metric-based approaches rely on heuristic definitions that frequently fail to align with the complex, subjective nature of user perception."

Sharper version (drawing on Binst et al.'s terminology): Something like — "While objective metric-based approaches provide computationally tractable solutions, they fundamentally operationalize serendipity as an item property (e.g., unexpectedness score) rather than as a user experience. This conflation means that a system might recommend items with high 'serendipity scores' that users perceive as merely random or irrelevant. Binst et al. (2025) identify this as the 'conceptualization-operationalization gap.' The core issue is that serendipity arises from a cognitive process — the interplay between expectation violation, curiosity arousal, and value recognition — that cannot be reduced to item-level features."
Issue 11: LR Move 4 (Conclusion) — Needs Stronger Bridge to Your Study
Your concluding paragraph mentions "cognitive science-grounded approach" but doesn't explain what this entails. The LR conclusion should:

Summarize the key insight from your review (both approaches treat serendipity computationally rather than cognitively)
State how your study specifically addresses this (which cognitive models? what methodology?)
Create anticipation for the methodology section


Part 2B: Novelty Analysis — How Well Does Your Draft Communicate Novelty?
(See also: novelty.md — a course-wide reference on types of novelty and strategies for communicating them.)
Your Novelty Claim
Your draft's novelty is a perspective novelty — applying cognitive science to serendipity modeling in recommender systems. This is a legitimate and potentially powerful form of novelty (see novelty.md, Type 3). However, the current draft does not communicate this novelty effectively.
What the Draft Does Well
You identify a genuine gap: existing approaches "frequently fail to align with users' subjective perceptions"
You name a specific perspective (cognitive science) as your contribution
The gap-to-solution structure is present in embryonic form
What Needs Improvement
Problem 1: The novelty claim is asserted, not demonstrated.

You state that you will adopt "a cognitive science perspective" but never explain what cognitive science reveals about serendipity that computational approaches miss. Compare how other papers demonstrate their novelty:

Your RecSys 2025 paper (analysis) demonstrates novelty through a concrete research question: "Can LLMs effectively simulate human users for serendipity evaluation?" — and names the framework (SerenEva). Your draft should similarly name your cognitive science framework and state what it enables.

Cai et al. (analysis) demonstrates novelty by identifying exactly what existing work overlooks: "overlooking the critical role of the feedback loop between the user and the recommender." Your draft says existing approaches "fail to align" but doesn't explain why they fail — the cognitive mechanism explanation is missing.

Binst et al. (arXiv:2505.15440) demonstrates novelty by using a different method (grounded theory) to study a familiar topic (serendipity), producing a new conceptualization (fortuitous + refreshing + enriching). Your draft should similarly state what new understanding cognitive science produces.

Problem 2: No contribution enumeration.

Every strong model paper enumerates its contributions. Your draft has none. You should add 2-3 specific contribution statements. For example:

We propose a cognitive framework that models serendipity perception as a three-stage process: expectation violation → curiosity arousal → value recognition
We demonstrate that incorporating cognitive features (e.g., curiosity) improves alignment with human serendipity judgments by X%
We provide a systematic comparison between cognitive-grounded and metric-based serendipity evaluation

Problem 3: No name for the contribution.

Successful papers name their contributions: SerenEva, AFL, CHASE-SQL, FedSum, COLDQ. Consider naming your framework — this forces you to define what it is precisely enough to deserve a name.

Problem 4: No quantitative or qualitative evidence preview.

Other papers preview their results in the Introduction:

"average improvement of 11.52%" (Cai et al.)
"Pearson correlation coefficient of over 20%" (Kang et al.)
"73.01% execution accuracy" (CHASE-SQL)

Even if your results are preliminary, previewing them signals confidence and gives readers a reason to continue reading.
How Other Model Papers Signal Novelty (Strategies You Should Adopt)
Recommended Revision for Novelty
In your Introduction Move 3, after stating the research direction, add something like:

"Specifically, we draw on [cognitive theory X] to model serendipity perception as a multi-stage cognitive process involving [stage 1], [stage 2], and [stage 3]. We implement this in [framework name], which [does what specifically]. Our results show that [preview of key finding]."

This single paragraph would transform your novelty claim from asserted to demonstrated.


Part 3: Addressing Your Self-Identified Challenges
Based on your reflection, here are targeted suggestions for the challenges you identified:
Challenge: "Logical flow and coherence"
Strategy: Use the "known → new" principle. Each sentence should begin with information already established and end with new information. Each paragraph should begin with a topic sentence that connects to the previous paragraph.

Example: Your LR currently jumps from defining objective metrics (paragraph 1) to LLM methods (paragraph 2) without a transition. Add a bridging sentence: "While these metric-based approaches provide systematic frameworks for quantifying serendipity, they require pre-defined formulations that may not capture the full complexity of the concept. An alternative paradigm has emerged with the rise of large language models..."
Challenge: "Compelling research narrative"
Strategy: Think of your Intro+LR as telling a story with a central tension: "Everyone agrees serendipity matters, but nobody can measure it properly because they're treating a cognitive experience as an engineering metric." Every paragraph should advance this narrative.
Challenge: "Balancing precision with brevity"
Strategy: For each study you cite, ask: "Does mentioning this specific detail advance my argument?" If it only adds technical detail without supporting your point, cut it. For example, the specific formula details (category differences, weighted distances) are less important than the underlying assumption they share (treating serendipity as item-level distance).


Part 4: Concrete Next Steps (Priority Order)
Add a title that signals your cognitive science contribution
Expand Move 1 of the Introduction: define serendipity, establish its importance with citations, introduce the evaluation challenge
Develop Move 2: articulate the conceptualization-operationalization gap with evidence
Strengthen Move 3: state your research question, preview your cognitive science framework, announce your contribution
Restructure the LR with three threads: (a) objective metric approaches, (b) LLM-based approaches, (c) cognitive/psychological perspectives on serendipity
Transform descriptions into critical analysis: for each approach, discuss not just what they do but what assumptions they make and why those assumptions are problematic
Add all citations and build a reference list — aim for 15–25 references for this length
Write connecting transitions between all major sections
Ensure the cognitive science thread runs throughout — this is your unique contribution and should be visible in every section


Part 5: Key Resources to Incorporate


Part 6: Rubric-Based Assessment Summary
(Rubric details: writing_instructions_formatted.md)


Your writing quality is actually strong — the language is clear, technically precise, and grammatically sound. The main improvements needed are structural (expanding the Introduction, deepening the LR) and scholarly (adding citations, building critical analysis). These are very achievable with revision.



End of Feedback — Kang Li

--- firstDraft.md ---
My First Draft
Source Information
Date written: [2026-02-14]

Context: [This is a draft for the course assignment.]

Status: [Partial draft - includes Introduction and Literature Review sections.]


Introduction
Serendipity-oriented recommender systems play a pivotal role in enhancing user satisfaction and engagement by mitigating the information cocoon and filter bubble issues prevalent in traditional systems. Despite growing recognition of its importance, explicitly modeling serendipity remains significantly challenging due to its inherently subjective and ambiguous nature. Existing algorithms often rely on objective metrics that linearly combine relevance, novelty, and unexpectedness, or directly employ Large Language Models (LLMs) to predict user serendipity. However, these approaches frequently fail to align with users' subjective perceptions, creating a discrepancy between algorithmic optimization and actual user experience. To address this gap, this study adopts a cognitive science perspective. We aim to simulate the serendipity perception process to develop a model that more accurately reflects subjective user experiences.

Simon comments 

no in-text citation 

no references 

no title 

I am not sure about the coherence of the intro paragraph - seems a bit short 

we need to find some model papers and review the introduction section 

it is assumed that readers already know enough about serendipity - but this may not be the case 

there is some info about the limitations of the current approach - these approaches ... fail to ... yet, there should be a bit more info about how the present study would address this gap; how a cognitive science perspective could help 

near the end of the Intro there should be announcing the present study with a summary of what has been done and what is found or achieved 
Literature Review
Current research on serendipity in recommender systems primarily focuses on quantifying a serendipity score for candidate items to guide recommendations. The objective is to identify and recommend high-scoring items that are both unexpected and valuable to the user. Existing methodologies can be broadly categorized into two paradigms: objective metric-based approaches and Large Language Model (LLM)-based prediction methods.

The first category defines serendipity through objective metrics, typically constructed as a linear combination of factors such as relevance, novelty, unexpectedness, diversity, and unpopularity. For instance, Zhang et al. and Li et al. formulate the serendipity score by combining relevance (e.g., click-through rate) and unexpectedness. Specifically, Zhang et al. measure unexpectedness via category and content differences between candidates and user history, while Li et al. calculate it as the weighted distance between a candidate item and the clusters of user interests. Kotkov et al. extend this by integrating relevance (predicted ratings), diversity (dissimilarity within the candidate set and user history), and unpopularity. Similarly, Jiang et al. approach the problem by balancing long-term preferences against short-term demands to capture serendipitous moments.

The second category leverages the semantic capabilities of LLMs to directly predict serendipity scores. Fu et al. define serendipity as "unexpected but relevant," utilizing LLMs to output a probability of "Yes" for a serendipity query, which serves as the score. Kang et al. adopt a "pleasant surprise" definition, prompting LLMs to simulate the user's serendipity rating of a candidate item.

Despite these advancements, significant limitations persist. Objective metric-based approaches rely on heuristic definitions that frequently fail to align with the complex, subjective nature of user perception. While LLM-based methods offer a more semantic approach, they often treat serendipity prediction as a black-box classification task without explicitly modeling the underlying cognitive mechanisms that drive user perception.

In summary, while existing methods have made strides in estimating serendipity through heuristic combinations and semantic predictions, a critical gap remains in aligning computational models with human cognitive processes. This underscores the necessity for a cognitive science-grounded approach to model the user's perception of serendipity more accurately, setting the stage for the methodology proposed in this study.

Simon comments

there seems to be limited connection between Intro and LR

when discussing the first category, we find little info about the nature and limitatons of the appraoches; just a few summaries of what has been done

the paragraph on the second category is also short 

the third paragraph touches upon the limitations of both types of approaches; but I don't find the discussion adequate 

human cognitive processes is a key concept that is central of the present study; its relationship with the existing studies should be explored and discussed in greater depth 

Notes
[Any additional notes about your draft, challenges you faced, questions you have, etc.]

--- reflection.md ---
My Reflection on Writing
Writing Challenges and Difficulties
What aspects of academic writing do you find most challenging? Ensuring logical flow and coherence between paragraphs and sentences.

What specific difficulties do you face when writing Introduction/Literature Review I struggle with crafting a clear and compelling narrative for the research motivation, specifically in making the storytelling aspect of the introduction more engaging and logical.

What do you struggle with most? I find it challenging to express complex critical analyses concisely. Detailed critique often seems to require extensive explanation, but using too many words can make the writing verbose and repetitive. Balancing precision with brevity is my biggest struggle.


My Writing Process
How do you approach writing Introduction and Literature Review? I typically start with an outline, write linearly, and go through multiple rounds of revision.

What steps do you take?

Draft an initial outline.
Refine and structure the outline.
Gather relevant materials and references based on the outline.
Flesh out the outline with detailed content.
Refine and polish the writing.

Do you have a particular method or strategy? I apply the "3 Moves" strategy for the Introduction and the "4 Moves" framework for the Literature Review learned in class. This approach significantly improves the structure and logical coherence of my writing.


How I Use AI for Help
Do you use AI tools (ChatGPT, Claude, etc.) to help with writing? Yes, I primarily use ChatGPT to polish my writing.

How do you use them? I use AI to assist with brainstorming, but I always write the first draft myself. Afterward, I use it for checking grammar and improving sentence.

What prompts do you typically use? "Please polish my writing in an academic style, making it clearer and more concise."

What do you find helpful or not helpful about AI assistance? I find AI most helpful for refining my writing and correcting grammatical errors after I have completed the initial draft. However, it cannot effectively help me structure my writing logically from the start, nor can it reliably write the literature review, as it often hallucinates and may cite non-existent references.


My Goals
What do you hope to improve in my writing? I hope to improve my writing in two key aspects:

Enhancing logical clarity and sentence conciseness.
Strengthening the overall structural coherence.

What specific skills do you want to develop?

Efficiently synthesizing literature and identifying weaknesses in existing studies.
Writing with greater precision and brevity.


Additional Notes
[Any other thoughts about your writing, concerns, questions, etc.]



