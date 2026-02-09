
# AIG 230 – Lab 05 Setup Guide  
## Sequence Models with PyTorch (RNNs)

This document contains **only the required setup steps** for Lab 05.  
Follow the steps **in order**. Do not skip steps.

---

## 1. Navigate to the Lab Folder

Open **Git Bash** and navigate to your Lab 05 directory:

```bash
cd "~/Documents/Seneca Polytechnic/AIG230 - NLP/labs/aig230-lab05"
```

Confirm:

```bash
pwd
```

You should see a path ending in `aig230-lab05`.

---

## 2. Create a Virtual Environment

Create a dedicated environment for Lab 05:

```bash
python -m venv aig230-env
```

This isolates PyTorch and neural-model dependencies.

---

## 3. Activate the Virtual Environment

```bash
source "aig230-env/Scripts/activate"
```

Your prompt must show:

```text
(aig230-env)
```

If not, stop and fix before continuing.

---

## 4. Upgrade pip

```bash
pip install --upgrade pip
```

---

## 5. Install Required Packages

Install dependencies for sequence models and embeddings:

### Option A: Install from requirements file (recommended)

```bash
pip install -r requirements.txt
```

### Option B: Manual install

```bash
pip install jupyter ipykernel numpy pandas matplotlib scikit-learn nltk torch torchvision torchaudio
```

These packages are used for:

- **PyTorch** – RNNs and sequence models  
- **NLTK** – tokenization  
- **NumPy / Pandas** – data handling  
- **Matplotlib** – loss visualization  
- **Jupyter** – notebook execution  

---

## 6. Register the Environment as a Jupyter Kernel

```bash
python -m ipykernel install --user   --name aig230-env   --display-name "Python (AIG230)"
```

This step is required once per environment.

---

## 7. Launch Jupyter Notebook

From the lab folder:

```bash
jupyter notebook
```

In the browser:

1. Open `AIG230_Week5_Lab_Sequence_Models.ipynb`
2. Kernel (top right) must be **Python (AIG230)**

---

## 8. Expected Folder Structure

Before starting the lab, confirm:

```
aig230-lab05/
├─ aig230-env/
├─ AIG230_Week5_Lab_Sequence_Models.ipynb
├─ README.md
├─ SETUP.md
├─ requirements.txt
```

Do not rename files or folders.

---

## 9. Common Issues

### PyTorch not detected
- Confirm environment is activated
- Restart Jupyter after kernel registration

### CUDA not available
- GPU is **not required** for this lab
- CPU execution is expected and sufficient

### NLTK resource errors
Run inside the notebook if prompted:

```python
import nltk
nltk.download("punkt")
```

---

## 10. Before Submission Checklist

Before submitting:

- Notebook runs top to bottom
- All checkpoint questions answered
- Kernel is **Python (AIG230)**
- No extra packages installed beyond instructions
- Changes committed and pushed to GitHub

---

## Key Reminder

This lab introduces **sequence modeling**.  
Understanding tensors, shapes, and time steps is essential for upcoming labs on attention and transformers.

---
