# Design Methodology: [Prompt Name]
## Design Goal
I am trying to come up with a prompt that successfully gets the AI to write a cover letter for the user to implement into their resume when they are looking for jobs
---
## Design Approach: Structure and Technique
**Structure I used:** I used a modified C-A-R-E frame work in which I removed the E  
**Why this structure fits my task:**
- The user just needs to provide info for the Ai and let it write the cover letter
- The AI is already given the specifics and doesn't need to guess on any of the details about the user
**Technique I used:** Zero-Shot
**Why this technique fits my task:**
- I used Zero-Shot because no example besides work experience is necessary and even then, the work experience is considered a placeholder for the details of the user
**Example of modifying a framework:**
- I started from C-A-R-E and removes the E (Which meant provide examples), which means the AI still has the background of the user, the task of creating the Cover Letter, and knows what the user expects out of it.
**Constraints**
- The model cannot stray from writing about what the user has provided and must write professionally/appealing towards the employer
---
## Part-by-Part Justification
| Part | What I put here | Why the prompt needs it |
|------|-----------------|-------------------------|
| The Context | The user tells the AI that they need it write them a cover letter for their resume | This establishes the core task to the Ai  |
| The Input | The user then tells the AI what they're skills are, what they excel in, and their past work experience | This gives the AI a baseline on what to write about and how it applies to the resume |
| The Formatting | The user then tells the Ai that the writing style of the cover letter must be formal and strictly professional | This keeps the AI in line with how the user wants their cover letter done as to make it more appealing to the employer |
---
## Testing and Iteration
Test your prompt against a naive baseline, a plain version of the same request with
no deliberate structure or technique, and refine it based on what you see.
**Baseline I compared against:**
```
Write me a cover letter based on my computer programming skills and make it sound professional as to appeal to the employer
```
| Version | Result / score | What changed |
|---------|----------------|--------------|
| Naive baseline | 25/100 | Gives the core task but doesn't specify enough the requirements |
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
