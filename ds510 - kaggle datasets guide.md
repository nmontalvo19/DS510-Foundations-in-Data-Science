# DS-510 Mini-Guide: How to Download Kaggle Datasets

---

## Step 1: Create a Kaggle Account

1. Go to [https://www.kaggle.com/](https://www.kaggle.com/)
2. Click **Sign Up** and create a free account

---

## Step 2: Accept Kaggle Terms

1. Once logged in, click your profile icon → **Account**
2. Under **API**, click **Create New API Token** — this is needed if you want to use the Kaggle API in Jupyter or KNIME (optional — for advanced use)

---

## Step 3: Find a Dataset

1. Use **Datasets** tab on Kaggle to browse or search
2. You can search by topic (example: "COVID", "movies", "NBA", "education")
3. Click on a dataset to open it

---

## Step 4: Download the Dataset

1. On the dataset page, look for the **Download** button (usually top-right of the page)
2. Click **Download** — the file will download as a ZIP file

---

## Step 5: Extract and Use

1. Unzip the ZIP file on your computer
2. Place the dataset (usually `.csv`, `.xlsx`, or `.json`) in your project folder
3. Load into your Jupyter Notebook or KNIME workflow

---

## Example: Load CSV in Python

```python
import pandas as pd

# Load CSV file
df = pd.read_csv('your-dataset.csv')
df.head()
```

---

**End of Kaggle Mini-Guide**

