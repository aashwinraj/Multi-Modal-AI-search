# Multi-Modal-AI-search
# 🧠 Fashion Product Image Search Engine

This project is a **multi-modal product search engine** that allows users to input a **text querry or an image query** and retrieves the **top matching fashion product images** from a dataset using deep learning and vector similarity.

It uses **CLIP (Contrastive Language–Image Pre-training)** for creating embeddings from both images and text, and **FAISS** for efficient nearest neighbor search.

---

## 📁 Dataset

We use a subset of the [Fashion Product Images (Small)](https://www.kaggle.com/datasets) dataset from Kaggle, consisting of:

- ~15,000 product images
- `styles.csv`: CSV file mapping product metadata
- `styles/`: Folder containing per-image JSON files with `category`, `subcategory`, and descriptions


querry: red shirts for men:
Output:top 5 matching images:
![{A288AB88-5431-4C0F-9672-31671DF288A0}](https://github.com/user-attachments/assets/79ff89da-390e-43bf-8065-213ac32f78be)

querry:
![1525](https://github.com/user-attachments/assets/cb159c5b-31c3-4d9b-822a-fd0083048108)


Oytput:![{A785ACCC-28F6-4179-A070-15E8835D6FD8}](https://github.com/user-attachments/assets/7ba3a1ba-e26b-4a72-ba43-c528916aed68)


