# UDL Planning Partner

A reusable, UDL-informed assistant configuration for helping educators separate learning goals from delivery methods, identify design barriers and plan accessible options with consistent evidence of learning.

## Use

1. Copy `prompts/assistant-instructions.txt` into the instructions of an AI project or assistant that supports custom instructions.
2. Describe the audience in aggregate, learning goal, current activity, constraints and available resources. Do not include student names, diagnoses or other personal information.
3. Review the proposed barrier hypotheses before asking for options. The instructions require educator validation before recommendations.
4. Choose a manageable set of options and check that all formats produce equivalent evidence of learning.

`examples/` contains original Python tracing and unit-price learner cards. They are generic activity templates, not real learner work or assessment answers.

## Design

- Engagement, representation and action/expression are considered together.
- The learning goal is distinguished from the current method.
- Success criteria preserve intellectual challenge across response formats.
- Educator review, an evidence-collection plan and remaining accessibility checks stay explicit.
- CLEAR (Connected, Legitimate evidence, Equivalent challenge, Accessible, Realistic) is a mission-specific planning checklist, not an official CAST acronym.

For primary UDL guidance, consult [CAST's UDL Guidelines](https://udlguidelines.cast.org/). This independent assistant is not affiliated with CAST, does not diagnose learners and does not certify accessibility. Review outputs in the actual classroom context.

## Repository scope

This is a prompt/template project, not a hosted application or account integration. It contains the reusable configuration and fictional teaching materials only. No private ChatGPT conversations, learner records or account exports are included. No build step or API key is required to read the materials; using an AI service depends on that service's access and terms.
