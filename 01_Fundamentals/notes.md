# Introduction to Machine Learning

## What is Artificial Intelligence (AI)?

Artificial Intelligence (AI) is the broader field of creating systems that can perform tasks that typically require human intelligence.

Examples:

* Voice assistants
* Self-driving cars
* Recommendation systems
* Chatbots

AI aims to make machines capable of reasoning, learning, problem-solving, and decision-making.

---

## What is Machine Learning (ML)?

Machine Learning is a subset of AI that enables computers to learn patterns from data and make predictions or decisions without being explicitly programmed for every task.

Instead of writing rules manually:

```text
If marks > 40 → Pass
Else → Fail
```

A Machine Learning model learns patterns automatically from historical data.

---

## Definition

Machine Learning is the study of algorithms that improve their performance on a task through experience (data).

In simple terms:

Input Data → Learn Patterns → Make Predictions

---

## What is Deep Learning (DL)?

Deep Learning is a subset of Machine Learning that uses neural networks with multiple layers to learn complex patterns from large amounts of data.

Examples:

* Image Recognition
* Speech Recognition
* Large Language Models (LLMs)
* Autonomous Vehicles

---

## Relationship Between AI, ML and DL

```text
Artificial Intelligence
│
└── Machine Learning
     │
     └── Deep Learning
```

AI is the broadest field.

Machine Learning is one approach used to achieve AI.

Deep Learning is a specialized area of Machine Learning.

---

## Why Machine Learning?

Traditional Programming:

Input + Rules → Output

Machine Learning:

Input + Output Data → Model Learns Rules

Reasons for using ML:

* Large volumes of data
* Complex patterns
* Automation
* Better predictions
* Continuous improvement

---

## Real-World Applications of Machine Learning

### Healthcare

* Disease prediction
* Medical image analysis

### Finance

* Fraud detection
* Credit scoring

### E-Commerce

* Product recommendations
* Customer segmentation

### Social Media

* Content recommendation
* Spam detection

### Transportation

* Route optimization
* Self-driving systems

---

## Key Takeaways

* AI is the broad field of intelligent systems.
* ML is a subset of AI that learns from data.
* DL is a subset of ML based on neural networks.
* Machine Learning helps discover patterns and make predictions.
* ML powers many modern applications used every day.

# Types of Machine Learning

Machine Learning can be categorized into three main types based on the availability of labeled data and the learning process.

## 1. Supervised Learning

In supervised learning, the model is trained using labeled data, meaning both the input features and the correct outputs are provided.

The objective is to learn a mapping between inputs and outputs so that predictions can be made on unseen data.

### Examples

* House Price Prediction
* Spam Email Detection
* Loan Approval Prediction
* Disease Prediction

### Types of Supervised Learning

#### Regression

Used when the output is a continuous numerical value.

Examples:

* Predicting salary
* Predicting house prices
* Predicting stock prices

#### Classification

Used when the output belongs to predefined categories.

Examples:

* Spam or Not Spam
* Approved or Rejected
* Positive or Negative Review

---

## 2. Unsupervised Learning

In unsupervised learning, the dataset contains only input features and no labels.

The algorithm identifies hidden patterns, structures, or relationships within the data.

### Examples

* Customer Segmentation
* Market Basket Analysis
* Anomaly Detection
* Pattern Discovery

### Common Algorithms

* K-Means Clustering
* Hierarchical Clustering
* Principal Component Analysis (PCA)

---

## 3. Reinforcement Learning

Reinforcement Learning is a learning paradigm where an agent interacts with an environment and learns through rewards and penalties.

The objective is to maximize cumulative rewards over time.

### Examples

* Self-Driving Cars
* Robotics
* Game Playing AI
* Resource Optimization

---

## Comparison

| Feature          | Supervised     | Unsupervised          | Reinforcement         |
| ---------------- | -------------- | --------------------- | --------------------- |
| Labels Available | Yes            | No                    | No                    |
| Learns From      | Input + Output | Input Only            | Rewards and Penalties |
| Goal             | Prediction     | Pattern Discovery     | Decision Making       |
| Example          | Spam Detection | Customer Segmentation | Self-Driving Cars     |

## Key Takeaways

* Supervised Learning uses labeled data.
* Unsupervised Learning uses unlabeled data.
* Reinforcement Learning learns through interaction and feedback.
* Regression and Classification are types of Supervised Learning.
* Clustering is a common Unsupervised Learning task.

