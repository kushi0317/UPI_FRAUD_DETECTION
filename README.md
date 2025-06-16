# 💳 UPI Fraud Detection Using Machine Learning

## 📌 Abstract

- With the rapid increase in UPI usage for online payments, the number of fraudulent activities is also rising.
- UPI frauds pose a serious threat to financial security and can cause significant losses to both users and financial institutions.
- This project explores how Hidden Markov Models (HMM) and machine learning techniques can be used to detect fraud in UPI transactions.
- Initially, an HMM is trained for a cardholder’s transaction pattern. If a transaction deviates significantly from the learned behavior, it is flagged as fraudulent.
- Along with HMM, we implemented and compared 5 different machine learning algorithms to detect UPI fraud, analyzing their accuracy and effectiveness.

---

## 🧩 Problem Definition

- Real-world UPI fraud detection is challenging due to the unavailability of public, labeled transaction datasets.
- Financial data is sensitive and must be kept confidential to maintain user privacy.
- Data often contains **noise**, such as incorrect or inconsistent records, which hampers model accuracy.
- Due to this noise, generalization becomes difficult no matter how extensive the training set is.
- A robust approach is required to handle such issues while still providing accurate detection of fraud.

---

## ✅ Advantages

- Offers **high security** against unauthorized use of UPI.
- Prevents fraudulent use of card or UPI credentials in online transactions.
- Detects if a card/UPI is being used by unauthorized users, e.g., when a card is lost.

---

## 🧪 Methodology

- Multiple models were trained and evaluated including:
  - Hidden Markov Models (HMM)
  - Convolutional Neural Networks (CNN)
  - Random Forest
  - Decision Tree
  - K-Nearest Neighbors (KNN)
  - Support Vector Machine (SVM)
  - Naive Bayes
- The dataset was preprocessed to handle class imbalance and noise.
- Each algorithm was tested, and accuracy scores were recorded and compared.

---

## 📊 Model Performance Comparison

| Algorithm Name               | Relative Accuracy |
|-----------------------------|-------------------|
| Convolutional Neural Network (CNN) | ⭐ Highest        |
| Random Forest               | 🔼 High           |
| Decision Tree               | 🔼 High           |
| K-Nearest Neighbors (KNN)   | 🔸 Moderate       |
| Support Vector Machine (SVM)| 🔸 Moderate       |
| Naive Bayes                 | 🔽 Low            |

> ⚠️ *Exact percentage values were not available, but the ranking is based on the visual chart analysis.*

---

## 🔚 Conclusion

- UPI fraud is a growing concern and needs advanced solutions to combat.
- Fraudulent activities cause **huge financial losses**, prompting UPI platforms to invest in fraud detection techniques.
- This study provides a comparison of machine learning algorithms for identifying fraudulent UPI transactions.
- The **goal** is to offer a solution that is accurate, efficient, and cost-effective for real-world deployment by UPI service providers.
