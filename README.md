# MSCS_634_Lab_2  
**Classification Using KNN and RNN Algorithms**  
**Name:** Bishesh  
**Date:** November 3, 2025  

## Purpose
This lab explores the performance of **K-Nearest Neighbors (KNN)** and **Radius Neighbors (RNN)** classifiers using the Wine dataset from sklearn. The goal is to understand how parameter selection impacts classification accuracy.

## Dataset
- **Source:** Built-in sklearn Wine dataset  
- **Features:** 13 chemical properties of wines  
- **Classes:** 3 wine types  
- **Class distribution:** class_0: 59, class_1: 71, class_2: 48  

## Key Steps
1. Loaded and standardized the dataset.  
2. Split data into 80% training and 20% testing sets.  
3. Implemented KNN with k = 1, 5, 11, 15, 21.  
4. Implemented RNN with radius = 350, 400, 450, 500, 550, 600 (scaled for standardized data).  
5. Plotted accuracy trends and compared performance between the two algorithms.  

## Key Insights
- **KNN:** Accuracy improves with more neighbors, reaching 100% for k ≥ 11.  
- **RNN:** Accuracy is highest at a smaller radius (350) and decreases as radius increases.  
- **Comparison:** KNN achieves consistently higher accuracy for moderate k values, while RNN performs best with a smaller radius.  

## Conclusion
Parameter choice significantly affects model performance. For this dataset:
- **KNN:** k ≥ 11 is optimal.  
- **RNN:** radius = 350 is optimal.  

## Tools Used
- Python (NumPy, Pandas, Matplotlib, Scikit-learn)  
- Jupyter Notebook
