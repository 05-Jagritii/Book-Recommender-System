# 📚 Book Recommender System

A Machine Learning–based **Book Recommendation System** that suggests books to users based on similarity scores.  
The project uses **collaborative filtering** techniques and a pre-trained model to generate personalized recommendations.

---

## 🚀 Features
- Recommends books similar to the user’s input
- Uses cosine similarity on preprocessed data
- Simple and clean web interface built with Flask
- Fast recommendations using pre-trained `.pkl` files

---

## 🛠️ Tech Stack
- **Python**
- **Flask**
- **Pandas**
- **NumPy**
- **Scikit-learn**
- **HTML / CSS**
- **Git LFS** (for large model files)

---

## 📂 Project Structure
Book-Recommender-System/
│
├── app.py
├── books.pkl
├── popular.pkl
├── pt.pkl
├── similarity_score.pkl
├── requirements.txt
├── templates/
│ ├── index.html
│ └── recommend.html
└── README.md


---

## 📦 Model Files
Large model files (`.pkl`) are stored using **Git LFS**:
- `books.pkl`
- `popular.pkl`
- `pt.pkl`
- `similarity_score.pkl`

> Git LFS is used to handle large files efficiently without exceeding GitHub’s size limits.

---

## ▶️ How to Run Locally

### Clone the repository
```bash
git clone https://github.com/05-Jagritii/Book-Recommender-System.git
cd Book-Recommender-System
```

### Install dependencies
```
pip install -r requirements.txt
```

### Run the application
```
python app.py

```


