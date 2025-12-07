# Observation-Based Heuristics (H1-H3)

The foundation of great research is often a keen observation of the world. These heuristics focus on turning occurrences and reflections into research questions.

**Usage Note**: Be selective—choose the most relevant heuristic and develop ideas thoroughly. Quality and depth are more important than using multiple heuristics or generating many ideas.

## H1: Investigate Deviations from Expectations

**Core Principle:** Notice outliers, anomalies, or surprising results and ask why they occur.

**Application:** When observations contradict existing theories, common wisdom, or expected patterns, these discrepancies often signal hidden mechanisms or flawed assumptions worthy of investigation.

**Key Questions:**
- What result surprised you or contradicted expectations?
- Why might this anomaly exist?
- What assumptions might be wrong?
- Could this outlier represent a new phenomenon?

**Examples:**
- **Medicine:** Noticing that some patients don't respond to standard treatments, leading to discovery of genetic variations in drug metabolism
  - *Hypothesis*: "Patients with CYP2D6 poor metabolizer genotype will show reduced efficacy to standard codeine doses compared to normal metabolizers"
- **Computer Science:** Observing unexpected performance bottlenecks in systems, revealing cache coherence issues
  - *Hypothesis*: "Systems with high cache miss rates will show performance degradation proportional to memory access latency"
- **Psychology:** Finding individuals who remain resilient despite adverse conditions, leading to research on protective factors
  - *Hypothesis*: "Individuals with strong social support networks will demonstrate lower stress biomarkers following traumatic events compared to those with weak social support"
- **Machine Learning:** Identifying cases where current hypotheses fail to explain, then iteratively refining hypotheses based on these failures (exemplified by HypoGeniC and Iterative Hypothesis Refinement approaches)
  - *Hypothesis*: "Model predictions will fail systematically for data points with feature X > threshold, indicating a missing interaction term"

**Implementation Strategy:**
1. Actively collect cases that violate current understanding
2. Analyze what makes these cases different
3. Formulate hypotheses that explain both normal and anomalous cases
4. Test whether the new explanation has broader applicability

**Observation Sources:**
- Empirical data analysis
- Prior beliefs or expectations
- Inconsistencies in existing literature
- Real-world phenomena that contradict theory

---

## H2: Question the Norm

**Core Principle:** Explore why a widely accepted pattern exists.

**Application:** Take phenomena or practices that everyone accepts as "normal" and scrutinize their underlying assumptions. This can reveal unexamined principles, implicit biases, or alternative explanations.

**Key Questions:**
- Why is this pattern considered normal or standard?
- What historical or contextual factors created this norm?
- Are there hidden assumptions embedded in this convention?
- What would happen if we challenged this established view?
- Could this pattern be culturally or historically contingent rather than universal?

**Examples:**
- **Organizational Studies:** Questioning why 40-hour work weeks are standard, leading to research on productivity and work-life balance
- **Economics:** Challenging the assumption that humans are purely rational actors, spawning behavioral economics
- **Education:** Questioning age-based grade levels, exploring competency-based advancement
- **Medical Research:** Challenging why most drug trials historically excluded women, revealing sex-based differences in drug efficacy

**Implementation Strategy:**
1. Identify widely accepted patterns in your field
2. Ask "why" repeatedly to uncover foundational assumptions
3. Search for counter-examples or alternative practices
4. Investigate whether the norm serves its intended purpose
5. Consider what alternatives might work equally well or better

**Warning:** Ensure questioning is substantive, not contrarian for its own sake. Focus on norms where examination could yield genuine insight.

---

## H3: Juxtapose Opposite Problems

**Core Principle:** Deepen your understanding of a problem by studying its inverse, and examine how each of these contrary problems suggests solutions to the other.

**Application:** By examining both a problem and its opposite simultaneously, you can identify shared underlying structures, complementary mechanisms, or symmetric principles that apply to both.

**Key Questions:**
- What is the inverse or opposite of this problem?
- What mechanisms are common to both the problem and its opposite?
- Can solving one help solve the other?
- What principles emerge from comparing both extremes?
- Are there middle-ground cases that challenge both extremes?

**Examples:**
- **Neuroscience:** Studying both memory formation and forgetting to understand memory consolidation mechanisms
- **Climate Science:** Examining both global warming and ice age triggers to understand climate regulation systems
- **Social Psychology:** Investigating both cooperation and conflict to understand social dynamics
- **Machine Learning:** Studying both overfitting and underfitting to understand model capacity and generalization
- **Economics:** Analyzing both inflation and deflation to understand monetary policy effectiveness

**Implementation Strategy:**
1. Clearly define the primary problem
2. Articulate what the opposite problem would be
3. Identify mechanisms or factors present in both
4. Look for asymmetries that distinguish the two
5. Develop theories that explain both phenomena
6. Test whether insights from one apply to the other

**Relationship to Other Heuristics:**
- Often combines with H1 (deviations) when one direction is normal and the other anomalous
- Can lead to H13 (challenge assumptions) by revealing that assumed unidirectional relationships are actually bidirectional

---

## Using These Heuristics Together

These three observation-based heuristics work synergistically:

1. **H1** helps identify what's surprising or anomalous
2. **H2** helps question why the "normal" is considered normal
3. **H3** helps understand both by studying them together

**Workflow Example:**
1. Notice an anomaly (H1)
2. Question whether what you consider "normal" is actually universal (H2)
3. Study both the anomaly and the norm together to find underlying patterns (H3)

This category establishes the foundation for research by transforming observations into structured questions worthy of investigation.
