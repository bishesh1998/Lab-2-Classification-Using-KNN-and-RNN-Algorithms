# Lab 2: Classification Using KNN and RNN Algorithms
**Name:** Bishesh  
**GitHub:** https://github.com/bishesh1998/Lab-2-Classification-Using-KNN-and-RNN-Algorithms  
**Date:** November 3, 2025  

## Purpose
This lab evaluates the classification performance of **KNN** and **RNN** on the Wine dataset (sklearn), focusing on how parameter choices influence accuracy.

## Dataset
- **Features:** 13 chemical properties of wines  
- **Classes:** 3 wine types  
- **Class distribution:** 59, 71, 48 samples per class  

## Methodology
- Standardized the dataset and split into 80% training and 20% testing.  
- Tested **KNN** with k = 1, 5, 11, 15, 21 and visualized accuracy trends.  
- Tested **RNN** with radius = 350–600 (scaled) and compared accuracy trends with KNN.  

## Results
- **KNN Accuracy:** k=1: 0.9722, k=5: 0.9722, k=11: 1.0000, k=15: 1.0000, k=21: 1.0000  
- **RNN Accuracy:** radius=350: 1.0000, radius=400: 0.9444, radius=450: 0.9167, radius=500: 0.8611, radius=550: 0.8333, radius=600: 0.7500  

KNN achieved 100% accuracy for k ≥ 11, while RNN performed best with a smaller radius (350). Overall, KNN outperformed RNN for moderate parameter values.

## Conclusion
Parameter selection significantly impacts classification performance. For this dataset, **KNN with k ≥ 11** and **RNN with radius 350** are optimal, with KNN providing the best overall performance.

## References
- Katumullage, D., Yang, C., Barth, J., & Cao, J. (2022). Using neural network models for wine review classification. *Journal of Wine Economics, 17*(1), 27-41.  
- Vrigazova, B. (2021). The proportion for splitting data into training and test set for the bootstrap in classification problems. *Business Systems Research: International Journal of the Society for Advancing Innovation and Research in Economy, 12*(1), 228-242.
