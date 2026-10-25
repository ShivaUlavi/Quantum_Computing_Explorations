# Quantum Computing Explorations 🌌

Welcome! This repository serves as my active codebase and playground as I transition my background in Deep Learning into the field of **Quantum Machine Learning (QML)** and **Quantum Information Processing**. 

Rather than focusing on passive learning, I am actively building, testing, and optimizing hybrid quantum-classical algorithms using Python's leading quantum computing frameworks.

---

## 🚀 Current Technical Focus
I am currently upskilling in open-source quantum ecosystems to understand how quantum mechanics can accelerate or alter traditional optimization frameworks:
* **PennyLane:** Building differentiable quantum circuits and hybrid quantum neural networks (HQNNs).
* **Qiskit:** Implementing basic quantum circuits, gate operations, and variational algorithms.
* **PyTorch Integration:** Connecting quantum circuit nodes (`QNodes`) directly into classical neural network layers to track gradient flow via backpropagation.

---

## 🛠️ Repository Contents

### 1. Variational Quantum Classifier (VQC)
* **File:** `01_quantum_classifier.ipynb`
* **Frameworks:** PennyLane + PyTorch
* **Description:** A hybrid model that takes a non-linear classical dataset (SciKit-Learn Moons), projects it into a 2-qubit Hilbert space via **Angle Embedding**, applies a parameterized **Strongly Entangling Layers Ansatz**, and uses a PyTorch Adam optimizer to draw non-linear decision boundaries.
* **Key Learning Objective:** Understanding parameter initialization in variational circuits and mitigating barren plateaus.

---

## 📈 Next Steps & Implementation Pipeline
- [ ] Add a visual decision-boundary mapping script using `matplotlib` to track how the quantum ansatz shifts during training epochs.
- [ ] Implement a **Quantum Support Vector Machine (QSVM)** utilizing quantum kernel estimation.
- [ ] Explore **Tensor Networks** and matrix product states (MPS) for simulating large-scale quantum systems on classical hardware.

---

## 🎓 About Me
* **Background:** Master of Science (MS) in Business Analytics with a 3.7 GPA from Bentley University, USA & Bachelors of Engineering in Computer Science with 8.25 CGPA.
* **Foundational Work:** Deep learning architectures, algorithm implementation from scratch, and generative AI pipelines. (See my other repositories for core deep learning and NLP implementations).
* **Objective:** Actively preparing for advanced doctoral-level research in Quantum Computing, Tensor Networks, and Machine Learning.
