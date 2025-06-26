# 🧠 Experiment 01: Informed vs. Control

## Objective

To investigate how large language models (LLMs) respond differently when they are **informed** they are part of a research experiment versus when they are not.

## Research Question

Does telling an LLM that it is being studied affect the **tone**, **content**, **ethics**, or **creativity** of its output?

## Design

- Compare outputs from GPT-4, Claude, and Gemini
- Two conditions:
  - **Informed**: Prompt includes an “informed consent”-style disclosure
  - **Control**: Prompt gives the same task but without context
- Responses are logged and compared side-by-side

## Prompts

Stored in the `/prompts/` directory. This includes both the informed and control versions used across agents.

## Results

Outputs from each model are saved in `/results/experiment_01_informed_vs_control/` and manually reviewed for patterns or changes in behavior.

## Notes

This is a foundational experiment to explore whether and how LLMs exhibit meta-awareness or shift responses when given transparency.
