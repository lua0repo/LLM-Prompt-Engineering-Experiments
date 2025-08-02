# LLM-Prompt-Engineering-Experiments
Python notebooks or scripts that show data preprocessing, model training, or evaluation on smaller datasets.

# LLM Security NLP Suite

## Overview
This project includes:
- Prompt engineering test scripts
- ML phishing classifier (Logistic Regression + TF-IDF)
- Stub for fine-tuning an LLM on a security dataset

## Structure
/prompts → Prompt engineering tests
/phishing_detector → Classic ML phishing classifier
/fine_tuning → Notebook stub for LLM training


## Requirements
- Python 3.9+
- `openai`, `sklearn`, `pandas`, `jupyter`

## How to Use

### 1. Prompt Testing
```bash
export OPENAI_API_KEY=your_key_here
python prompts/prompt_tests.py
