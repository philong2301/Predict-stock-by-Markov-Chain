# 📈 Stock Price Modeling using Markov Chains

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Statistics](https://img.shields.io/badge/Field-Stochastic%20Processes-green)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen)

---

## 📌 Overview

This project applies a **Markov Chain model** to analyze and model stock price movements.

The idea is to represent stock price changes as a sequence of **states** and study how the system transitions from one state to another over time. This allows us to understand the probabilistic behavior of stock price movements.

---

## 🎯 Objectives

* Represent stock price movements as discrete states
* Estimate **transition probabilities** between states
* Analyze patterns in stock price changes
* Simulate future state sequences based on probabilities

---

## 🧠 Methodology

### 1. Data Preparation

* Load historical stock price data
* Compute price changes / returns

---

### 2. State Definition

Price movements are converted into discrete states, for example:

* 📈 Up (price increase)
* 📉 Down (price decrease)
* ➡️ Stable (little or no change)

---

### 3. Transition Matrix

A **transition matrix** is constructed by counting how often the system moves from one state to another.

[
P_{ij} = P(X_{t+1} = j \mid X_t = i)
]

This matrix describes the probability of moving between different states.

---

### 4. Simulation

Using the transition matrix, the model can:

* Simulate future sequences of states
* Explore possible stock movement patterns

---

## ⚙️ Implementation

* Language: **Python**
* Main libraries:

  * `numpy`
  * `pandas`
  * `matplotlib`

Steps implemented in the notebook:

1. Load and preprocess data
2. Convert data into states
3. Build transition matrix
4. Simulate future states

---

## 📂 Project Structure

```id="2d9h1k"
project/
├── Stochasting_Project.ipynb
└── README.md
```

---

## 📊 Results

* Transition probabilities show how likely the market is to:

  * Continue in the same direction
  * Reverse direction
* Simulations illustrate possible future behaviors of stock movements

---

## ⚠️ Limitations

* Assumes the **Markov property** (future depends only on current state)
* Uses simplified state definitions
* Does not include external factors (news, macroeconomics)

---

## 💡 What I Learned

* How to model time series using **Markov Chains**
* How to estimate transition probabilities from data
* How to simulate stochastic processes
* Understanding probabilistic behavior in financial data

---

## 👨‍💻 Author

**Tran Quoc Bao**
Bachelor of Applied Statistics

---

## ⭐ Final Note

This project demonstrates how **stochastic processes** can be applied to financial data to better understand uncertainty and probabilistic behavior in stock price movements.

---
