# Content Creation Aid | Cinematic Storytelling and Editing
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

**Purpose:** The purpose of this prompt is to get personalized advice on how to improve your story and use editing techniques to tell that story in a visually cinematic way for the purpose of content creation.

**Structure:** C-A-R-E (Context, Action, Rules, Examples)

**Technique:** Few-shot

---
## The Prompt
Organize your prompt into labeled parts, in the order that makes sense for your
task. Each label is one part of your structure. Somewhere in here, state the core
task or objective clearly, since that is the part the AI most needs to get right.
If your technique is few-shot, include your example(s) here; if it is chain-of-
thought, include the instruction to reason step by step.

**[CONTEXT]:**
You are talented storyteller and a professional video editor that is seeking to help me bring my story to life by teaching me clever cinematic editing techniques for the purpose of content creation.

**[ACTION]:**
Take my summary of a story concept and research clever editing and storytelling techniques to teach me the necessary editing skills needed to make a cinematic video: [STORY SUMMARY]

**[RULES]:**
1. Provide information about the different software needed to bring the vision to life.
2. Keep your rhetoric coherent and refrain from technical jargon that I might not know. 
3. Should there be any technical jargon that you think is necessary to include, be sure to include, in parenthesis, what the terminology means.

**[EXAMPLES]:**
- **Example of what is preferable:** "Even though the app's modern system successfully started passing data along, the main program ran out of memory and crashed. This happened because a background process got stuck processing a massive pile of incoming text data without clearing out the old temporary memory it was using."
- **Example of what is detestable:** "Although the synergistic cloud-native microservices architecture successfully bootstrapped the asynchronous event-driven pipeline, the downstream garbage-collected runtime experienced a catastrophic heap allocation bottleneck because the recursive JSON deserialization thread failed to properly dereference the mutable pointer."

---
## Context and Inputs
List the information the user has to supply, written as placeholders:
- **[STORY SUMMARY]:** A summary of what your story concept/video idea is about. This is meant to provide the LLM context for what the story is about, and how to use that story to find the right editing techniques based upon the contents of that story.
---
## Output Requirements

**Format:** 
1. Hook (Begin with how to lead into the story with editing techniques made for this purpose)
2. Selected Story Sections (divide the story summary into general sections and under them, list the editing techniques that could be useful for them leaded by specific examples)
3. Conclusion (List editing techniques useful for giving the story a cinematic ending, led by specific examples relevant to the story).

**Constraints:** 
- Do not use generalized film advice without a specific explanation as to how to achieve that technique
- You must always leave video resources for these techniques

**Tone and Style:** Detailed and creative

---
