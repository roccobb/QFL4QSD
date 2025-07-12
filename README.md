# QFL4QSD

This repository contains the code and experiments for the paper **"Quantum Federated Learning for Noisy and Imbalanced State Discrimination"** submitted to the **3rd International Workshop on AI for Quantum and Quantum for AI (AIQxQIA 2025)**.

The work explores how **Quantum Federated Learning (QFL)** can be applied to mitigate the effects of data imbalance and depolarizing noise in the task of **Quantum State Discrimination (QSD)**. This repository provides the Jupyter notebooks used to generate the experiments and plots included in the paper.


## Repository Structure
```
QFL4QSD/
├── nb/
│   ├── Imbalance.ipynb   # Experiments on imbalanced datasets
│   └── DepoNoise.ipynb   # Experiments on imbalanced + noisy datasets
├── figs/                 # Output plots used in the paper
├── requirements.txt      # Python dependencies
└── README.md             # This file
```

## Running Experiments with Jupyter Lab

To run the experiments using **Jupyter Lab**, follow these steps:
1. **Create a virtual environment**
```bash
   python3 -m venv .venv
```
2. **Activate the virtual environment**
```bash
   source .venv/bin/activate
```
3. **Install the required dependencies**
```bash
pip install -r requirements.txt
```
4. **Install the virtual environment as a Jupyter kernel**
```bash
python -m ipykernel install --user --name=qfl4qsd
```
5. **Launch Jupyter Lab and select the qfl4qsd kernel**
```bash
jupyter lab
```
