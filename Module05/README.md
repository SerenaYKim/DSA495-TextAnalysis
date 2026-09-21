# Module 5: Evaluation and Error Analysis

This module compares RoBERTa sentiment classification and BART zero-shot
classification on English tweets. It connects model predictions to precision,
recall, F1, and confusion matrices, with a clear separation between development
and final evaluation.

## Contents

| File | Description |
| --- | --- |
| [`DSA495-M05-Evaluation-Error-Analysis.ipynb`](./DSA495-M05-Evaluation-Error-Analysis.ipynb) | In-class activity covering sentiment classification, confusion-matrix calculations, development-based label wording, and model comparison. |

## What You Will Do

- Use illustrative examples to identify true positives, false positives, and
  false negatives and calculate precision, recall, and F1.
- Load TweetEval sentiment data with negative, neutral, and positive labels.
- Inspect tokenization and evaluate a fixed RoBERTa sentiment classifier.
- Compare BART label descriptions on 60 development tweets and inspect changed
  predictions, with an optional wording revision.
- Select wording using development macro-F1, freeze the choice, and evaluate
  BART on 300 separate tweets.
- Compare both models on the same evaluation tweets using classification
  reports, confusion matrices, accuracy, macro-F1, weighted-F1, and inference time.

## Before You Begin

Google Colab with a T4 GPU runtime is recommended. Obtain these three CSV files
from the course materials; they are not included in this folder:

- `illustrative_metrics_12.csv`
- `tweeteval_sentiment_development_60.csv`
- `tweeteval_sentiment_evaluation_300.csv`

Upload them through Colab's Files sidebar and use `DATA_DIR = Path("/content")`.
For a local run, set `DATA_DIR` to the folder containing your copies. Internet
access is required to download the pretrained models. Run the notebook in order
and finish any wording changes on development data before BART's final evaluation.
Both models are already trained; this activity does not update their weights.
