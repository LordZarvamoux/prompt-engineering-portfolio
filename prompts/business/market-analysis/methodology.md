# Design Methodology: Market Analysis | Demographics
## Design Goal

This prompt produces an output from the LLM that focuses on the most likely demographic of people (in terms of age, location, daily life, and more) is most likely to purchase an idea that the prompter has for a product. This prompt could be used by people who are interested in market analysis.

---
## Design Approach: Structure and Technique

Explain the two design choices behind your prompt and why they fit the task.

**Structure I used:** R-T-F (Role, Task, Format)

**Why this structure fits my task:**
- The RTF strategy provides a role for the LLM to understand the desired output and rhetoric to the benefit of the prompter.
- The RFT strategy provides a format for the LLM to emulate in order for the prompter to understand this specific topic on market analysis in a step-by-step process before revealing the conclusion.

**Technique I used:** Zero-shot

**Why this technique fits my task:** Zero-shot was used because no examples are necessarily needed to understand this topic of market analysis.

---
## Part-by-Part Justification
Justify each part of your prompt: what it is, what goes in it, and why the prompt
needs it. If your prompt is technique-driven and short (for example zero-shot
chain-of-thought), justify the technique and the few parts you do have instead.
| Part | What I put here | Why the prompt needs it |
|------|-----------------|-------------------------|
| [ROLE] | “You are an experienced market researcher looking to help a business sell a new product. You already know how to manufacture this product, but you also need to market this product and get the best possible monetary results.”  | The purpose for this role is to give the LLM a specific context to work in in order to give the prompter a desired learning outcome, given the strategic rhetoric of the output. |
| [TASK] | “Analyze the product concept and make predictions on the most likely demographics of people to purchase it: [PRODUCT CONCEPT]” | This gives context for the LLM as to what to analyze, which in this case, is the product concept. With this information, the LLM will be able to identify the most likely consumer base for that specific product concept. |
| [FORMAT] | “List each demographic in a table with their explanations to the right of the demographic names.”  | This defines the format for the LLM to emulate. If the prompter defines a specific format, this personalizes the output from the AI model to increase chances of higher-quality analysis and learning. |

---
## Testing and Iteration

Test your prompt against a naive baseline, a plain version of the same request with
no deliberate structure or technique, and refine it based on what you see.

**Baseline I compared against:**
```
Please explain what demographics are most likely to purchase this product: [PRODUCT CONCEPT]
```

| Version | Result / score | What changed |
|---------|----------------|--------------|
| Naive baseline | 10/100 | The prompt is completely unstructured, and has no context. |
| Designed prompt | 85/100 | The task is defined and actionable, using a well-developed structure (R-T-F). It establishes a satisfactory business scenario for market research. |

**What testing showed:** No clarification in the prompt as to how exactly the prompter wants to analyze the market could leave flaws in their analysis.

**What I learned:** When it comes to building an analysis with an LLM, there has to be structure to the prompt in order to understand the analysis to the prompter’s personal liking.

---
## Strengths and Limitations

**Works well when:** The prompt is structured, making the market analysis more seamless for the prompter to read and understand.

**Struggles when:** The prompt is profoundly vague, and the analysis structure is left completely to the decision of the LLM.

**Would improve next:** The format by which the analysis is provided could be improved and restructured more seamlessly via a different format or a different technique/structure.
