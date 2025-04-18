# 📰 Fake News Detection (LSTM)

This project uses an LSTM-based deep learning model to classify news articles as **real** or **fake** based on their text.

## 📊 Dataset

- 44,898 articles (Balanced)
  - Real: 21,417
  - Fake: 23,481
- We also explored the amount of data in various topics and the data available per year.
- We also observed that the text size was maximum 500 for most cases
    
  ![image](https://github.com/user-attachments/assets/f462b659-2d5a-4931-8ba1-14e24bcfbcc0)
  ![image](https://github.com/user-attachments/assets/b6282942-9fa0-490d-9ae6-5fcd94fe78cd)
  ![image](https://github.com/user-attachments/assets/e41c91d8-17b0-461e-936d-effbbb48dd0e)
  ![image](https://github.com/user-attachments/assets/c1d43cc0-50b6-4c7c-bf97-fe618d7bd634)
  ![image](https://github.com/user-attachments/assets/4020e288-6d3a-4fef-b30c-1fca2d160ed9)
  ![image](https://github.com/user-attachments/assets/7efe2ab2-2923-44fa-b4dd-6f2776d3d201)


  

## ⚙️ Preprocessing

- Merged title + text
- Lowercased, removed punctuation/digits/stopwords
- Tokenized & padded to 500 tokens

## 🧠 Model

- Embedding (vocab=5000, dim=32)
- LSTM (100 units)
- Dense + Sigmoid  
- Loss: Binary Crossentropy  
- Optimizer: Adam  
- Epochs: 5 | Batch Size: 64

## ✅ Results

![WhatsApp Image 2025-04-18 at 13 36 53_acb90b81](https://github.com/user-attachments/assets/cc2d7d07-4561-47cd-ba91-7fd8338841b0)

## 👥 Authors

- Srihitha Pulapa (CS22B2009)  
- Rikitha Ravi (CS22B2045)
