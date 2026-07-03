# Bellabeat Smart Device Usage Analysis

##  Project Overview
This repository contains a case study analysing smart device fitness data to unlock new growth opportunities for **Bellabeat**, a high-tech manufacturer of health-focused products for women. 

This project is completed as part of the **Google Data Analytics Professional Certificate** capstone requirement.

---

##  Business Task
Analyse public Fitbit consumer datasets to identify trends in smart device usage and understand how these behavioural patterns apply to Bellabeat’s product ecosystem. The final objective is to deliver high-level, data-driven marketing strategy recommendations to Bellabeat’s executive team.

### Core Business Questions:
1. What trends exist in smart device usage?
2. How do these trends apply to Bellabeat customers?
3. How can Bellabeat use these insights to guide its marketing strategy?

---

##  Stakeholders
*   **Urška Sršen:** Co-founder and Chief Creative Officer
*   **Sando Mur:** Co-founder and Key Executive
*   **Bellabeat Marketing Analytics Team**
*   **Bellabeat Executive Team**

---

## 📊 Data Source & Credibility
The analysis utilises the public domain dataset **FitBit Fitness Tracker Data** available on [Kaggle](https://www.kaggle.com/datasets/arashnic/fitbit). 

### ROCCC Assessment:
*   **Reliable (Moderate):** Contains tracked biometric and activity data from 30 consenting Fitbit users.
*   **Original (No):** Third-party data collected via Amazon Mechanical Turk.
*   **Comprehensive (Limited):** Small sample size (30 users) tracked over a 31-day window. Crucially, it lacks demographic information such as gender and age. Given Bellabeat's specific focus on women's health, this omission limits direct generalisations.
*   **Current (No):** Data is from 2016.
*   **Cited (Yes):** Fully documented and publicly available under CC0: Public Domain.

### Analysed Data Files Include:
*   `dailyActivity.csv`
*   `sleepDay.csv`
*   `hourlySteps.csv`
*   `hourlyCalories.csv`
*   `heartRate.csv`
*   `weightLog.csv`

---

##  Tools Used
*   **Language:** Python
*   **Libraries:** Pandas (Data Manipulation), Matplotlib / Seaborn (Data Visualisation)
*   **Environment:** Jupyter Notebook

---

##  How to Run the Analysis
1. Clone this repository:
   ```bash
   git clone [https://github.com/Chikerezejt/bellabeat-case-study.git](https://github.com/Chikerezejt/bellabeat-case-study.git)
2. Install the required dependencies:
   ```bash
   pip install pandas matplotlib seaborn notebook
3. Open the Jupyter Notebook to view the full pipeline:
   ```bash
    jupyter notebook

## Key Insights for Bellabeat's Marketing Strategy:
* **Automation is King**: Features that require zero user effort (Steps, Calories, Intensity) have 100% participation (33/33 users). Users rely on the device to passively collect their daily movement.

* **The "Friction" Drop-off (Sleep)**: Sleep tracking requires wearing the device to bed consistently. We see a drop down to 24 users, indicating that a segment of consumers finds wearing a tracker to sleep uncomfortable or forgets to charge/wear it at night.

* **The Manual Entry Barrier (Weight)**: Weight tracking has an abysmal 8-user participation rate. Because this requires manual logging (or an expensive smart scale ecosystem), users almost completely ignore it.


# Conclusion

This analysis of smart device trends highlights a critical opportunity for Bellabeat to position itself not just as a passive data tracker but as an **active wellness partner**.
Bellabeat should lean heavily into marketing its passive, automatic tracking capabilities (like seamless, comfortable sleep tracking designed specifically for women's lifestyle habits) and find gamified or automated ways to reduce the friction of manual data logs like hydration or weight.

The data indicate that regular movement and intensive activity are the primary drivers of caloric expenditure, while prolonged stationary time (being more sedentary) predictably hinders health goals. By leveraging these insights—specifically by prompting action during sedentary valleys (Mondays) and celebrating activity peaks (Saturdays)—Bellabeat can design a highly tailored wellness app that empowers the user experience. This will ultimately guide users to balance intensity and movement throughout their busy weeks and solidify Bellabeat's footprint in the global smart wellness market.


#### Author:
##### **Timothy John**

###### Project Date: June 29, 2026

