# Design Methodology: How-To Guide
## Design Goal
The goal of this prompt is to create a guide the user can use as reference
---
## Design Approach: Structure and Technique
- **Structure I used:** E-R-A
- **Why this structure fits my task:** It's simple at to the point and the Ai knows its role and the task it's given
- **Technique I used:** Zero-Shot
- **Why this technique fits my task:**
The user can't provide examples if they do not know the example itself, so I chose Zero-Shot
- **Constraints:** The Ai must stay withing 500-1000 word for their response and cannot stray from the topic

---
## Part-by-Part Justification
| Part | What I put here | Why the prompt needs it |
|------|-----------------|-------------------------|
| Expectations | The expectation is for the user is to be able to understand how [PLACEHOLDER 1] work and how it interacts with the code | This establishes what the result should be be for the user |
| Role | The role of the AI is to act as an instructor that can accurately teach [PLACEHOLDER 1] in a manner that isn't overly difficult but not too simple for the use | tells the Ai how it should approach how they respond with the output |
| Action | The Ai's task is to create a step-by-step guide that is at least 500-1000 words long, is on topic, and keep examples short but detailed. | Gives the Ai the task of creating the guide |
---
## Testing and Iteration
**Baseline I compared against:**
```
Generate a step-by-step guide on how to use nested loops in my code
```
| Version | Result / score | What changed |
|---------|----------------|--------------|
| Naive baseline | 25 | Does not clarify enough what the expectations are |
| Final | 100/100 | Explicit on expectations and how it should be executed |
**What testing showed:** My version 1 prompt performed four times better than the baseline prompt
**What I learned:** I learned that I don't need to go into so much detail for the prompt to be sufficient
---
## Strengths and Limitations
- **Works well when:** creating step-by-step guides for processes
- **Struggles when:** the user asks for more detail than what is already provided
