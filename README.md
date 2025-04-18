# 📰 Fake News Detection using Deep Learning

## 📖 Overview
This project aims to automatically detect fake news articles using deep learning techniques. With the increasing spread of misinformation across digital platforms, this system serves as a scalable solution to identify and filter out deceptive content in real-time.

Our model uses Natural Language Processing (NLP) techniques and neural networks to classify news articles into "Fake" or "Real", trained on the publicly available ISOT dataset.

## 💡 Problem Statement
The rapid proliferation of fake news on digital platforms has emerged as a major concern. This fake content can mislead the public, sway political decisions, and destabilize societies. Manual fact-checking can't keep up with the volume and speed of fake news generation.

Hence, we propose a deep learning-based model to automatically classify articles as real or fake using text-based features.


## 🔍 Dataset
We use the **ISOT Fake News Dataset** from the University of Victoria. It contains:
- **Real news**: Collected from Reuters
- **Fake news**: Collected from unreliable news sources

Dataset Link: [ISOT Dataset](https://onlineacademiccommunity.uvic.ca/isot/2022/11/27/fake-news-detection-datasets/)

## ⚙️ Installation & Setup

### Step 1: Clone the Repository
### Step 2: Create a Virtual Environment (Optional but Recommended)
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

### Step 3: Install Dependencies
```bash
pip install -r requirements.txt
```

---

## 🚀 Running the Project

1. **Preprocess the Dataset**  
   Open and run `DL_PROJECT(DATASET).ipynb` to load and preprocess the data.

2. **Train the Model**  
   Open and run `DL_PROJECT.ipynb` to build, train, and evaluate the deep learning model.

---

## 📈 Evaluation Metrics

| Metric      | Description                                |
|-------------|--------------------------------------------|
| Accuracy    | Overall correctness of the model           |
| AUC         | Area under the ROC curve                   |
| Precision   | Correctness of positive (fake) predictions |
| EER         | Point where FAR and FRR are equal          |

---

## 📊 Model Architecture
The model uses:
- Text tokenization using `nltk`
- TF-IDF vectorization
- Deep neural network with dropout for regularization
- Softmax for binary classification

See `report.pdf` for a visual block diagram.

---

## 🧠 Technologies Used

- Python
- TensorFlow / Keras
- Scikit-learn
- Pandas / NumPy
- NLTK
- Seaborn / Matplotlib

---

## 📌 Future Work
- Incorporating visual content (images/memes)
- Real-time news API integration
- BERT or transformer-based classification
- Multilingual fake news detection

---

## 🧑‍💻 Author
""Srihitha Pulapa, CS22B2009""
""Rikitha Ravi, CS22B2045"
---
