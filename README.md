# 🏆 Visualizing the History of Nobel Prize Winners

**Executive Summary:**
In this Exploratory Data Analysis (EDA) project, I investigated the historical dataset of Nobel Prize winners from 1901 to 2023. By leveraging data manipulation and visualization techniques, I analyzed demographic trends, geographic distributions, and the evolution of gender representation across different prize categories over the last century.

---

## 1. The Analytical Context

The Nobel Prize has been among the most prestigious international awards since 1901. Analyzing its historical data provides a unique window into the evolution of global scientific research, geopolitical shifts, and societal changes in academia. 

**Objective:** Perform a comprehensive EDA to uncover historical patterns and answer key questions regarding:
* The historical gender gap and recent breakthroughs in female representation.
* The geographic distribution of laureates and the rise of US dominance post-WWII.
* Trends across different prize categories grouped by decades.

## 2. Data & Methodology

The dataset contains records of all prize winners from the outset of the awards. To extract meaningful insights, I implemented the following analytical pipeline:

* **Data Integrity & Imputation:** Investigated null values in demographic columns, identifying them as institutional winners (e.g., the Red Cross, UNHCR) rather than missing individual data.
* **Feature Engineering:** Created a `decade` feature to group continuous temporal data, allowing for ratio calculations and macro-trend analysis over time.
* **Aggregations & Ratios:** Built nested data groupings to calculate the exact percentage of US-born winners per decade and to isolate the top category/decade combinations with the highest proportion of female laureates.

## 3. Tech Stack

To clean, manipulate, and visualize the data, I used standard Python data science libraries:

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge)
![Seaborn](https://img.shields.io/badge/Seaborn-3776AB?style=for-the-badge)

> 💡 **Detailed visualizations (including bar charts, line graphs, and demographic plots) and final analytical takeaways are documented directly inside the Jupyter Notebook.**
