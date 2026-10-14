# Design Methodology: Content Creation Aid | Cinematic Storytelling and Editing
## Design Goal

The purpose of this prompt is to receive personalized advice on how to portray your video idea using specific editing techniques to tell that story in a visually cinematic way for the purpose of content creation. 

---
## Design Approach: Structure and Technique

**Structure I used:** C-A-R-E (Context, Action, Rules, Examples)

**Why this structure fits my task:**
- The Rules section of this structure is very helpful in creating restraints on the LLM in order to get an output as close to exactly what the prompter wants as possible.
- The Examples section of this structure provides examples of what kind of rhetoric is acceptable, versus what kind of rhetoric is detestable.

**Technique I used:** Few-shot

**Why this technique fits my task:**
The few-shot example was used because it uses a sufficient amount of examples for the LLM to build its response upon.

---
## Part-by-Part Justification

| Part | What I put here | Why the prompt needs it |
|------|-----------------|-------------------------|
| [CONTEXT] | “You are a talented storyteller and a professional video editor that is seeking to help me bring my story to life by teaching me clever cinematic editing techniques for the purpose of content creation.” | Giving the LLM the perspective of someone who is very skilled in portraying complex information in simple ways could give it a better understanding of what it needs to do. |
| [ACTION] | “Take my summary of a story concept and research clever editing and storytelling techniques to teach me the necessary editing skills needed to make a cinematic video: [STORY SUMMARY]”  | Giving the LLM context for what the story is about will give it information on what specific editing techniques could fit with certain parts of the story. |
| [RULES] | Provide information about the different software needed to bring the vision to life. Keep your rhetoric coherent and refrain from technical jargon that I might not know. Should there be any technical jargon that you think is necessary to include, be sure to include, in parenthesis, what the terminology means. | The rules ensure that the LLM refrains from jargonized language that the prompter will not have an immediate definition to. It also makes sure that recommendations for editing software are included.|
| [EXAMPLES] | **Example of what is preferable:** "Even though the app's modern system successfully started passing data along, the main program ran out of memory and crashed. This happened because a background process got stuck processing a massive pile of incoming text data without clearing out the old temporary memory it was using." **Example of what is detestable:** "Although the synergistic cloud-native microservices architecture successfully bootstrapped the asynchronous event-driven pipeline, the downstream garbage-collected runtime experienced a catastrophic heap allocation bottleneck because the recursive JSON deserialization thread failed to properly dereference the mutable pointer." | The example gives the LLM a clear expectation for what its output should be, making the response more aligned with the prompter’s desires. |
---
## Testing and Iteration

Test your prompt against a naive baseline, a plain version of the same request with
no deliberate structure or technique, and refine it based on what you see.

**Baseline I compared against:**
```
Please tell me how to edit a video for a story like this: [STORY CONCEPT]
```
| Version | Result / score | What changed |
|---------|----------------|--------------|
| Naive baseline | 15/100 | The core idea is clear, but lacks any clarification of specific goals. There is absolutely no format or structure of any kind. Leaves the result of the output completely to the LLM. |
| Designed prompt | 86/100 | The goal is clear, but the format around a specific editing software could be improved. Sections are labeled, but the Rules section overlaps with constraints. It establishes a clear agenda. |

**What testing showed:** This testing showed the difference between a one-sentence prompt with no structure context and a well-designed and properly thought-out prompt that tells the LLM precisely how to format its output. As a result, the prompter would have a better understanding of what to do as it pertains to editing around their story.

**What I learned:** From this, one can infer that prompt design is crucial for a seamless learning experience.

---
## Strengths and Limitations

**Works well when:** The prompt is clear and precise, laying out a specific format for the LLM to follow. 

**Struggles when:** The baseline prompt does not have structure, lowering the chases of a desired output from the LLM to accelerate chances of useful, relevant information specific to the task. 

**Would improve next:** The prompt could be more specific when it talks about editing software. 
