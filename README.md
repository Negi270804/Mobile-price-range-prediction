## 📱 Mobile Price Range Prediction

This project uses machine learning classification algorithms to predict the price range of mobile phones based on their features.

### 📊 Dataset

The dataset includes various features such as battery power, RAM, camera specifications, and connectivity features like 3G/4G. The target variable is the **price range**, categorized into:

* 0 — Low cost
* 1 — Medium cost
* 2 — High cost
* 3 — Very high cost

---

### 🔍 Problem Statement

Build a classification model that can accurately predict the price range of a mobile phone using its specifications.

---

### 🧠 Machine Learning Models Used

The following models were implemented and compared:

* Decision Tree Classifier
* Random Forest Classifier
* Gradient Boosting Classifier ✅ *(Best performer)*

---

### ✅ Best Performing Model

**Gradient Boosting Classifier** showed the highest accuracy and best performance in terms of precision and recall on the test dataset.

---

### ⚙️ Features Used

The dataset includes features like:

* `battery_power`
* `ram`
* `px_height`, `px_width`
* `talk_time`, `mobile_wt`
* `dual_sim`, `four_g`, `three_g`, `wifi`
* and more...

Feature selection techniques (like `SelectKBest`) were used to identify top features for improving model accuracy.

---

### 📈 Evaluation Metrics

Models were evaluated using:

* Accuracy
* Precision
* Recall
* F1-score
* Confusion Matrix
* AUC-ROC Curve

---

### 🧪 How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/mobile-price-range-prediction.git
   cd mobile-price-range-prediction
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Run the notebook:

   * Open `Mobile_price_range_prediction.ipynb` using **Jupyter Notebook** or **Google Colab**.

---

### 📌 Conclusion

Among the models tested, the **Gradient Boosting Classifier** provided the best accuracy and generalization. It is suitable for making robust price predictions based on mobile specs.

---

### 📬 Contact

📧 **Nikhil Negi**  
🔗 [LinkedIn](https://www.linkedin.com/in/nikhil-negi-0bb166328)  
📁 [GitHub](https://github.com/Negi270804)



---
