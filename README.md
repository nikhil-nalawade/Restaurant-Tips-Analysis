# Restaurant Tipping Behavior Analysis 🍽️
### Exploratory Data Analysis (EDA) using Python & Seaborn

This project focuses on identifying patterns in restaurant tipping behavior using the classic 'tips' dataset. As a Computer Engineering student (Batch of 2027), I developed this project to bridge the gap between theoretical data science concepts and practical implementation.

---

## 🎯 Project Objective
The goal of this analysis was to answer three key business questions:
1. Which day of the week is most profitable for the restaurant?
2. Do demographic factors like Gender or Smoking status significantly affect tipping amounts?
3. Is there a strong linear correlation between the total bill and the tip provided?

## 🛠️ Tech Stack
* **Environment:** Anaconda / Jupyter Notebook
* **Data Manipulation:** Pandas, NumPy
* **Data Visualization:** Seaborn, Matplotlib
* **Version Control:** Git & GitHub



## 📊 Key Findings (The "Answers")
After performing the EDA and visualizing the distributions, the following insights were discovered:

* **The Sunday Premium:** Sunday consistently shows the highest average `total_bill`. This suggests that weekends (specifically Sundays) are the best times for maximizing revenue per table.
* **Gender Consistency:** The **Violin Plots** revealed that tipping behavior is remarkably similar across genders. However, male customers showed a wider range of bill amounts (more outliers) compared to female customers.
* **Linear Correlation:** The **Regression Plot** (`sns.regplot`) confirmed a strong positive correlation. As the bill increases, the tip increases linearly, generally staying within the 10-20% range.
* **Feature Engineering:** I utilized `np.where` to categorize "Generous Tippers" (those who tip > 15%), providing a clearer segment for customer loyalty analysis.
