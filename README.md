# 📌 Banknote Authentication using Machine Learning

## 📝 Overview
This project aims to classify banknotes as **real or fake** using machine learning techniques. The dataset, sourced from the **UCI Machine Learning Repository**, consists of statistical features extracted from images of banknotes using **Wavelet Transformation**.

## 📂 Dataset Information
- **Source:** UCI Machine Learning Repository
- **Task:** Binary classification (0 = Fake, 1 = Real)
- **Features:**
  - Variance of Wavelet Transformed Image
  - Skewness of Wavelet Transformed Image
  - Kurtosis of Wavelet Transformed Image
  - Entropy of the Image
- **File:** `banknote_authentication.txt`

## 📊 Methodology
1. Load and preprocess the dataset.
2. Perform exploratory data analysis (EDA).
3. Train machine learning models (e.g., Logistic Regression, SVM, Random Forest, etc.).
4. Evaluate model performance using accuracy, precision, recall, and F1-score.
5. Deploy or visualize results.

## 🚀 How to Run the Notebook
1. Clone the repository:
   ```bash
   git clone https://github.com/MasterShomya/BankNote-Authentication.git
   cd BankNote-Authentication
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Open and run the Jupyter Notebook:
   ```bash
   jupyter notebook banknote-authentication.ipynb
   ```

## 🛠 Technologies Used
- Python
- NumPy & Pandas
- Matplotlib & Seaborn
- Scikit-Learn (for ML models)
- Jupyter Notebook

## 📜 License
This project is licensed under the **Apache 2.0 License**.

## 📌 Acknowledgments
- The dataset was contributed by Dr. Volker Lohweg (University of Applied Sciences, Ostwestfalen-Lippe, Germany).
- Data sourced from the **UCI Machine Learning Repository**.

---
✉️ Feel free to reach out if you have any questions or contributions!
