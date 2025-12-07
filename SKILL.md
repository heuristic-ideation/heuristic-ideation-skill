---
name: heuristic-ideation
description: Framework for systematic research idea and hypothesis generation using 20 research heuristics across five categories. This skill should be used when users request help generating, developing, or refining research ideas, hypotheses, research questions, or novel research directions across any academic or scientific domain.
---

# Heuristic-Based Research Ideation

This skill provides a comprehensive framework for generating and developing research ideas using 20 proven heuristics organized into five interconnected categories.

## Purpose

Research ideation and hypothesis generation are creative yet systematic processes. This skill transforms Claude into a structured ideation partner by providing proven heuristics for:

- Generating novel research questions and testable hypotheses from observations, literature, and data
- Developing and refining initial concepts into rigorous, falsifiable hypotheses
- Breaking conventional thinking patterns to uncover new perspectives and predictions
- Systematically exploring problem spaces and formulating testable propositions across disciplines

## The Five Categories

The 20 heuristics are organized into five categories that represent different sources and stages of the research process:

### Primary Starting Points (Categories I-III)

1. **Observation-Based Heuristics** - The foundation of great research is often a keen observation of the world. Turn occurrences and reflections into research questions.
2. **Reinterpreting Past Research** - The existing body of literature is a vast resource for generating new ideas. Mine past work for new inspiration.
3. **Data-Driven Discovery** - Collect new data or reanalyze existing data to spark ideas.

### Development & Refinement (Categories IV-V)

4. **Direct Manipulation** - When you already have a proposition, break conventional thinking patterns.
5. **Structured Analytical Approaches** - Employ structured thinking tools to build upon your initial ideas.

While categories I-III often serve as initial inspiration sources, all categories are interconnected in practice. Data-driven approaches may generate anomalies that loop back to observation, literature reinterpretation can point to new data needs, and structured analysis may expose assumptions inviting direct manipulation.

## Research Ideas vs. Hypotheses

This skill supports both broad research ideation and specific hypothesis generation:

**Research Ideas** are broad directions that identify:
- Important phenomena to study
- Gaps in knowledge
- Novel theoretical frameworks
- Unexplored relationships

**Hypotheses** are specific, testable predictions that:
- Make falsifiable claims about relationships between variables
- Specify expected outcomes or patterns
- Include clear observational predictions
- Can be empirically tested

When users request hypotheses specifically, ensure outputs include:
1. Clear statement of the prediction
2. Specification of variables or conditions
3. Expected observable outcomes
4. Potential tests or measurements

## When to Use This Skill

Trigger this skill when users:

- Request help generating research ideas, hypotheses, or research questions
- Ask for testable hypotheses or predictions
- Ask for novel research directions in their field
- Want to develop or refine existing research concepts or hypotheses
- Need to explore a research problem systematically
- Ask for creative approaches to scientific questions
- Reference "research ideation," "hypothesis generation," "research questions," or similar terms
- Need to formulate falsifiable predictions from observations or theories

## How to Use This Skill

### Step 1: Understand the Context

Determine the user's:
- Research domain or field
- Current stage (initial brainstorming vs. refinement)
- Available resources (literature access, data, etc.)
- Specific constraints or interests

### Step 2: Select Relevant Heuristic Categories

Based on the user's needs, identify which category references to load:

- For **starting new ideas**: Begin with Observation-Based, Reinterpreting Past Research, or Data-Driven Discovery
- For **refining concepts**: Use Direct Manipulation or Structured Analytical Approaches
- For **comprehensive exploration**: Consider multiple categories

**Key Principle**: Select the most relevant heuristic(s) for the situation. There is no need to apply multiple heuristics or generate ideas with each one.

### Step 3: Load Category References

Load the reference file(s) containing the heuristic(s) you've selected:

- `references/observation_based.md` - H1-H3
- `references/reinterpreting_research.md` - H4-H7
- `references/data_driven.md` - H8-H12
- `references/direct_manipulation.md` - H13-H15
- `references/structured_analytical.md` - H16-H20

Be selective in what you load based on what's most relevant to the user's needs.

### Step 4: Apply the Heuristic

Apply the selected heuristic(s) thoughtfully to generate high-quality ideas:

1. **Explain the heuristic** briefly in the context of the user's domain
2. **Generate well-developed ideas or hypotheses** 
3. **For each idea, provide**:
   - Clear statement of the idea/hypothesis
   - Detailed rationale for why it's promising (novelty, feasibility, importance)
   - Testable predictions (if generating hypotheses)
   - Potential implications and next steps

Focus on developing ideas thoroughly rather than generating many ideas superficially.

### Step 5: Conclude and Offer Options

After presenting ideas, provide closure and ask for direction:

- Briefly synthesize what makes the ideas promising
- Suggest concrete next steps for development
- Ask the user what they'd like to do next:
  - Explore one of these ideas more deeply?
  - Try a different heuristic approach?
  - Refine a hypothesis?
  - Generate alternatives?

Wait for user direction rather than automatically continuing.

## Best Practices

- **Quality over quantity**: Focus on depth and thoughtful development rather than generating many ideas
- **Be selective**: Choose the most relevant heuristic(s) for the situation
- **No need to use every heuristic**: Applying one heuristic well produces better results than covering many superficially
- **Be concrete**: Always provide domain-specific examples, not just abstract descriptions
- **Formulate testable hypotheses**: When generating hypotheses, ensure they are specific, falsifiable, and include clear predictions
- **Distinguish ideas from hypotheses**: Research ideas are broad directions; hypotheses are specific, testable predictions
- **Develop fully**: Fully articulate rationale, examples, and implications for each idea
- **Encourage iteration**: Suggest revisiting or trying different heuristics based on user feedback
- **Adapt to domain**: Translate each heuristic into the language and conventions of the user's field
