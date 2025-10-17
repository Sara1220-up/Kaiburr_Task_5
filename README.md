# 🧩 Kaiburr Task 5 – Data Science Example  
### **Text Classification on Consumer Complaint Dataset**

---

## 🎯 Objective
Perform text classification on the [Consumer Complaint Database](https://catalog.data.gov/dataset/consumer-complaint-database)  
to categorize consumer complaints into the following four categories:

| Label | Category |
|:--:|:--|
| 0 | Credit Reporting, Repair, or Other |
| 1 | Debt Collection |
| 2 | Consumer Loan |
| 3 | Mortgage |

---

## ⚙️ Tech Stack
- **Python 3**
- **Google Colab**
- **Libraries:** pandas, scikit-learn, nltk, matplotlib, seaborn

---

## 🧠 Process Flow
1. **Dataset Loading** – Downloaded and loaded ~50,000 rows from the official Consumer Complaint dataset.  
2. **Data Preprocessing** – Cleaned text data, removed stop words and special characters, balanced the dataset.  
3. **TF-IDF Vectorization** – Converted text into numerical features.  
4. **Model Training** – Trained Logistic Regression model for multi-class classification.  
5. **Evaluation** – Calculated accuracy and generated classification report.  
6. **Prediction** – Tested model on unseen text samples to verify classification.  

---

## 📊 Results
✅ The model successfully classifies complaints into all four categories.  
✅ Example predictions:

| Complaint Text | Predicted Label |
|:--|:--|
| My credit report has wrong information even after dispute. | 0 – Credit Reporting |
| Debt collector keeps calling after full payment. | 1 – Debt Collection |
| The bank increased my mortgage rate without notice. | 3 – Mortgage |

Accuracy achieved: **≈ XX %** *(replace XX with your score from Colab)*

---

## 🖼️ Screenshots (with Name + Date/Time Visible)
### 2️⃣ Packages Downloaded  
![Packages Downloaded](./screenshots/Packages_Downloaded.png)

### 3️⃣ Loading Dataset  
![Loading Dataset](./screenshots/Loading_Dataset.png)

### 1️⃣ Dataset Created  
![Dataset Created](./screenshots/dataset_created.png)

### 4️⃣ Preprocessed Data \ TF-IDF Vectorization)
![Preprocessed Data](./screenshots/Preprocessed_data.png)

### 5️⃣ Splitting Data and Model Training  
![Splitting Data and Model Training](./screenshots/splitting_data_and_Model_Training.png)

### 6️⃣ Prediction on Test Data and Samples  
![Prediction on Test Data and Samples](./screenshots/Prediction_on_test_data_and_samples.png)

---

## ✅ Conclusion
- Task 5 completed successfully in Google Colab.  
- A representative subset of the Consumer Complaint dataset was used for efficient processing while maintaining balanced categories.  
- The model demonstrates reliable classification performance and interpretable results.

---
👩‍💻 Author

Sarayu Mandadi
📦 Kaiburr Internship — Task 5 Submission


 
