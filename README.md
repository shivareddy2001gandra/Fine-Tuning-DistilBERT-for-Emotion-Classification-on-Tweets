# Fine-Tuning-DistilBERT-for-Emotion-Classification-on-Tweets


This project fine-tunes a DistilBERT model on the [dair-ai/emotion dataset](https://huggingface.co/datasets/dair-ai/emotion) to classify text into six emotions: sadness, joy, love, anger, fear, and surprise.

## Requirements
- Python 3.11
- Install dependencies: `pip install transformers datasets scikit-learn`
- GPU recommended (e.g., Google Colab with T4 GPU)

## Results
- **Accuracy**: 92.55%
- **Weighted F1-Score**: 92.51%
- Classification Report:
  | Emotion  | Precision | Recall | F1-Score | Support |
  |----------|-----------|--------|----------|---------|
  | Sadness  | 0.97      | 0.95   | 0.96     | 591     |
  | Joy      | 0.95      | 0.94   | 0.95     | 697     |
  | ...      | ...       | ...    | ...      | ...     |

## How to Run
1. Clone the repo: `git clone <repo-url>`
2. Open `Fine_Tuning.ipynb` in Jupyter Notebook or Google Colab
3. Follow the steps in the notebook

