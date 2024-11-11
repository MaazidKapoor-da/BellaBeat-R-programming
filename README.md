# Case Study:- Bellabeat Fitness Data Analysis 

The case study follows six steps data analysis process

❓Ask

💻 Prepare

🛠️ Process

📊 Analyse

📋 Share

🧗 Act


![196562658-bfe5df3b-4e68-4c4e-97b8-d9c057d28dec](https://github.com/user-attachments/assets/4d0a0b5b-1d28-49c8-b441-3bd5c78630c2)

## Introduction

Bellabeat is a high-tech manufacturer of health-focused products for women. Collecting data on activity, sleep, stress, and reproductive health has allowed Bellabeat to empower women with knowledge about their own health and habits. Although Bellabeat is a successful small company, they have the potential to become a larger player in the global smart device market. Urška Sršen, cofounder and Chief Creative Officer of Bellabeat, believes that analyzing smart device fitness data could help unlock new growth opportunities for the company.

### STEP 1: ASK

### Business Task

To identify potential opportunities for growth and provide recommendations for the Bellabeat marketing strategy improvement based on trends in smart device usage.

**Key Stakeholders**

- Urška Sršen: Bellabeat's cofounder and Chief Creative Officer
- Sando Mur: Mathematician and Bellabeat’s co-founder

**Questions to explore for analysis:**

1. What are some trends in smart device usage?
2. How could these trends apply to Bellabeat customers?
3. How could these trends help influence Bellabeat marketing strategy?

### STEP 2: PREPARE

The data being used in this case study can be found here: [FitBit Fitness Tracker Data](https://www.kaggle.com/datasets/arashnic/fitbit) CC0: Public Domain, dataset made available through [Mobius](https://www.kaggle.com/arashnic)

The data is stored and uploaded in R Studio. This Kaggle data set contains personal fitness tracker from thirty fitbit users. Thirty eligible Fitbit users consented to the submission of personal tracker data, including minute-level output for physical activity, heart rate, and sleep monitoring. It includes information about daily activity, steps, and heart rate that can be used to explore users’ habits.

The data set contains 18 CSV files organized in long format. Below is a breakdown of the data using the ROCCC approach:

* **Reliability-Low**: The data comes from 30 fitbit users who consented to the submission of personal tracker data, including minute-level output for physical activity, heart rate, and sleep monitoring.
* **Original-Low**: Third party data collect using Amazon Mechanical Turk
* **Comprehensive - MED:** The dataset contains multiple fields on daily activity intensity, calories used, daily steps taken, daily sleep time and weight record.
* **Current - LOW:** This data is from March 2016 through May 2016. The data is not current, meaning that user habits may have changed over the years.
* **Cited - LOW:** Data was collected from a third party, therefore unknown.

### Loading packages





