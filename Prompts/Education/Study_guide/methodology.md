# Design Methodology: Study Guide
## Design Goal
This prompt is supposed to generate a study guide for students to be able to use for upcoming exams
---
## Design Approach: Structure and Technique
Explain the two design choices behind your prompt and why they fit the task.
**Structure I used:** C-A-R-E
**Why this structure fits my task:**
- It specifies what the user needs with examples and with the rules, the Ai isn't able to hallucinate or make up details nearly as often 
**Technique I used:**
- Few-Shot
**Why this technique fits my task:**
- I used Few-Shot because the AI needs some kind of context on how to go about with the notes, so example questions are perfect for the Ai to know how to approach format of the study guide
**Constraints**
- The Ai is not allowed to deviate from the topic, exceed formatting restrictions such as length, and must keep notes short and sweet
---
## Part-by-Part Justification
Justify each part of your prompt: what it is, what goes in it, and why the prompt
needs it. If your prompt is technique-driven and short (for example zero-shot
chain-of-thought), justify the technique and the few parts you do have instead.
| Part | What I put here | Why the prompt needs it |
|------|-----------------|-------------------------|
| Context and Action | The user tells the Ai what kind of study guide they are looking for | Gives the context to the AI |
| Rules | States the rules for the Ai and the DOs and DON'Ts | This is to keep the Ai from hallucinating information and over-explaining the topic |
| Example | Gives example problems for the Ai | So the Ai knows what to base the study guide off of |
---
## Testing and Iteration
**Baseline I compared against:**
```
Give me a study guide based on [PLACEHOLDER 1] for the upcoming test
```
| Version | Result / score | What changed |
|---------|----------------|--------------|
| Naive baseline | 15/100 | Clarifies a bit of context but not enough |
| Version 1 | 40 | Disorganized Framework |
| Final | [result] | [notes] |
**What testing showed:** [In your own words, how your designed prompt performed
compared to the baseline, and what you changed as a result.]
**What I learned:** [What this taught you about prompt design.]
---
## Strengths and Limitations
**Works well when:** [The conditions where this prompt performs best.]
**Struggles when:** [Where it breaks down, and why.]
**Would improve next:** [What you would refine with more time.]
