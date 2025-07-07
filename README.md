# QFL4QSD

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
