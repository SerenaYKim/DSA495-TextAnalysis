# Module 10: Evaluating LLM Answers

Use Qwen3-8B as a judge for the Module 9 Phi-generated answers about public education in Wake County. Evaluate faithfulness, relevance, and completeness, then inspect the judge's explanations against the evidence.

## Contents

| File | Description |
| --- | --- |
| [`DSA495-M10-LLM-Evaluation.ipynb`](./DSA495-M10-LLM-Evaluation.ipynb) | Structured LLM judgments, reference-checklist coverage, source audits, and A/B/C comparison charts. |

## What You Will Do

- **Without a reference answer:** Judge faithfulness to each candidate's source and relevance to the education question.
- **With a reference checklist:** Measure completeness as the fraction of expected reference points covered.
- **Inspect and compare:** Check the explanations, compare A/B/C results with bar charts, and examine evaluation time.

A valid JSON response does not establish that the judgment is correct. Keep the three criteria separate and use source evidence when reviewing Qwen's ratings.

## Before You Begin

Use Google Colab with a **T4 GPU**. Mount Google Drive and update `data_root` to the course Data folder in your Drive. Obtain these six input files from the course materials:

- **`M10_LLMEvals`:** `m10_answers.csv` and `m10_reference_points.csv`.
- **`M09_ContextEngineering`:** `christine_kushner.txt`, `gary_hartong.txt`, `kyle_stogoski.txt`, and `mona_singh.txt`.

Internet access is required to install packages and download Qwen3-8B. Run notebook cells in order; both evaluation stages reuse the same loaded model.

Results and figures are saved once to **`/content/m10_results`**, Colab's temporary storage. Download the files you want to keep before the runtime ends; the notebook does not write results to the input folders or shared Drive.
