# Multi-Label Classification using Transformers

This repository contains notebooks associated with the article **Classification in the Era of Transformers**. The article explores five major techniques for performing multi-label classification using transformer-based models:

1. **Classifier using BERT embeddings**  
2. **Fine-tuning transformers with classification heads**  
3. **Sentence Transformers Fine-tuning (SetFit)**  
4. **Prompting Large Language Models (LLMs) — decoder-only**  
5. **Instruction tuning of LLMs — decoder-only**

---

## Table of Contents

- [Dataset](#dataset)
- [Notebooks](#notebooks)
- [Usage](#usage)
- [License](#license)

---

## Dataset

The `dataset` folder contains a CSV file for a multi-label classification dataset originally sourced from [Kaggle](https://www.kaggle.com/datasets/shivanandmn/multilabel-classification-dataset/data).

- The processed version of this dataset is available on the Hugging Face Hub:  
  **[bhujith10/multi_class_classification_dataset](https://huggingface.co/datasets/bhujith10/multi_class_classification_dataset)**

- The code used for creating and uploading this dataset can be found in **[`notebooks/Dataset_creation.ipynb`](notebooks/Dataset_creation.ipynb)**.

---

## Notebooks

This repository includes several Jupyter notebooks, each demonstrating a different technique:

1. **Fine-tuning Transformers with a Classification Head**  
   - **[`notebooks/Finetuning_transformers_with_classification_head_for_multi_label_classification.ipynb`](notebooks/Finetuning_transformers_with_classification_head_for_multi_label_classification.ipynb)**  
   Covers the first two techniques:  
     - Classifier using BERT embeddings  
     - Fine-tuning a transformer with a classification head

2. **SetFit Fine-tuning**  
   - **[`notebooks/SetFit_finetuning_of_transformers_for_multi_label_classification.ipynb`](notebooks/SetFit_finetuning_of_transformers_for_multi_label_classification.ipynb)**  
   Demonstrates the third technique using the SetFit framework for multi-label classification.

3. **Prompting GPT Models**  
   - **[`notebooks/Multi_Label_classification_using_GPT_models.ipynb`](notebooks/Multi_Label_classification_using_GPT_models.ipynb)**  
   Showcases how to leverage GPT models and other open source LLMs (decoder-only) via prompting, corresponding to technique four.

4. **Instruction Tuning Open-Source LLMs**  
   - **[`notebooks/Instruction_tuning_transformers_for_multi_label_classification.ipynb`](notebooks/Instruction_tuning_transformers_for_multi_label_classification.ipynb)**  
   Demonstrates how to instruction-tune open-source decoder-only LLMs for multi-label classification, which is the fifth technique.

---
