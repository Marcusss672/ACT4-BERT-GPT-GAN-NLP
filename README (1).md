# ACT4-BERT-GPT-GAN-NLP

Multi-variant text analysis and generation using BERT, GPT-2, and GAN-based approaches. This project explores text classification, language generation, and model evaluation across multiple deep learning architectures.

## Overview

This notebook implements and compares three NLP model variants:

- **BERT** – fine-tuned for sequence classification tasks
- **GPT-2** – used for autoregressive text generation
- **GAN** – applied for generative text modeling

Model outputs are evaluated using standard NLP metrics including BLEU score, precision, recall, F1-score, and accuracy.

## Project Structure

```
.
├── notebooks/   # Jupyter notebook with full implementation
├── result/      # Output results and generated artifacts
└── README.md
```

## Tech Stack

- Python
- PyTorch
- Hugging Face Transformers (BERT, GPT-2)
- TensorFlow/Keras (text preprocessing utilities)
- scikit-learn (evaluation metrics)
- NLTK (BLEU score)
- pandas, numpy, matplotlib

## Setup

```bash
pip install transformers datasets torch scikit-learn nltk
```

The notebook was developed and run on Google Colab, with data accessed via Google Drive.

## Usage

1. Open `notebooks/Act_4_Multi_Variant_Text_Analysis_and_Generation_(BERT,_GPT,_and_GANs).ipynb` in Jupyter or Google Colab.
2. Run the cells sequentially to install dependencies, load data, train/fine-tune each model variant, and generate evaluation results.
3. Generated outputs and result artifacts are saved to the `result/` folder.

## Evaluation Metrics

- BLEU score (corpus and sentence-level)
- Accuracy, Precision, Recall, F1-score

## References

McKinney, W. (2010). Data structures for statistical computing in Python. *Proceedings of the 9th Python in Science Conference (SciPy 2010)*, 56–61. https://doi.org/10.25080/Majora-92bf19e-00a
