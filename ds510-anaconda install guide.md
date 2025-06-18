# DS-510 How to Install and Use Anaconda

---

## What is Anaconda?

Anaconda is an easy way to install Python, Jupyter Notebooks, and many data science libraries — all in one package.

---

## Step 1: Download Anaconda

1. Go to: [https://www.anaconda.com/products/distribution](https://www.anaconda.com/products/distribution)
2. Download the **Individual Edition** (free)
3. Choose the version for your operating system (Windows, Mac, or Linux)

---

## Step 2: Install Anaconda

1. Run the installer
2. Use the **default settings** (recommended)
3. Let the installer complete (may take a few minutes)

---

## Step 3: Launch Jupyter Notebook

1. Open **Anaconda Navigator** from your Start Menu (Windows) or Applications (Mac)
2. Click **Launch** under Jupyter Notebook
3. A browser window will open — this is your Jupyter environment!

---

## Step 4: Start Your DS-510 Projects

1. Create a folder for your project:
   - Example: `DS510_Project1`
2. Save your notebooks inside this folder (`.ipynb` files)
3. Load datasets (CSV, XLSX) into the same folder

---

## Example: Load Data in Jupyter

```python
import pandas as pd

df = pd.read_csv('your-dataset.csv')
df.head()
```

---

## Notes

✅ You do NOT need to install Python separately — Anaconda includes it. ✅ You can use Jupyter Notebook OR JupyterLab (both are fine). 
---




**End of Anaconda Mini-Guide**

