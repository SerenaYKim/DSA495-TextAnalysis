# Module 3: Text Classification with Encoder Models

This module introduces encoder-based text classification through sentiment and
news-topic examples. It emphasizes model probabilities, evaluation metrics,
error analysis, and fair comparison of pretrained classifiers.

## Contents

| File | Description |
| --- | --- |
| [`DSA495_M03_Text_Classification_Encoder_Models.ipynb`](./DSA495_M03_Text_Classification_Encoder_Models.ipynb) | In-class lab and take-home task covering solar-tweet sentiment, movie-review sentiment, and comparison of two news classifiers. |

## What You Will Do

- Classify solar-energy tweets as positive, neutral, or negative with a
  domain-specific RoBERTa model.
- Classify Rotten Tomatoes reviews with a DistilBERT sentiment model.
- Organize model outputs as predicted labels, probabilities, and confidence
  scores.
- Evaluate predictions using precision, recall, F1, confusion matrices, and
  confident-error analysis.
- Compare DistilBERT and RoBERTa on the four-category AG News dataset using
  predictive performance, inference time, and model disagreements.

## Before You Begin

Google Colab with a T4 GPU runtime is recommended. Mount Google Drive before
running Part 1 and confirm that `solarenergytweets.csv` is available at the path
specified in the notebook. Internet access is required to download the Hugging
Face datasets and pretrained models. If a package is unavailable, uncomment and
run the optional installation cell at the beginning of the notebook.
