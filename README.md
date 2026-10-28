# LyricSense: NLP Music Genre Classifier

An end-to-end Natural Language Processing pipeline that classifies music genres directly from text-based lyrical content. 

This project extracts text features using TF-IDF vectorization and utilizes a One-vs-Rest Logistic Regression model to categorize songs into their respective genres with high accuracy. The model is deployed via an interactive web application built with Streamlit.

## 🛠️ Tech Stack
* **Language:** Python
* **Machine Learning:** Scikit-learn (Logistic Regression, TF-IDF)
* **Data Processing:** Pandas, NumPy, Joblib
* **Web Interface:** Streamlit

## 📁 Repository Structure
* `app.py`: The Streamlit application script for the frontend interface.
* `LyricSense Model.py`: The data processing and model training pipeline.
* `models/`: Contains the serialized model binaries (`genre_model.pkl` and `tfidf_vectorizer.pkl`).
* `train.csv`: The training dataset containing the lyrics and genres.
* `requirements.txt`: Python package dependencies.

## 🚀 Installation & Usage

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/balloneya/LyricSense.git](https://github.com/balloneya/LyricSense.git)
   cd LyricSense