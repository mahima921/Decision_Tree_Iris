# Decision Tree with Pre-Pruning and Post-Pruning 🌳

## 📌 Introduction
This project demonstrates the implementation of a **Decision Tree Classifier** using the Iris dataset.  
The main goal is to understand the problem of **overfitting** and how **pruning techniques** can improve generalization.

## ⚡ Steps in the Project
- Loaded the Iris dataset
- Built a baseline Decision Tree **without pruning**
- Implemented **Pre-Pruning** (using `max_depth`, `min_samples_split`, `min_samples_leaf`)
- Implemented **Post-Pruning**
- Compared results of all three approaches

## 📊 Key Insights
- **Without Pruning:** The tree tends to overfit the data  
- **Pre-Pruning:** Restricts tree growth early, reduces overfitting but may underfit  
- **Post-Pruning:** Grows full tree first, then prunes back → better balance between bias & variance  

## 🚀 Conclusion
Pruning makes decision trees more **accurate, generalizable, and interpretable**.  
It helps avoid overfitting and improves model performance in real-world scenarios.

---
