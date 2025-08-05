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

## 📁 Repository Structure
qGAN-Classiq/

├── qGAN_challenge.ipynb       # 🧪 Main challenge notebook

├── qGAN.py                    # 🧠 qGAN class for hybrid training

├── setup.py                   # 📦 For installing qGAN as a module

├── README.md                  # 📄 You’re here!

└── LICENSE                    # ⚖️ MIT License

---

## ⚙️ Installing the `qGAN` Class as a Module

This project defines a custom `qGAN` class in `qGAN.py` to manage hybrid training between a quantum generator and classical discriminator. Installing it as a module makes it easy to reuse across notebooks and scripts.

### 🧪 Install Steps

1. **Clone the repository** (if you haven't already):
   
   ```bash
   
   git clone https://github.com/YOUR_USERNAME/Challenge-Notebooks.git
   
   cd Challenge-Notebooks/qGAN-Classiq


3. **(Recommended) Create a venv**
   
   python -m venv .venv
   
   source .venv/bin/activate  # On Windows use: .venv\Scripts\activate
   

6. **Install Required Dependencies**
   
   pip install classiq qiskit torch qiskit-aer


8. **Install qGAN Locally**
   
   pip install .


10. **Startup Notebook**
    
   jupyter notebook qGAN_challenge.ipynb
