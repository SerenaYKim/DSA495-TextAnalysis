# Module 4: Zero-Shot and Few-Shot Classification

This module compares zero-shot and few-shot prompting for classifying banking
customer messages with a generative language model.

## Contents

| File | Description |
| --- | --- |
| [`DSA495_M04_Zero_Shot_Few_Shot_Classification.ipynb`](./DSA495_M04_Zero_Shot_Few_Shot_Classification.ipynb) | In-class lab covering prompt design, zero-shot classification, few-shot examples, evaluation metrics, confusion matrices, and error analysis. |

## What You Will Do

- Load a balanced subset of BANKING77 customer messages.
- Build a zero-shot prompt for four banking request categories.
- Add one, two, and four examples per class to create few-shot prompts.
- Compare model predictions using accuracy, macro-F1, precision, recall, and
  confusion matrices.
- Inspect changed predictions and misclassified messages across settings.
- Save prediction results for later review.

## Before You Begin

Google Colab with a GPU runtime is recommended. Mount Google Drive or upload the
three `banking77_m04_*.csv` files, then confirm that `DATA_DIR` points to the
folder containing the course data. Internet access is required to download the
Hugging Face model the first time the notebook runs.
