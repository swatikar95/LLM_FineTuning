### Overview

This repository contains scripts for fine-tuning large language models (LLMs) on specific text data named 'lamini_docs.jsonl'. 


### Scripts

- `data_prep.py`: Manages the preprocessing of text data including tokenization, padding, and truncation using a tokenizer from EleutherAI's `pythia-70m` model.
- `training.py`: Implements the fine-tuning of an LLM with detailed configuration of training parameters using the Hugging Face `Trainer` class.