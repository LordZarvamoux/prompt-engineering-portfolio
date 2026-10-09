# Market Analysis | Demographics
## Instructions for Use (delete this section when you build your actual prompt)
Your prompt must include:
- A short description of what it does
- Your prompt, organized into clearly labeled parts
- At least one `[PLACEHOLDER]` in square brackets and CAPS
- Output requirements so the AI knows what a good answer looks like
**Two design choices to make and note:**
- **Structure:** organize your prompt into intentional, labeled parts. Use a
framework from the lesson (for example R-T-F or C-A-R-E), modify a framework, or
design your own set of parts. What matters is that the structure is deliberate and
every part earns its place.
- **Technique:** the prompting method you use. Zero-shot (no examples), few-shot
(one or more worked examples), chain-of-thought (ask the AI to reason step by
step), or zero-shot chain-of-thought (add an instruction like "Think step by step"
with no examples).
You justify both choices in `methodology.md`.
---
## Overview

**Purpose:** This prompt produces an output from the LLM that focuses on the most likely demographic of people (in terms of age, location, daily life, and more) is most likely to purchase an idea that the prompter has for a product.

**Structure:** R-T-F (Role, Task, Format)

**Technique:** Zero-shot

---
## The Prompt

Organize your prompt into labeled parts, in the order that makes sense for your
task. Each label is one part of your structure. Somewhere in here, state the core
task or objective clearly, since that is the part the AI most needs to get right.
If your technique is few-shot, include your example(s) here; if it is chain-of-
thought, include the instruction to reason step by step.

**Role:**
You are a business founder looking to sell a new product. You already know how to manufacture this product, but you also need to market this product and get the best possible monetary results.

**Task:**
Analyze the product concept and make predictions on the most likely demographics of people to purchase it: [PRODUCT CONCEPT]

**Format:**
List each demographic in a table with their explanations to the right of the demographic names.

---
## Context and Inputs
List the information the user has to supply, written as placeholders:
- **[PRODUCT CONCEPT]:** A description of the product idea that you want to analyze for demographics likely to purchase it. The product concept is the single most important part of the prompt that will actually give the LLM context as to what to analyze.
---
## Output Requirements

**Format:** [How the answer should be structured, for example length, headings,
bullets, or a table.]

**Constraints:** [Rules that keep the AI on scope and protect quality.]

**Tone and Style:** [The voice, reading level, and style you want.]

---
## Additional Instructions (optional)
Anything else the AI should keep in mind that does not fit one of the parts above.
Delete this section if you do not need it.
