# What Makes a Mobile App Successful on Google Play?
This project explores which factors are associated with app success on the Google Play Store using exploratory data analysis (EDA).

## 📊 Overview
With millions of apps competing for attention, understanding what drives app success is important for developers and product teams. This analysis focuses on identifying patterns between app characteristics and install counts.

The main goal is to answer:
** What app attributes are associated with higher install counts on Google Play? **

_________________________________________________________________
## 📁 Dataset

- Source: Kaggle (Google Play Store Apps dataset)
- Number of apps: 10,841
- Features include:
  - App category
  - Installs
  - Ratings
  - Reviews
  - Price
  - Content rating
_________________________________________________________________
## 🧹 Data Cleaning

- Removed commas and "+" symbols from install counts
- Converted install values to numeric format
- Handled invalid/malformed values by converting them to missing (NaN)
- Excluded invalid entries from install-based analysis
_________________________________________________________________
## 📈 Analysis Performed

- Distribution of app install counts (log scale)
- Relationship between app ratings and installs
- Comparison of install counts across app categories
_________________________________________________________________
## 🔍 Key Insights

- App installs are highly skewed — a small number of apps dominate downloads
- Higher ratings are associated with higher installs, but not guaranteed success
- Certain categories (e.g., Photography, Entertainment) tend to perform better
_________________________________________________________________
## ⚠️ Limitations

- Install counts are ranges, not exact values
- Missing ratings may introduce bias
- No data on marketing, revenue, or retention
- The dataset represents a snapshot in time
_________________________________________________________________
## 🛠️ Tools Used

- Python
- Pandas
- Matplotlib
-  NumPy (for numerical operations)
_________________________________________________________________
## 📂 Files

- `m1.ipynb` → Main analysis notebook  
- `google_play_store_dataset.csv` → Dataset used
_________________________________________________________________
## 🔗 Medium Article

Read the full analysis here:  
👉 <INSERT YOUR MEDIUM LINK HERE>
_________________________________________________________________
This project demonstrates how exploratory data analysis can be used to uncover meaningful patterns in real-world datasets and support data-driven decision making.
---
## 👤 Author
Shazab Chaudhry  
University of Maryland
INST414 - Data Science Techniques
Date: March 17, 2026
