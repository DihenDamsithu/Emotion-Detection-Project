# Emotion Detection: A Comparative Analysis

### A comprehensive analysis of Machine Learning and Transformer models for multi-label emotion detection on the GoEmotions dataset.

This repository contains the code and resources for the project "Emotion Detection: A Comparative Analysis," which evaluates the performance of classic machine learning models against modern Transformer architectures. The key achievement of this project is a fine-tuned RoBERTa model that demonstrates high sensitivity with a state-of-the-art recall score.

---

## 🚀 Features

- **Comprehensive Analysis:** Compares 4 different models (Logistic Regression, Random Forest, DistilBERT, and RoBERTa).
- **Multi-Label Classification:** Tackles the complex task of predicting multiple emotions for a single piece of text.
- **In-Depth EDA:** Includes detailed Exploratory Data Analysis on the GoEmotions dataset, highlighting the severe class imbalance.
- **High-Recall Model:** The fine-tuned RoBERTa model achieves a weighted average recall of 0.66, demonstrating high sensitivity.
- **Code:** All code is provided in easy-to-follow Jupyter/Colab notebooks.

---

## 📖 Methodology

The project workflow is divided into two parallel approaches:

1.  **Classic Machine Learning Baseline:**
    - Text is vectorized using **TF-IDF**.
    - **Logistic Regression** and **Random Forest** models are trained using a `MultiOutputClassifier`.

2.  **Transformer Fine-Tuning:**
    - Text is tokenized using specific tokenizers for **DistilBERT** and **RoBERTa**.
    - The pre-trained models are fine-tuned on the GoEmotions dataset using PyTorch and Hugging Face.


---

## 📊 Results

The results clearly show the superiority of Transformer models. Our fine-tuned **RoBERTa** model achieved the best performance, most notably a high recall score, indicating its effectiveness at identifying emotions.


A key finding was the **precision-recall trade-off**, a direct consequence of the dataset's class imbalance. While our model excels at finding emotions (high recall), it sometimes over-predicts, leading to lower precision.

---

## 🛠️ How to Use

To run this project, follow these steps:

1.  **Clone the repository:**

2.  **Install the dependencies:**
    ```bash
    pip install -r requirements.txt
    ```
3.  **Download the dataset:**
    The `GoEmotions.csv` dataset is included in this repository.

4.  **Run the notebooks:**
    Open the files in the `notebooks/` directory using Jupyter Notebook, JupyterLab, or Google Colab.

---

## 👥 Authors

- **Mahmud** - [GitHub](https://github.com/Cyber-Mood/) - [LinkedIn](https://www.linkedin.com/in/mahmud-112ab0255/)
- **Tanjila Hussen**

*(Feel free to add your profile links here!)*
