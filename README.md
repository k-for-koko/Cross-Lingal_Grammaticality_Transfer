# Cross-Lingal_Grammaticality_Transfer

Implementing XLM-R model from Facebook AI to see how it performs on the task of grammaticality judgement in a cross-lingual setting.
XLM-R model is implented using HuggingFace transformers library and trained on the English CoLA dataset ("in_domain_train.tsv").
The model is then tested on English (baseline), French, and Chinese data ("out_of_domain_dev.tsv", "french_data.csv", "chinese_data.csv").

Please run .ipynb file for Python notebook environment.
