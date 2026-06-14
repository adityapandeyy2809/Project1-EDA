# Soft Nexis Internship Project1-EDA
**Written Summary: Some Interesting Findings from the EDA**

During the Exploratory Data Analysis (EDA) of the Titanic dataset, several meaningful patterns were discovered regarding passenger survival.

The first and most significant finding was the impact of **gender on survival**. Female passengers had a much higher survival rate than male passengers. Approximately 74% of females survived, while only about 19% of males survived. This suggests that women were given priority during the evacuation process, supporting the historical “women and children first” policy followed during the disaster.

The second important finding was the relationship between **passenger class and survival**. Passengers traveling in First Class had the highest survival rate (around 63%), followed by Second Class passengers (about 47%), while Third Class passengers had the lowest survival rate (about 24%). This indicates that socioeconomic status and cabin location may have influenced access to lifeboats and emergency assistance.

The third interesting observation involved **family size and traveling alone**. Passengers who traveled with family members generally had a better chance of survival than those traveling alone. The survival rate for passengers with family was approximately 51%, compared to around 30% for passengers traveling alone. This suggests that family groups may have been better able to support one another during the emergency or were more likely to receive assistance.

Overall, the EDA revealed that gender, passenger class, and family status were among the strongest factors influencing survival on the Titanic. These findings provide valuable insights into the social and situational factors that affected passenger outcomes during the tragedy.

# ⚙️ Environment Setup

Before running this project, make sure you have Python and the required libraries installed.

## 1. Install Python

Download and install **Python 3.10 or later** from the official Python website:

https://www.python.org/downloads/

During installation, make sure to check:

✅ **Add Python to PATH**

This step is important because it allows Python commands to work from the terminal.

---

## 2. Install Required Libraries

Open **Command Prompt** (Windows) or **Terminal** (Mac/Linux) and run:

```bash
pip install jupyter pandas matplotlib seaborn openpyxl
```

This installs:

* **Jupyter Notebook** – Interactive coding environment
* **Pandas** – Data manipulation and analysis
* **Matplotlib** – Data visualization
* **Seaborn** – Statistical plotting
* **OpenPyXL** – Excel file support

Wait until you see the message:

```text
Successfully installed
```

---

## 3. Launch Jupyter Notebook

Start Jupyter Notebook by running:

```bash
jupyter notebook
```

A browser tab will open automatically showing the Jupyter Notebook dashboard.

To create a new notebook:

1. Click **New**
2. Select **Python 3 (ipykernel)**

You can now write Python code in notebook cells and execute them using:

```text
Shift + Enter
```

---

## 4. Load the Titanic Dataset

This project uses the famous **Titanic Dataset**, which contains passenger information from the RMS Titanic disaster.

You can either download the dataset from Kaggle:

https://www.kaggle.com/datasets/brendan45774/test-file

Or load it directly from the internet using the following code:

```python
import pandas as pd

# Load dataset directly from URL
url = "https://raw.githubusercontent.com/datasciencedojo/datasets/master/titanic.csv"

df = pd.read_csv(url)

print("Dataset loaded successfully!")
print("Shape:", df.shape)
```

Expected output:

```text
Dataset loaded successfully!
Shape: (891, 12)
```

You are now ready to begin the Exploratory Data Analysis (EDA) and visualization tasks.
