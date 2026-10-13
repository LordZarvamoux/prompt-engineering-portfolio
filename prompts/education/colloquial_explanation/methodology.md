# Design Methodology: Paraphrasing Obscure Rhetoric | Making Jargon Coherent
## Design Goal
The purpose of this prompt is for the user to break down complex concepts that they struggle to understand in a way that they can process what it really means.
---
## Design Approach: Structure and Technique
Explain the two design choices behind your prompt and why they fit the task.
**Structure I used:** R-T-F (Role, Task, Format)
**Why this structure fits my task:**
- This structure fits this task because it provides a specific learning format by which the prompter will understand the complex concept better.
- Another reason this structure fits this task is because the role aspect gives the LLM context as to how to present itself to the prompter in order to increase chances of seamless learning.
**Technique I used:** Chain-of-thought
**Why this technique fits my task:**
Chain-of-thought was used because learning requires a step-by-step process to build understanding. 
---
## Part-by-Part Justification
Justify each part of your prompt: what it is, what goes in it, and why the prompt
needs it. If your prompt is technique-driven and short (for example zero-shot
chain-of-thought), justify the technique and the few parts you do have instead.
| Part | What I put here | Why the prompt needs it |
|------|-----------------|-------------------------|
| [ROLE] | “You are a professional teacher and speaker who specializes in teaching students complex concepts with coherent rhetoric, as if translating two different languages for one of the parties to understand what the other party is saying.” | The purpose of the role aspect was to give the LLM a perspective to teach from. Doing this could make the LLM understand the context of its desired performance and enhance it to produce the best possible results for the prompter. |
| [TASK] | “Take the following explanation of the complex concept and teach me how to properly understand it. Think step-by-step before giving a final answer: [COMPLEX CONCEPT]” | The purpose of the task is to give the LLM context as to what it will be teaching the prompter. It tells the AI model to teach the prompter the given subject in a step-by-step manner before giving the final answer, which could reduce confusion as opposed to if the LLM led with the answer before explaining it.|
| [FORMAT] | “If this concept is tied with any jargon that you know that an average person will not understand, always leave a footnote for the definitions of those terms. Instead of leading with a general overview of a specific part of the complex concept, lead with the scenario first and then use that logic to form a proper short summary after the fact.” | The reason for this format is to further ensure that the prompter gets the most efficient learning experience that they can. Leading with the full idea, or including jargonistic vocabulary words in the output with clarifying what they mean can deter a proper learning experience. |
---
## Testing and Iteration
Test your prompt against a naive baseline, a plain version of the same request with
no deliberate structure or technique, and refine it based on what you see.
**Baseline I compared against:**
```
“Explain [COMPLEX CONCEPT] in plain, simple terms.”
```
| Version | Result / score | What changed |
|---------|----------------|--------------|
| Naive baseline | 25/100 | The core request was clear, but there were no boundaries provided to the LLM. There was no structure, and the prompt only consisted of one sentence with no background information. The structure of the output was left up entirely to the AI model. |
| Structured Prompt | 100/100 | The instructional approach is very specific by providing structure with a step-by-step process and a specified output outcome from the LLM.|
**What testing showed:** Unlike the baseline prompt, the structured prompt provided a specific and structured task for what the LLM was to teach about the complex concept, as well as a format on how to provide this information to benefit the prompter.
**What I learned:** Prompt design is profoundly essential to the kind of output that an LLM will produce, and how effective that output will be to the prompter. A poorly written prompt can lead to many unnecessary follow-up prompts on clarification and correction.
---
## Strengths and Limitations
**Works well when:** The LLM is told how to execute a task and what format to represent the output’s information in.
**Struggles when:** The prompt has little to no structure for the LLM to build, leading to confusion and many unnecessary follow up prompts from the user.
**Would improve next:** I might use a different structure in order to have a more detailed and better designed output from the LLM.
