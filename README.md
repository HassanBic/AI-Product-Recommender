# AI-Driven Smart Product Recommendation System

## 🚀 Project Overview
This is a final-year dissertation project for the School of Computer Science and Mathematics at LJMU. It implements an **Advanced Hybrid Recommendation Engine** designed to provide personalized product suggestions by combining User-Item interactions (Collaborative Filtering) with Product Metadata analysis (NLP).

## 🧠 Key Features (The "Advanced" Edge)
* **Hybrid Architecture:** Uses a weighted ensemble of SVD (Singular Value Decomposition) and TF-IDF vectorization.
* **Cold-Start Solution:** Leverages content-based filtering for new users with zero purchase history.
* **Real-time API:** Built with FastAPI/Flask to serve recommendations instantly.
* **Evaluation Suite:** Measured using RMSE, MAE, and Precision@K metrics.

## 📁 Repository Structure
- `data/`: Datasets used for training (e.g., Amazon/H&M Product Data).
- `notebooks/`: Exploratory Data Analysis (EDA) and Model prototyping.
- `src/`: Core production code (Preprocessing, Modeling, API).
- `docs/`: Dissertation drafts and Project Management reports.

## 🛠️ Tech Stack
- **Language:** Python 3.10
- **AI/ML:** Scikit-learn, Pandas, NumPy, Surprise (for CF), NLTK (for NLP)
- **Deployment:** Streamlit / Flask

## 📥 Installation & Setup
1. Clone the repo: `git clone https://github.com/your-username/your-repo-name.git`
2. Create venv: `python -m venv venv`
3. Install dependencies: `pip install -r requirements.txt`
