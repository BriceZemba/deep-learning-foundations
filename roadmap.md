**Deep Learning – Goodfellow, Bengio, Courville**.


## 1️⃣ Repository structure

```text
deep-learning-goodfellow/
│
├── README.md
├── roadmap.md
├── requirements.txt
│
├── notes/
│   ├── ch01_introduction.md
│   ├── ch02_linear_algebra.md
│   ├── ch03_probability.md
│   ├── ch04_numerical_computation.md
│   ├── ch05_machine_learning_basics.md
│   ├── ch06_deep_feedforward_networks.md
│   ├── ch07_regularization.md
│   ├── ch08_optimization.md
│   ├── ch09_convnets.md
│   ├── ch10_rnns.md
│   ├── ch11_practical_methodology.md
│   ├── ch12_applications.md
│   └── ch13_generative_models.md
│
├── math/
│   ├── linear_algebra.md
│   ├── probability_theory.md
│   ├── optimization.md
│   └── information_theory.md
│
├── code/
│   ├── fundamentals/
│   │   ├── backprop_from_scratch.py
│   │   ├── gradient_descent.py
│   │   └── logistic_regression.py
│   │
│   ├── neural_networks/
│   │   ├── mlp_pytorch.py
│   │   ├── regularization.py
│   │   └── batch_norm.py
│   │
│   ├── convnets/
│   │   ├── cnn_mnist.py
│   │   └── cnn_cifar10.py
│   │
│   ├── rnns/
│   │   ├── rnn_from_scratch.py
│   │   └── lstm_pytorch.py
│   │
│   └── generative_models/
│       ├── autoencoder.py
│       └── vae.py
│
├── experiments/
│   ├── optimization_study.md
│   ├── regularization_comparison.md
│   └── architecture_ablation.md
│
└── references/
    ├── papers.md
    ├── lecture_notes.md
    └── external_resources.md
```

---

## Repository Structure
- `notes/` – Chapter summaries and explanations
- `math/` – Mathematical prerequisites and derivations
- `code/` – Implementations (from scratch + PyTorch)
- `experiments/` – Empirical studies and ablation experiments

## Progress
- [ ] Chapter 1 – Introduction
- [ ] Chapter 2 – Linear Algebra
- [ ] Chapter 3 – Probability and Information Theory
- [ ] Chapter 4 – Numerical Computation
- [ ] Chapter 5 – Machine Learning Basics
- [ ] Chapter 6 – Deep Feedforward Networks
- [ ] Chapter 7 – Regularization
- [ ] Chapter 8 – Optimization
- [ ] Chapter 9 – Convolutional Networks
- [ ] Chapter 10 – Recurrent Networks
- [ ] Chapter 11 – Practical Methodology
- [ ] Chapter 12 – Applications
- [ ] Chapter 13 – Linear Factor Models
- [ ] Chapter 14–20 – Advanced Topics (Selective)

```

---


### Mathematical foundations

* Ch. 1: Overview of Deep Learning
* Ch. 2: Linear Algebra → `math/linear_algebra.md`
* Ch. 3: Probability & Information Theory
* Ch. 4: Numerical Computation

Goal: full mathematical readiness

---

### Core ML concepts

* Ch. 5: Machine Learning Basics
* Implement:

  * Logistic regression
  * Gradient descent
  * Loss functions

📁 `code/fundamentals/`

---

### Deep feedforward networks

* Ch. 6: Deep Feedforward Networks
* Ch. 7: Regularization
* Implement:

  * MLP from scratch
  * Dropout, L2, batch normalization

📁 `neural_networks/`

---

### Optimization

* Ch. 8: Optimization for Deep Learning
* Experiments:

  * SGD vs Adam vs RMSProp
  * Learning rate schedules

📁 `experiments/optimization_study.md`

---

### Specialized architectures

* Ch. 9: Convolutional Networks
* Ch. 10: Recurrent Networks
* Implement:

  * CNN on CIFAR-10
  * RNN / LSTM sequence modeling

📁 `convnets/`, `rnns/`

---

### Generative models & methodology

* Ch. 11: Practical Methodology
* Ch. 13–14: Autoencoders, VAEs
* Final experiments + documentation

📁 `generative_models/`

---
