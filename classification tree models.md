# Classification Trees in Python

A classification tree is a decision tree used to predict categorical outcomes (e.g., Yes/No, Pass/Fail).

- Splits data into branches based on feature values.

- Each split reduces impurity (e.g., Gini Index, Entropy).

- Ends at leaf nodes with predicted class labels.

---

Key library: `scikit-learn` (`DecisionTreeClassifier`).

---

```python
from sklearn.tree import DecisionTreeClassifier
from sklearn.datasets import load_iris
from sklearn.model_selection import train_test_split
```
