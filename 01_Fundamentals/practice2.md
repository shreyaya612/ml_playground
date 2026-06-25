# Practice Questions: Dataset, Features, Labels, Training Data and Testing Data

## Concept Questions

1. What is a dataset?
2. What are features in Machine Learning?
3. What are labels?
4. Differentiate between features and labels.
5. What is training data?
6. What is testing data?
7. Why do we split datasets into training and testing sets?
8. What is the purpose of a train-test split?
9. What happens if we train on 100% of the data?
10. Why is testing data important?

---

## Interview Questions

### Q1. What are features and labels?

Ideal Answer:

Features are the input variables provided to a model, while labels are the target outputs the model is trained to predict.

---

### Q2. Why do we need testing data?

Ideal Answer:

Testing data is used to evaluate how well a trained model performs on unseen data. It helps determine whether the model can generalize beyond the training set.

---

### Q3. What is the difference between training and testing data?

Ideal Answer:

Training data is used to learn patterns and relationships, whereas testing data is used to evaluate the model after training.

---

### Q4. Why can't we train on the entire dataset?

Ideal Answer:

Training on the entire dataset leaves no unseen data for evaluation. As a result, we cannot determine whether the model has learned meaningful patterns or merely memorized the training data.

---

## Common Interview Mistakes

❌ Features are the outputs.

✅ Features are inputs.

---

❌ Testing data is used to train the model.

✅ Testing data is only used for evaluation.

---

❌ Labels are always numerical.

✅ Labels can be numerical (regression) or categorical (classification).

---

## Quick Interview Tip

Whenever you see a dataset:

Step 1: Identify the target variable.

Step 2: Everything else is usually a feature.


