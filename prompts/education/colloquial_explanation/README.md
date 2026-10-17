# Paraphrasing Obscure Rhetoric | Making Jargon Coherent
> *The purpose of this prompt is to make an input about a complex concept that is difficult to understand and receive an output from the LLM that explains the concept in a personalized and coherent manner.*

## Overview

This prompt is meant to produce a colloquial, step-by-step explanation to a complex concept. This could solve the problem of a lack of understanding about such things. This prompt could be used by people like students in the education system who seek a more efficient way of learning to catalyze their success. 

**Best for:**

- College/high school students who need to understand a concept for their academic success.

- Workers who seek advice on how to complete their jobs efficiently.

- Self-taught learners who want to excel in their personal endeavors.

**Structure:** R-T-F (Role, Task, Format)

**Technique:** Chain-of-thought

**Output:** The LLM is expected to speak to the prompter from the perspective of a teacher who specializes in teaching complex topics in colloquial terms that people can understand. For the form, the LLM has been told to refrain from leading with a general summary of the topic and instead to include the summary at the end of the step-by-step process. 

---

## Quick Start

1. Open [`prompt.md`](./prompt.md) and copy the template.
2. Replace the placeholders:
- `[COMPLEX CONCEPT]`: This is where the prompter will insert a description of the complex concept that they want to understand. This will help provide the LLM with context as to what to strategically teach the prompter.
3. Paste it into your AI model of choice and run it.
4. Review the output and adapt it to what you need.

---
## Examples

See the [`examples/`](./examples/) folder for filled-in demonstrations showing the
prompt and the resulting output.

---
## Customization Tips

- **Want more detail?** Prioritize prompting requests for creative analogies. 

- **Want it shorter?** Set a maximum word limit.

- **Different context?** Change the role to fit whatever is adjacent to the position of the alternative audience/industry. 

---
## Technical Details

- **Structure:** R-T-F (Role, Task, Format) 

- **Technique:** Chain-of-thought 

- **Best models:** ChatGPT, Gemini 

- **Placeholders:** 1, [COMPLEX CONCEPT]
