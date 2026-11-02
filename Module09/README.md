# Module 9: Prompt Engineering and Context Design

Compare prompt instructions and source organization using Phi-4-mini to summarize public-education proposals from four Wake County commissioner candidates. Check whether each claim is relevant and attributed to the correct source.

## Contents

| File | Description |
| --- | --- |
| [`DSA495-M09-Prompt-Context-Engineering.ipynb`](./DSA495-M09-Prompt-Context-Engineering.ipynb) | Prompt-component and context-design comparisons, source checks, and optional passage-selection experiments. |

## What You Will Do

- **Task A:** Use a basic prompt with all four files and check a saved answer against the sources.
- **Task B:** Make persona, instruction, context, format, audience, tone, and data explicit in the prompt.
- **Task C:** Give the model one candidate's file per call and compare attribution and relevance.

Optional activities select relevant excerpts and test the effect of changing one passage-selection decision.

## Before You Begin

Use Google Colab with a **T4 GPU**. Obtain the four candidate TXT files from the course materials and place them in `MyDrive/M09_Context_Design/knowledgebase`. Update `KB_DIR` if your folder differs.

Internet access is required to install packages and download Phi-4-mini. No Hugging Face account or token is required. Run cells in order and complete **Tasks A–C** before the optional material.
