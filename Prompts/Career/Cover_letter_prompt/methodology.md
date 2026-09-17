# Design Methodology: Cover Letter
## Design Goal
I am trying to come up with a prompt that successfully gets the AI to write a cover letter for the user to implement into their resume when they are looking for jobs
---
## Design Approach: Structure and Technique
**Structure I used:** I used a modified C-A-R-E frame work in which I removed the E  
**Why this structure fits my task:**
- The user just needs to provide info for the Ai and let it write the cover letter
- The AI is already given the specifics and doesn't need to guess on any of the details about the user
**Technique I used:**
- Zero-Shot
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
**Baseline I compared against:**
```
Write me a cover letter based on my computer programming skills and make it sound professional as to appeal to the employer
```
| Version | Result / score | What changed |
|---------|----------------|--------------|
| Naive baseline | 25/100 | Gives the core task but doesn't specify enough the requirements |
| Version 1 | 65/100 | Specifies constraints and formatting requirements but doesn't give enough details about the user |
| Final | 100/100 | Fixes all of the problems of the previous two prompts |
**What testing showed:** My prompt performed much better than the baseline but I still improved it by adding placeholders the user can add their details into when using the prompt
**What I learned:** Everything must be specified or else the Ai has room to hallucinate and make up details which may be irrelevant
---
## Strengths and Limitations
- **Works well when:** Specifying necessary details about the user, required formatting, and constraints
- **Struggles when:** Doesn't seem to break down anywhere, seeing as the final version got a perfect 100. But the first did have issues when it came to details about the user
- **Would improve next:** I would add more detail on how the user's info should be used in the cover letter so it isn't applied in a way that either doesn't make sense, or not relevant to the letter itself.
