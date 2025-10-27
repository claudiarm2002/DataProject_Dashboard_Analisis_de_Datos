# Risk Factors and Living Area Impact – UrbanTrace Dashboard

---

## Project Description

This project presents an interactive dashboard built using the **UrbanTrace** dataset, which predicts individual pollution exposure and associated risk levels based on lifestyle and environmental factors.

The main objective is to identify key factors that strongly contribute to increased risk, and to examine how the risk index changes within each type of living area depending on specific environmental and lifestyle factors.

The analysis combines **data cleaning**, **exploratory data analysis (EDA)**, and **interactive visualization techniques**. Macros are used to dynamically analyze the risk within a specific living environment, depending on factors such as awareness level, years spent in that environmental context, and access to green spaces, among others.

---

## Project Structure

In the folder, besides this explanatory README file, you can find:

- **Original dataset (.csv):** the raw data used for the analysis.  
- **Excel workbook (.xlsx):** which includes the following sheets:  
  - **Dataset:** contains the dataset after cleaning and formatting.  
  - **Data Comprovation:** used to verify data consistency, ensure that missing values do not significantly affect the results, and outline the initial research questions and data relationships to be explored.  
  - **Analysis (EDA):** includes descriptive statistics, preliminary visualizations, correlation analysis, and the identification of key patterns and relationships in the data. This sheet helps determine which factors are most relevant for the dashboard.  
  - **Dashboard:** the interactive visualization area where the macros operate to dynamically analyze risk factors.  

---

## Results and Conclusions

The analysis revealed that, as expected in a synthetic dataset, some variables are perfectly and strongly correlated. In contrast, others show almost no relationship, even though such a connection would likely exist in real-world scenarios. Despite this limitation, it was exciting to observe how certain relationships produced logical and consistent results, reflecting realistic patterns of environmental influence on risk. It would have been great to perform the same analysis with real-world data, but after extensive research, I was unable to find a publicly available dataset on this topic that was both suitable and easy to interpret.

### Key Observations from the Dashboard

- **Overall KPIs:**  
  At the top of the dashboard, key indicators show the average pollution score, the total number of individuals in risk situations due to pollution, and the percentage of the population without access to natural spaces. These KPIs provide context for the rest of the analysis.

- **Left Panel – Risk vs Environment:**  
  - The probability of living in an **urban environment** is noticeably higher for individuals in **high-risk** situations compared to those in **low-risk** situations, suggesting a direct relationship between risk level and residential environment.  
  - The average number of nearby industries for high-risk individuals exceeds 4, while for low-risk individuals it is below 1. Other environmental and lifestyle factors also show higher values for high-risk individuals than for low-risk ones.

- **Right Panel – Insights by Residential Area:**  
  - The **pollution score** is consistently higher for individuals living in **urban areas** compared to **semi-urban** and **rural areas**.  
  - This confirms that the living environment strongly influences exposure and risk patterns, supporting the observations from the left panel.

---

**Author:** Clàudia Rafart Medina

