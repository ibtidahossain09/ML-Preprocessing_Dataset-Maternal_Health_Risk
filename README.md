# Maternal Health Risk Dataset – EDA & Preprocessing

## 📌 Objective

This project performs Exploratory Data Analysis (EDA) and preprocessing on the **Maternal Health Risk Dataset** to better understand the data and prepare it for future model development (classification tasks).

## 📁 Dataset

The dataset includes the following features:

- `Age`: Age of the patient
- `SystolicBP`: Systolic Blood Pressure
- `DiastolicBP`: Diastolic Blood Pressure
- `BS`: Blood Sugar level
- `BodyTemp`: Body Temperature
- `HeartRate`: Heart Rate
- `RiskLevel`: Target label with categories such as low, mid, high

📍**File Path:**  
`/content/drive/MyDrive/pre processing/Maternal_Health_Risk.csv`

---

## 🔍 Steps Covered

### ✅ 1. Exploratory Data Analysis (EDA)
- Displayed top records using `df.head()`
- Plotted pairwise relationships with `sns.pairplot()`
- Visualized target class distribution with bar plot

### ✅ 2. Preprocessing
- **Min-Max Normalization** using `MinMaxScaler`
- **Z-Score Normalization** using `StandardScaler`
- Preserved original and transformed versions for analysis

---

## 📊 Sample Visualizations

- **Pairplot of original features**
- **Normalized feature pairplots**
- **Risk level distribution bar chart**

