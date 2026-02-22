# 📧 Spam Email Detector

A simple Machine Learning web app built using **Streamlit** that detects whether an email message is **Spam** or **Not Spam**.

The model uses:

* TF-IDF Vectorization
* Linear Support Vector Machine (SVM)

---

## 🚀 Features

✅ Detects spam emails instantly
✅ Clean Streamlit UI
✅ Machine Learning powered classification
✅ Real-time prediction
✅ Displays model accuracy
✅ No external dataset required

---

## 🛠️ Tech Stack

* Python
* Streamlit
* Scikit-learn
* TF-IDF Vectorizer
* Linear SVM

---

## 🧠 Machine Learning Model

The system uses:

* **TF-IDF (Term Frequency - Inverse Document Frequency)** for text feature extraction
* **LinearSVC (Support Vector Machine)** for classification

Pipeline:

Text → TF-IDF → SVM → Prediction

---

## 📂 Project Structure

Spam-Email-Detector/
│── spam_app.py      # Main Streamlit app
│── README.md        # Documentation

---

## ▶️ Run Locally

### 1️⃣ Install Dependencies

```bash
pip install streamlit scikit-learn
```

---

### 2️⃣ Run the App

```bash
streamlit run spam_app.py
```

---

### 3️⃣ Open in Browser

Streamlit will generate a local URL like:

[http://localhost:8501](http://localhost:8501)

---

## 📊 Model Accuracy

The model is trained on a small sample dataset and typically achieves around:

~80% - 100% accuracy (due to limited demo dataset)

---

## 🧪 How It Works

1. User enters an email message
2. Text is converted into TF-IDF vectors
3. SVM model classifies it
4. Output is shown as:

* 🚨 Spam
* ✅ Not Spam

---

## 🎯 Learning Outcomes

This project demonstrates:

* Text preprocessing
* Feature extraction
* Supervised ML classification
* Streamlit deployment
* Real-time prediction

---

## 📸 Future Improvements

* Use larger real-world dataset
* Add probability score
* Show confidence level
* Deploy on Streamlit Cloud
* Add file upload option

---

## 👨‍💻 Author

Yash Tripathi
