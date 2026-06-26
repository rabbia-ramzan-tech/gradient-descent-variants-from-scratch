# 🚀 Gradient Descent Variants from Scratch Using NumPy

## 📌 Project Overview

Gradient Descent is one of the most fundamental optimization algorithms in Machine Learning. This project implements three popular Gradient Descent variants from scratch using **NumPy** and compares their convergence behavior under different learning rates.

The objective is to understand how optimization algorithms update model parameters and how the choice of learning rate affects training stability and convergence speed.

---

## 🎯 Objectives

- Implement Batch Gradient Descent (BGD) from scratch.
- Implement Stochastic Gradient Descent (SGD) from scratch.
- Implement Mini-Batch Gradient Descent (MBGD) from scratch.
- Compare the performance of each optimizer.
- Analyze the effect of different learning rates on convergence.
- Visualize training loss using learning curves.

---

## 📚 Algorithms Implemented

### 1. Batch Gradient Descent (BGD)
Uses the entire dataset to compute gradients before updating the model parameters.

**Characteristics**
- Stable convergence
- Computationally expensive for large datasets
- Smooth learning curves

---

### 2. Stochastic Gradient Descent (SGD)

Updates the model parameters after processing each training example.

**Characteristics**
- Faster updates
- Noisy convergence
- Can escape shallow local minima

---

### 3. Mini-Batch Gradient Descent (MBGD)

Updates the model parameters after processing a small batch of training examples.

**Characteristics**
- Faster than Batch Gradient Descent
- More stable than SGD
- Widely used in Deep Learning

---

## ⚙️ Technologies Used

- Python
- NumPy
- Matplotlib
- Jupyter Notebook

---

## 📁 Project Structure

```
gradient-descent-variants-from-scratch/

│── gradient_descent_from_scratch.ipynb
│── README.md
│── requirements.txt
│── LICENSE
│── .gitignore


├── results and images/
│     gradient_descent_from_scratch_results.pdf
```

---

## 📊 Learning Rates Tested

| Learning Rate | Expected Behavior |
|---------------|-------------------|
| 0.001 | Very slow convergence |
| 0.01 | Stable convergence |
| 0.05 | Fast and stable convergence |
| 0.1 | Fast convergence with slight oscillations |
| 0.5 | Unstable convergence due to overshooting |

---

## 📈 Experimental Results

The project compares the optimization algorithms by visualizing their learning curves.

The following aspects are analyzed:

- Training Loss
- Convergence Speed
- Stability
- Effect of Learning Rate
- Optimization Efficiency

> *(Add screenshots of your graphs inside the `images` folder and display them here.)*

Example:

```markdown
### Learning Rate Comparison

![Learning Rate Comparison](images/learning_rate_comparison.png)
```

---

## 🔍 Key Findings

- Batch Gradient Descent produces smooth and stable convergence.
- Stochastic Gradient Descent converges faster but exhibits noisy updates.
- Mini-Batch Gradient Descent provides a balance between computational efficiency and convergence stability.
- Moderate learning rates generally produce the best optimization performance.
- Very large learning rates can cause oscillations and prevent convergence.

---

## ▶️ How to Run

### Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/gradient-descent-variants-from-scratch.git
```

### Navigate to the project directory

```bash
cd gradient-descent-variants-from-scratch
```

### Install dependencies

```bash
pip install -r requirements.txt
```

### Launch Jupyter Notebook

```bash
jupyter notebook
```

Open

```
gradient_descent_variants.ipynb
```

and run all cells.

---

## 📖 Concepts Covered

- Gradient Descent
- Optimization Algorithms
- Machine Learning Fundamentals
- Learning Rate Tuning
- NumPy Programming
- Loss Functions
- Parameter Optimization
- Data Visualization

---

## 🚀 Future Improvements

- Implement Momentum Gradient Descent
- Implement RMSProp
- Implement Adam Optimizer
- Compare execution times
- Apply the optimizers to real-world datasets
- Extend the implementation to Logistic Regression

---

## 💡 What I Learned

Through this project, I gained practical experience in implementing optimization algorithms from scratch and analyzing their behavior under different hyperparameter settings. This helped strengthen my understanding of how machine learning models learn through iterative parameter updates and why optimizer selection is crucial for efficient training.

---

## 👩‍💻 Author

**Rabbia Ramzan**

---

## ⭐ If you found this project useful, consider giving it a star!