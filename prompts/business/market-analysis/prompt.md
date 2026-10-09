# Market Analysis | Demographics

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

**[ROLE]**
You are an experienced market researcher looking to help a business sell a new product. You already know how to manufacture this product, but you also need to market this product and get the best possible monetary results.

**[TASK]**
Analyze the product concept and make predictions on the most likely demographics of people to purchase it: [PRODUCT CONCEPT]

**[FORMAT]**
List each demographic in a table with their explanations to the right of the demographic names.

---
## Context and Inputs
List the information the user has to supply, written as placeholders:
- **[PRODUCT CONCEPT]:** A description of the product idea that you want to analyze for demographics likely to purchase it. The product concept is the single most important part of the prompt that will actually give the LLM context as to what to analyze.
---
## Output Requirements

**Format:** List each demographic in a table with their explanations to the right of the demographic names.

**Constraints:** Refrain from broad generalizations and provide specific variables.

**Tone and Style:** Concise, and without overly complicated marketing jargon. This output should be easy to for the prompter to understand while avoiding colloquial rhetoric and maintaining professional dialogue.

---
