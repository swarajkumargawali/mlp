# ML Practical Code Library

A generic exam-practical code workflow.

## Usage

```python
from ml_practical import gc

print(gc("logistic regression"))
print(gc("decision tree"))
print(gc("linear regression"))
print(gc("svm"))
print(gc("knn"))
print(gc("k means"))
```

The generated templates do not contain a specific dataset or target column.

Dataset-specific places use a single blank space:

```python
df = pd.read_csv(" ")

X = df.drop(" ", axis=1)
y = df[" "]
```

Fill those spaces according to the dataset given in the practical exam.

## Available models

- decision tree classifier
- logistic regression
- linear regression
- svm
- knn
- k-means
