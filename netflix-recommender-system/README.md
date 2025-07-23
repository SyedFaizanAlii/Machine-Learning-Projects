# 🎬 Netflix Movie Recommender System

This project builds a personalized movie recommender using Collaborative Filtering and SVD on the Netflix Prize dataset. It includes full data cleaning, EDA, model building, evaluation, and explanation.

📂 **Files inside this folder**:
- `netflix_recommender.ipynb`: Jupyter Notebook with complete step-by-step workflow
- `README.md`: Project overview

📌 Built entirely using Kaggle notebooks — all data manipulation, modeling, and visualization done using:
- `Pandas`, `NumPy`, `Matplotlib`, `Seaborn`
- `Surprise Library` for recommendation model
 
# 🤖 Collaborative Filtering + Matrix Factorization | Real-World ML Project

Welcome to this end-to-end machine learning project where we build a **Netflix-style personalized movie recommendation engine** using the **Netflix Prize Dataset**.

This notebook is designed not just to run — but to **teach**, **explain**, and **demonstrate** how real-world recommender systems are built step by step.

---

## 🎯 Objective

To simulate how Netflix recommends content by:
- Learning from user-movie interaction data
- Building models that can predict what a user will enjoy next
- Keeping the system **efficient**, **interpretable**, and **deployable-ready**

---

## 📦 Dataset: Netflix Prize Data  
- Contains over **100 million ratings**
- We use a **subset (combined_data_1.txt + movie_titles.csv)** for memory efficiency
- Data includes `user_id`, `movie_id`, `rating`, `date`, and `title`

---

## 🔍 Techniques Used

| Model Type | What it does |
|------------|--------------|
| 🧍 User-Based CF (UBCF) | Recommends movies based on similar users |
| 🎥 Item-Based CF (IBCF) | Recommends movies similar to ones user already liked |
| 📐 Matrix Factorization (SVD) | Learns user and item features to predict ratings |

---

## 🧠 What's Special About This Notebook?

✅ Raw Netflix data parsed manually (no pre-processed files)  
✅ Every model explained with markdown — no blind code  
✅ All charts created using `matplotlib` and `seaborn`  
✅ No unnecessary libraries, no overengineering  
✅ Focused on **real ML logic**, not flashy visuals

---

> ⚠️ Note: This project is optimized to run within **Kaggle kernels** without exceeding RAM.  
> We avoided heavy libraries (like deep learning or Streamlit) to focus on core recommender system principles.

---

Let’s build your own **Netflix recommender** — from scratch 🔧🔥

