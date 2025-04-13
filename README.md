# AI-Powered Vacation Recommender System

This project is a hybrid AI-based travel recommendation system that suggests personalized tourist destinations and curated tour packages using real-world data from Indonesia. It integrates content-based filtering (TF-IDF + cosine similarity), collaborative filtering (SVD), and logic-based rules to generate intelligent, user-tailored recommendations — even for cold-start users with minimal data.

---

## 📌 Project Overview

This system was developed as part of the AAI 501: Introduction to Artificial Intelligence course at the University of San Diego. It explores how classical machine learning methods can be applied to real-world decision-making and personalization tasks in the tourism industry.

---

## 🚀 Features

- 🔍 Content-based filtering using TF-IDF + cosine similarity on place descriptions
- 🧠 Collaborative filtering using SVD from the `surprise` library
- 📦 Tour package recommendation logic using hybrid scoring
- 🌱 Cold-start support via favorite place input or fallback city-based suggestions
- 📊 Matplotlib visualizations for top recommended packages
- ✅ Handles missing inputs, low-rating history, and invalid user cases

---

## 🧪 Tech Stack

- **Python 3.10.16**
- **Anaconda Environment** (recommended for managing dependencies)
- Jupyter Notebook or VS Code

---

## 🧰 Required Libraries

Install dependencies using `pip` or `conda`. Here's the full list:

```bash
# If using pip:
pip install pandas numpy scikit-learn scikit-surprise matplotlib seaborn

# Or use conda (recommended):
conda create -n vacation-recommender python=3.10.16
conda activate vacation-recommender
conda install pandas numpy scikit-learn matplotlib seaborn
conda install -c conda-forge scikit-surprise