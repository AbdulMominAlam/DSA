
Title: Evaluating the Effect of Macro-economic Conditions on Corporate R&D Investments

Objective:
Corporate spending on research and development (R&D) is essential for driving innovation and maintaining a competitive edge in the global market. However, investment in R&D is significantly shaped by macroeconomic factors such as GDP growth, inflation, unemployment, government support, and export capacity. This project aims to evaluate how these broader economic conditions influence R&D spending across multiple countries between 2010 and 2023.

Data Sources & Structure (Simulated Data):
To facilitate a structured and focused analysis, the study utilizes synthetically generated datasets that mirror real-world macroeconomic and innovation data. The dataset includes information for 10 countries over a 14-year period (2010–2023).

Dataset 1 – Macroeconomic Indicators:

Variables: GDP Growth (%), Inflation Rate (%), Unemployment Rate (%), R&D Spending (% of GDP)

Description: Represents national-level economic performance and investment in R&D

Simulated based on trends found in OECD and World Bank data

Dataset 2 – Government R&D Share:

Variable: Government’s share of total R&D funding (% of national R&D budget)

Description: Reflects the public sector's role in national innovation systems

Dataset 3 – High-Tech Exports:

Variable: High-tech exports as a percentage of total manufactured exports

Description: Indicates industrial focus and export-driven innovation activity

Countries Included (Synthetic Representations):
Germany, South Korea, Japan, United States, United Kingdom, China, India, Brazil, South Africa, Turkey

Data Preparation & Merging:
All datasets were merged on Country and Year.

The final panel dataset contains 140 observations (10 countries × 14 years).

Variables were normalized and preprocessed for visualization and machine learning modeling.

Planned Methodology:
Exploratory Data Analysis (EDA):

Use of correlation matrices, time-series plots, boxplots, and scatterplots

Analyze how R&D spending trends differ based on economic indicators

Apply Principal Component Analysis (PCA) to simplify visualization of economic dimensions

Hypothesis Testing:

Formulate and test hypotheses such as:

“Higher GDP growth leads to increased R&D investment”

“Inflation negatively correlates with R&D spending”

Machine Learning Models:

Apply supervised regression models to predict R&D spending:

Linear Regression, Decision Tree, Random Forest, XGBoost, k-Nearest Neighbors (kNN)

Apply unsupervised learning:

PCA and K-Means Clustering to reveal country groupings and innovation profiles

Justification for Synthetic Data Use:
Due to time constraints and challenges in aligning multiple public datasets across countries and years, real-world patterns were simulated using Python to reflect authentic relationships between economic conditions and innovation activity. This approach allows for focused exploration while maintaining academic relevance.

Expected Outcome:
Understand how macroeconomic factors drive or inhibit R&D investment

Identify clusters of countries with similar innovation behaviors



