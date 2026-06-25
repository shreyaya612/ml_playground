# Dataset, Features, Labels, Training Data and Testing Data

## Dataset

A dataset is a collection of data organized in rows and columns.

* Rows represent observations or records.
* Columns represent variables or attributes.

Datasets are used to train and evaluate Machine Learning models.

---

## Features

Features are the input variables used by a Machine Learning model to make predictions.

Features are commonly represented by X.

### Example

| Hours Studied | Attendance |
| ------------- | ---------- |
| 2             | 80         |
| 4             | 90         |

Features:

* Hours Studied
* Attendance

---

## Labels

Labels are the target values that the model is trying to predict.

Labels are commonly represented by y.

### Example

| Marks |
| ----- |
| 35    |
| 65    |

Label:

* Marks

---

## Features vs Labels

| Feature          | Label              |
| ---------------- | ------------------ |
| Input            | Output             |
| Given to Model   | Predicted by Model |
| Represented as X | Represented as y   |

---

## Training Data

Training data is the subset of the dataset used to train the Machine Learning model.

The model learns patterns and relationships from this data.

---

## Testing Data

Testing data is used to evaluate the performance of a trained model.

The model has never seen this data before.

Testing data helps determine how well the model generalizes to unseen examples.

---

## Train-Test Split

A dataset is commonly divided into:

* 80% Training Data
* 20% Testing Data

Other splits such as 70-30 and 90-10 are also used.

---

## Why Testing Data is Important

Without testing data, it is difficult to determine whether a model has learned meaningful patterns or simply memorized the training data.

Testing data provides an unbiased evaluation of model performance.

---

## Why Not Train on All Data?

Suppose:

Train = 100%
Test = 0%

The model may memorize answers instead of learning patterns.

Then you won't know whether it performs well on new data.

This leads to:

Overfitting

The model performs well on training data but poorly on new data.

---

## Key Takeaways

* A dataset contains rows and columns of data.
* Features are input variables (X).
* Labels are target variables (y).
* Training data is used to teach the model.
* Testing data is used to evaluate the model.
* Train-test split helps assess model generalization.
