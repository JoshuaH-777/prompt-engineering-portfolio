# Study Guide Template
---
## Overview
- **Purpose:** This prompt is supposed to get an AI to create a study guide for the user to use for their work
- **Structure:** I'm using the C-A-R-E framework. The Context is that the user needs a study guide to use, with the Action being where the user tell the Ai to write the prompt for the specified subject or topic. The Rules are the constraints such as no walls of text or the limit on how big or small the guide must be. And finally, the Example is the user providing a sample question for the topic
- **Technique:** Few-Shot
---
## The Prompt
- **Context and Action:**
The goal is to create a study guide for [PLACEHOLDER 1], in which the students needs for their upcoming exam.
- **Rules:**
The goal of the student is to get above an 85% or B on their test, so information must be sufficient, but not too much where it takes too long to digest the information. There cannot be massive paragraphs and the guide must be around 1.5 to 2 pages long with 2 pages being the absolute maximum. The study guide must be able to be reviewed over in around 30 minutes, no longer, so keep the notes consistent. Make sure to write down key definitions and stay on topic. Do not stray away from what the user is asking for and do not write down irrelevant information that does not pertain to the desired subject. If the user asks for a guide for a massive final/cumulative exam, the guide's page limit is now 10-15 pages long instead. All of these requirements are subject to change from the user. These changes are [PLACEHOLDER 3]
- **Example:**
A few example problems for this subject are [PLACEHOLDER 2].
---
## Context and Inputs
List the information the user has to supply, written as placeholders:
- **[PLACEHOLDER_1]:** The subject the user is creating the study guide for
- **[PLACEHOLDER_2]:** The example problems for context so the AI can understand
- **[PLACEHOLDER_3]:** Any change to the rules the user may want to input so the AI can meet specifications
---
## Output Requirements
**Format:** The Guide should mostly be bullet points and roughly 1-2 pages max
**Constraints:** The Ai must stay on topic and cannot include info that isn't relevant to what the user is looking for
---
