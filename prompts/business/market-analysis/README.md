# Market Analysis | Demographics
> *This prompt produces an output from the LLM that focuses on the most likely demographic of people (in terms of age, location, daily life, and more) is most likely to purchase a product that the prompter has an idea to make.*

## Overview

This prompt is meant to produce an analysis of the demographics likely to purchase the given product. This could solve a problem of filtering out bad markets for a product. People who could find this prompt useful may be people in the industry of marketing. 

**Best for:**

- Entrepreneurs who seek to start a business.

- People in the e-commerce industry who want assistance in their journey to make sales.

- Marketing strategists who seek to understand more about variables that affect the market.

**Structure:** R-T-F (Role, Task, Format)

**Technique:** Zero-shot

**Output:** The length of the output is expected to be however the LLM sees fit, as length has not been mentioned as a detail in the expected response. The format will consist of tables with the name of each type of demographic as the subject matter of each row with additional information in those rows to the right of the subjects. The LLM is expected to prioritize specific explanations as opposed to broad generalizations. 

---

## Quick Start

1. Open [`prompt.md`](./prompt.md) and copy the template.
2. Replace the placeholders:
- `[PRODUCT CONCEPT]`: A description of the product idea that you want to analyze for demographics likely to purchase it. The product concept is the single most important part of the prompt that will actually give the LLM context as to what to analyze.
3. Paste it into your AI model of choice and run it.
4. Review the output and adapt it to what you need.

---
## Examples

See the [`examples/`](./examples/) folder for filled-in demonstrations showing the
prompt and the resulting output.

---
## Customization Tips

- **Want more detail?** Specify things like location or age to contribute to the demographic analysis. 

- **Want it shorter?** Specify a specific word-count limit for the LLM, or tell it to keep its response short and concise. 

- **Different context?** Replace the role with something more adjacent to your position.

---
## Technical Details

- **Structure:** R-T-F (Role, Task, Format)

- **Technique:** Zero-shot

- **Best models:** ChatGPT, Gemini, Claude

- **Placeholders:** 1, [PRODUCT CONCEPT]

