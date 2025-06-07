# 🧠 Resume Classification System

An intelligent resume classifier built using NLP and Machine Learning algorithms.  
Automatically processes 100+ resumes with **90% accuracy**, supports **batch processing**, and includes a **user-friendly web interface** for easy classification.

---

## 📌 Features

- 🔍 **Automated Resume Parsing & Classification**
- 🧾 **Supports multiple formats** (PDF, DOCX, TXT)
- 🤖 **ML/NLP-based classifier** (e.g., TF-IDF + SVM/Logistic Regression)
- 📊 **Batch resume processing**
- 🌐 **Web Interface** built with Flask/Streamlit
- 📈 Accuracy: ~90%

---

## 🛠️ Tech Stack

- **Programming Language**: Python  
- **Libraries**: Scikit-learn, Pandas, NumPy, NLTK/spaCy, PyPDF2/docx  
- **Web Framework**: Flask / Streamlit  
- **Visualization**: Matplotlib, Seaborn  
- **Others**: Joblib, TQDM, OS, Glob

---

## 📂 Folder Structure



resume-classifier/
│
├── data/                 # Resume samples for training/testing
├── web\_app/              # Flask or Streamlit-based UI
├── models/               # Saved ML model files
├── utils/                # Preprocessing and helper functions
├── notebooks/            # Jupyter notebooks for EDA and experimentation
├── requirements.txt      # Required Python packages
├── app.py                # Main web app script
└── README.md             # Project documentation



---

## 🚀 Getting Started

1. **Clone the repository**
bash
git clone https://github.com/yourusername/resume-classifier.git
cd resume-classifier


2. **Create virtual environment and install dependencies**

bash
python -m venv venv
source venv/bin/activate    # On Windows: venv\Scripts\activate
pip install -r requirements.txt


3. **Train the model (Optional - already trained model included)**

bash
python train_model.py


4. **Run the web app**

bash
python app.py   # or streamlit run app.py


---

## 🧪 Sample Output

* Upload resumes → Get classified into predefined job roles (e.g., Data Scientist, Web Developer, etc.)
* Real-time prediction + Confidence score
* Bulk processing via folder upload

---

## 📈 Accuracy & Evaluation

* Achieved \~90% accuracy using TF-IDF + Logistic Regression
* 5-fold cross-validation
* Performance metrics: Accuracy, Precision, Recall, F1-score

---

## 🤝 Contributions

Contributions, issues, and feature requests are welcome!
Feel free to fork the repo and submit a pull request.

---

## 📧 Contact

For questions or collaborations:
**\[K. Sai Dhanush \[[saidhanush2200@gmail.com]]
---

## 📜 License

This project is licensed under the MIT License.
