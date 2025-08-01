# Custom-Decision-Trees-Weighted-Ensemble-Nursery-Dataset-
Interpretable multi-class classifier for nursery application prioritization, built **from scratch in Python/NumPy**. Implements **Decision Trees** with both **Gini Index** and **Information Gain** split criteria and combines them via a simple **weighted-majority ensemble**.

## What’s inside
- **Data:** Nursery dataset — **12,960 rows**, **5 target classes**, all **categorical** features.
- **Algorithms:** ID3/CART-style tree induction (best-split search, stopping rules), prediction by leaf majority.
- **Ensemble:** Weighted vote of Gini + InfoGain trees to improve robustness on minority classes.
- **Evaluation:** **65/35 train–test split**, accuracy, per-class precision/recall, and **confusion matrices**; plots for error analysis.

## Results (Test)
- **Gini Tree:** **97.88%** accuracy  
- **Information Gain Tree:** **97.82%** accuracy  
- **Weighted Ensemble:** **97.88%** accuracy  
Includes class-wise confusion matrices for interpretability.
