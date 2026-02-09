# QFL4QSD

This repository contains code and experiments related to **Quantum Federated Learning (QFL) for Quantum State Discrimination (QSD)**.

The project originated from the paper  
**"Quantum Federated Learning for Noisy and Imbalanced State Discrimination"** (https://ceur-ws.org/Vol-4153/paper5.pdf),  
presented at the **3rd International Workshop on AI for Quantum and Quantum for AI (AIQxQIA 2025)**,  
and has since been **extended with additional experiments and analyses** that form the basis of a
journal article currently under submission to **Quantum Machine Intelligence**.

The repository is organized to clearly separate the **original workshop experiments** from the **new experimental results** introduced in the journal version.


## Repository Structure

```QFL4QSD/
├── AIQxQIA/ # Material related to the AIQxQIA workshop paper
│ ├── nb/ # Jupyter notebooks for workshop experiments
│ │ ├── Imbalance.ipynb
│ │ └── DepoNoise.ipynb
│ └── figs/ # Figures used in the workshop paper
│
├── nb/ # Jupyter notebooks for journal-paper experiments
│ ├── SETUP_*.ipynb # Imbalance experiments for different setups
│ ├── Noise Setups # Noise-related experiments
│ ├── Quantum Computer # Experiments on real quantum computer
│ └── Scaled Problems # Scaled-up experiments
│
├── figs/ # Figures generated for the journal article
├── requirements.txt # Python dependencies
└── README.md # This file
```


## Running Experiments with Jupyter Lab To run the experiments using **Jupyter Lab**, follow these steps: 
1. **Create a virtual environment**
```bash
python3 -m venv .venv
```
3. **Activate the virtual environment**
```bash
source .venv/bin/activate
```
5. **Install the required dependencies**
```bash
pip install -r requirements.txt
```
6. **Install the virtual environment as a Jupyter kernel**
```bash
python -m ipykernel install --user --name=qfl4qsd
```
7. **Launch Jupyter Lab and select the qfl4qsd kernel**
```bash
jupyter lab
```
