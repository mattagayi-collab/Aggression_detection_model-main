# Abusive Level Multiclass Text Classification Model

## Idea:
Multiclass text classification based on TFIDF 

## Model
Naive Bayes Classifier for Multinomial Models

## Validation Method
kFold (k = 10)

## Dataframe columns

- user
- abusive_level
  - Not abusive
  - Ambiguous
  - Mildly abusive
  - Strongly abusive
  - Very strongly abusive

## How to use
- Click on the link to open Google Colab which can be found in `abusive_speech_detection.ipynb`
- Run each code block, except the last one
- Change the text in quotes that can be found in the last code block to the sentence you want to input into the model
- Run the last code block

---
@inproceedings{cercas-curry-etal-2021-convabuse,
title = "{C}onv{A}buse: Data, Analysis, and Benchmarks for Nuanced Abuse Detection in Conversational {AI}",
author = "Cercas Curry, Amanda and
Abercrombie, Gavin and
Rieser, Verena",
booktitle = "Proceedings of the 2021 Conference on Empirical Methods in Natural Language Processing",
month = nov,
year = "2021",
address = "Online and Punta Cana, Dominican Republic",
publisher = "Association for Computational Linguistics",
url = "https://aclanthology.org/2021.emnlp-main.587",
doi = "10.18653/v1/2021.emnlp-main.587",
pages = "7388--7403"
}

## Slides
[Google Slides](https://docs.google.com/presentation/d/1a0ZMqQk33PdaptESNBiKfLoxsBD4U5R3Y-0g5udHxnk/edit?usp=sharing)
