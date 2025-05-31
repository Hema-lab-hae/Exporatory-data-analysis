📁 Project Structure

titanic-eda/
│
├── data/
│   └── train.csv                # Raw Titanic dataset
│
├── notebooks/
│   └── titanic_eda.ipynb       # vscode notebook for EDA
│
├── images/
│   └── *.png                   # Saved graphs and visualizations
│
├── requirements.txt            # Python dependencies
└── README.md                   # Project documentation


---

📊 Dataset Description

The Titanic dataset provides information about passengers aboard the Titanic, including:

Survived – Target variable (0 = No, 1 = Yes)

Pclass – Ticket class

Sex, Age, SibSp, Parch

Fare, Embarked, Cabin, Ticket, Name



---

🔍 EDA Highlights

Some key questions I explored:

💡 What factors contributed to survival?

📈 Does gender or passenger class affect survival rate?

📊 What is the age distribution of survivors vs non-survivors?

🛳️ Where did passengers embark from, and how does it relate to survival?



---

📌 Key Insights

Women had a higher survival rate than men

1st class passengers were more likely to survive than 3rd class

Children aged 0–10 had a relatively higher chance of survival

Passengers who embarked from Cherbourg (C) had higher survival rates



---

🧰 Tools & Libraries

Python

Pandas

NumPy

Matplotlib

Seaborn



---

▶️ How to Run

1. Install requirements:



pip install -r requirements.txt

2. Open the vs code terminal:



titanic_eda.ipynb


---

📚 What I Learned

How to perform descriptive statistics and summary analysis

How to create and interpret visualizations using Seaborn and Matplotlib

How to explore relationships between categorical and numerical features

How to generate data-driven insights from raw data



---

📦 requirements.txt

pandas
numpy
matplotlib
seaborn
# Exporatory-data-analysis