# 🩺 Heart Failure Risk Classification  
**Comparison of Random Forest and Support Vector Machine (SVM)**  

This repository contains a study applying machine learning algorithms to classify the Heart Failure dataset. The dataset includes medical records of patients, aiming to predict the likelihood of heart disease occurrence. Two widely-used machine learning algorithms, Random Forest and Support Vector Machine (SVM), are compared to evaluate their performance.  

---

## 🚀 Research Highlights  
- **📋 Data Preprocessing:**  
  - ✅ Missing value handling, duplicate removal, and outlier detection using the Interquartile Range (IQR) method.  
  - 🔧 Data cleaning ensures high-quality input for model training and testing.  

- **📈 Model Evaluation:**  
  - 🎯 Random Forest achieved an accuracy of **89.33%**, outperforming SVM, which reached **81.33%**.  
  - 💡 Random Forest demonstrated superior handling of complex, non-linear relationships between features.  
  - ⚡ SVM performed well with simpler data structures, but Random Forest showed greater stability with higher variability.  

- **📊 Performance Metrics:**  
  - Evaluated using **classification report** and **confusion matrix**.  
  - 🏆 Random Forest outperformed SVM in **precision**, **recall**, and **F1-score**, particularly in recall for the high-risk class (class 1).  

---

## 📊 Conclusion  
The results suggest that **Random Forest** is a better choice for the Heart Failure dataset due to its robustness with complex data and higher accuracy. However, **SVM** remains a viable option for simpler classification problems.  

---

## 🛠️ Tools & Libraries  
- **💻 Programming Language:** Python  
- **📦 Libraries:**  
  - 🧠 `sklearn` for model implementation and evaluation  
  - 📊 `pandas` and `numpy` for data preprocessing  
  - 🎨 `matplotlib` and `seaborn` for visualization  

---

## 💡 Future Work  
- 🔍 Extend the study with algorithms like Gradient Boosting or Neural Networks.  
- 🔧 Hyperparameter tuning for enhanced performance.  
- 🛠️ Explore feature engineering techniques for better classification accuracy.  

---

Feel free to explore, give feedback, or contribute! 🚀  
