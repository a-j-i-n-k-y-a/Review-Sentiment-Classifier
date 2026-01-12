# Review-Sentiment-Classifier

# 📝 Review Sentiment Classifier using BERT

This project implements a binary sentiment classifier for product reviews using a pretrained **BERT base model** fine-tuned with transfer learning. The model predicts whether a review expresses **positive** or **negative** sentiment based on textual content.

The pipeline uses the **Capterra Reviews dataset**, Hugging Face’s **Transformers** library, and PyTorch.

---

## 🚀 Features
- Pretrained **BERT (bert-base-uncased)** for text representation
- Binary sentiment classification (Positive / Negative)
- Frozen base model with fine-tuned classification head
- Train / Validation / Test split
- Tokenization using Hugging Face tokenizer
- Evaluation using **Accuracy** and **ROC-AUC**
- Compatible with Apple Silicon (MPS) and GPU

---

## 📂 Dataset
- Source: Capterra Reviews (Kaggle)
- Labels converted from 5-star ratings:
  - Rating ≥ 4 → Positive
  - Rating < 4 → Negative

---

## ⚙️ Installation

```bash
pip install transformers==4.39.3 huggingface_hub==0.20.3 tokenizers==0.15.2
pip install datasets torch scikit-learn evaluate pandas
````

---

## ▶️ Usage

```bash
python train.py
```

Or run the notebook to train and evaluate the model interactively.

---

## 📊 Metrics

* Accuracy
* ROC-AUC

---

## 🔮 Future Improvements

* Multi-class sentiment classification (1–5 stars)
* Hyperparameter tuning
* Model explainability (SHAP / LIME)
* Deployment as a web API or dashboard

---

## 📌 Author

Ajinkya



