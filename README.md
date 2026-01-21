# BookWise — KNN-Based Book Recommendation Engine

A lightweight machine learning recommendation engine that suggests similar books using **K-Nearest Neighbors (KNN)** based on user ratings and similarity scores.

---

## ✨ Features
- 🔍 Content-based recommendation using similarity metrics  
- 📚 Works with book ratings dataset  
- 🧠 Powered by KNN algorithm  
- 🚀 Fast & minimal dependency footprint  
- 🎯 Great for ML learning projects & demos  

---

## 📂 Project Structure
```
├── data/               # book + rating datasets  
├── notebook.ipynb      # model training & experimentation  
├── model.py            # KNN recommendation module (optional)  
├── requirements.txt    # Python dependencies  
├── README.md           # project documentation
```

---

## 🧰 Tech Stack
- Python  
- NumPy  
- Pandas  
- Scikit-learn  

---

## ⚙️ How It Works
1. Loads & preprocesses dataset  
2. Creates a pivot matrix (users × books)  
3. Computes similarity using KNN  
4. Returns top N similar books  

---

## 🚀 Usage Example
```python
from model import recommend

recommend("The Hobbit", top_n=5)
```

Example Output:
```
1. The Lord of the Rings  
2. The Silmarillion  
3. Harry Potter and the Sorcerer's Stone  
...
```

---

---

## 📦 Installation
```bash
pip install -r requirements.txt
```

---


