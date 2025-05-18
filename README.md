# 🌳🧠 Baye-Tree: Integrating Naive Bayes into Decision Trees

This hybrid classification model combines the interpretability of **Decision Trees** with the probabilistic efficiency of **Naive Bayes**. By embedding Naive Bayes at intermediate and leaf nodes of a decision tree, the Baye-Tree aims to mitigate overfitting and improve generalization on structured data.

## 📄 Paper
Read the full paper here: [`baye-tree_paper.pdf`](paper/baye-tree_paper.pdf)

## 📊 Datasets Used
- [Contraceptive Method Choice Dataset (UCI)](https://doi.org/10.24432/C59W2D)
- Titanic (Seaborn)
- Mushroom Dataset (UCI)
- MNIST (Scikit-learn)
- Buys Computer (internal demo)
  
## 🧠 Methodology
The Baye-Tree builds a traditional decision tree and integrates Naive Bayes classifiers at specific nodes. Based on a confidence threshold, the model decides whether to split further or predict using Naive Bayes. This provides a flexible framework that adapts to data complexity and feature independence.
