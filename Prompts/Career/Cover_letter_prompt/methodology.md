# Design Methodology: [Prompt Name]
## Design Goal
[A sentence or two on what you were trying to achieve and who the prompt is for.]
---
## Design Approach: Structure and Technique
Explain the two design choices behind your prompt and why they fit the task.
**Structure I used:** I used a modified C-A-R-E frame work 
**Why this structure fits my task:**
- The user just needs to provide info for the Ai and let it write
- The AI is already given the specifics and doesn't need to guess on any of the details
**Technique I used:** Zero-Shot
**Why this technique fits my task:**
I used Zero-Shot because no example besides work experience is necessary and even then, the work experience is considered a placeholder for the details of the user
**Example of modifying a framework (delete if not relevant):**
I started from C-A-R-E and removes the E (Which meant provide examples), which means the AI still has the background of the user, the task of creating the Cover Letter, and knows what the user expects out of it.
**Constraints** The model cannot stray from writing about what the user has provided and must write professionally/appealing towards the employer
**Example** part to lock in the tone I wanted. My final structure was Role, Task,
Constraints, Example, Format. Each added part solved a specific problem the plain
framework left open.
---
## Part-by-Part Justification
Justify each part of your prompt: what it is, what goes in it, and why the prompt
needs it. If your prompt is technique-driven and short (for example zero-shot
chain-of-thought), justify the technique and the few parts you do have instead.
| Part | What I put here | Why the prompt needs it |
|------|-----------------|-------------------------|
| [Part 1] | [Your text] | [Reason] |
| [Part 2] | [Your text] | [Reason] |
| [Part 3] | [Your text] | [Reason] |
---
## Testing and Iteration
Test your prompt against a naive baseline, a plain version of the same request with
no deliberate structure or technique, and refine it based on what you see.
**Baseline I compared against:**
```
[Your plain, naive version of the same request]
```
| Version | Result / score | What changed |
|---------|----------------|--------------|
| Naive baseline | [result] | [notes] |
| Version 1 | [result] | [notes] |
| Final | [result] | [notes] |
**What testing showed:** [In your own words, how your designed prompt performed
compared to the baseline, and what you changed as a result.]
**What I learned:** [What this taught you about prompt design.]
---
## Strengths and Limitations
**Works well when:** [The conditions where this prompt performs best.]
**Struggles when:** [Where it breaks down, and why.]
**Would improve next:** [What you would refine with more time.]
