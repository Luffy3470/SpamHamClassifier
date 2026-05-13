# SpamHamClassifier
# 🤖 DistilBERT Spam Classifier

A high-performance NLP project that classifies SMS/Email messages as **Spam** or **Ham** using the powerful **DistilBERT Transformer Model** from Hugging Face Transformers.

This project leverages **Transfer Learning** and **Deep Learning for NLP** to achieve highly accurate spam detection.

---

# 🚀 Features

- Transformer-based Spam Detection
- Fine-tuned DistilBERT model
- High accuracy classification (~97%)
- Fast inference using lightweight BERT architecture
- NLP preprocessing pipeline
- Real-time text prediction support

---

# 🛠️ Tech Stack

- Python
- PyTorch
- Hugging Face Transformers
- Scikit-learn
- Pandas
- NumPy
- Matplotlib

---

# 🧠 Model Architecture

This project uses:

## 📌 DistilBERT

DistilBERT is a smaller, faster, and lighter version of BERT that retains most of BERT's language understanding capabilities while reducing computational cost.

Advantages:
- Faster training
- Lower memory usage
- High NLP performance
- Efficient for deployment

---

# 📂 Project Structure

```bash
distilbert-spam-classifier/
│
├── data/
│   └── spam.csv
│
├── notebooks/
│   └── training.ipynb
│
├── models/
│   └── distilbert_model/
│
├── app.py
├── train.py
├── predict.py
├── requirements.txt
└── README.md
```

---

# ⚙️ Workflow

1. Data Collection
2. Text Cleaning
3. Tokenization using DistilBERT Tokenizer
4. Fine-tuning DistilBERT
5. Model Evaluation
6. Spam/Ham Prediction

---

# 📊 Model Performance

| Metric | Score |
|--------|--------|
| Accuracy | ~97% |
| Precision | High |
| Recall | High |
| F1-Score | Strong |

---

# ▶️ Installation

Clone the repository:

```bash
git clone https://github.com/your-username/distilbert-spam-classifier.git
cd distilbert-spam-classifier
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

# ▶️ Run the Project

Train the model:

```bash
python train.py
```

Run predictions:

```bash
python predict.py
```

Launch app:

```bash
python app.py
```

---

# 💡 Example Predictions

| Message | Prediction |
|----------|------------|
| "Congratulations! You won ₹50,000." | Spam |
| "Meeting has been rescheduled to tomorrow." | Ham |

---

# 📈 Future Improvements

- Deploy using Flask/FastAPI
- Build Streamlit Web App
- Multi-language Spam Detection
- Email Integration
- Real-time API Deployment

---

# 🤝 Contributing

Contributions are welcome. Feel free to fork the repository and submit pull requests.

---

# 📜 License

This project is licensed under the MIT License.

---

# 👨‍💻 Author

**Roshan Bhaskar**  
AI/ML Enthusiast | NLP Learner 

```
