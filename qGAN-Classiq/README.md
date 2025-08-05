# 🧠 Quantum GAN Challenge: QFT State Preparation with Classiq + Qiskit

Welcome to the Quantum Generative Adversarial Network (qGAN) Challenge!  
This beginner-to-intermediate level project walks you through building a hybrid quantum-classical GAN to generate **Quantum Fourier Transform (QFT)** states using the [Classiq](https://classiq.io) platform and [Qiskit](https://qiskit.org).

## 📚 What You'll Learn

By completing this challenge notebook, you will:

- Understand the structure of qGANs and their hybrid quantum-classical training loop
- Design a variational quantum ansatz suitable for QFT-like state generation
- Compile and export quantum circuits using Classiq’s synthesizer
- Build a classical discriminator in PyTorch
- Train and evaluate a qGAN with custom quantum noise and sampling
- Explore exporting quantum circuits to QASM and running them on IBM Quantum devices

---

## 📦 Requirements

Make sure to install the following Python packages:

```bash
pip install classiq qiskit torch qiskit-aer
