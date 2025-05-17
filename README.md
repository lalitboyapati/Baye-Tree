# 🌳🧠 Baye-Tree: Integrating Naive Bayes into Decision Trees

This hybrid classification model combines the interpretability of **Decision Trees** with the probabilistic efficiency of **Naive Bayes**. By embedding Naive Bayes at intermediate and leaf nodes of a decision tree, the Baye-Tree aims to mitigate overfitting and improve generalization on structured data.

## 📄 Paper
Read the full paper here: [`Q2_Machine_Learning_Paper.pdf`](paper/Q2 Machine Learning Paper.pdf)

## 📊 Datasets Used
- [Contraceptive Method Choice Dataset (UCI)](https://doi.org/10.24432/C59W2D)
- Titanic (Seaborn)
- Mushroom Dataset (UCI)
- MNIST (Scikit-learn)
- Buys Computer (internal demo)

## 📈 Results Summary

| Dataset        | Decision Tree Acc | Baye-Tree Acc |
|----------------|-------------------|---------------|
| CMC            | 47.46%            | 53.90%        |
| Titanic        | 81.46%            | 80.90%        |
| Mushroom       | 100.00%           | 95.94%        |
| MNIST          | 85.00%            | 83.00%        |

## 🧠 Methodology
The Baye-Tree builds a traditional decision tree and integrates Naive Bayes classifiers at specific nodes. Based on a confidence threshold, the model decides whether to split further or predict using Naive Bayes. This provides a flexible framework that adapts to data complexity and feature independence.
