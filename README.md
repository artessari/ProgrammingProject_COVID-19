# Exploring Europe's COVID-19 Landscape: A Data Journey

This project was developed for the **Introduction to Programming for Data Science** course at the **Free University of Bozen-Bolzano**. It offers a comprehensive analysis of COVID-19’s impact and spread across Europe, utilizing a range of **data science** and **machine learning** techniques. Through data exploration, visualization, and predictive modeling, the project aims to uncover key patterns and insights into how the pandemic evolved, while highlighting the factors that influenced its trajectory.

## Project Overview

The COVID-19 pandemic has had a far-reaching impact on public health, economics, and daily life across the globe. Focusing on Europe, this project explores COVID-19 data to uncover patterns and insights into the pandemic’s progression and its effects on different countries. By integrating data science techniques, this study sheds light on correlations between cases, government responses, and societal factors. The key aspects of the project include:

- **Data Exploration and Preprocessing**: Cleaning, handling missing values, and selecting relevant features.
- **Data Visualization**: Interactive maps to track the pandemic’s geographical spread, time series analysis to monitor case trends, and correlation heatmaps for understanding feature relationships.
- **Machine Learning Models**: Regression techniques (linear, polynomial, ridge, and lasso regression) to predict outcomes and understand significant predictors.
- **Feature Selection and Ranking**: Methods such as random forest and recursive feature elimination (RFE) to identify key variables.
- **Clustering and Dimensionality Reduction**: Principal component analysis (PCA) and clustering techniques to group countries and identify common patterns.

## Repository Structure

```
├── owid-covid-data.csv                             # Dataset in CSV format
├── FinalProject_Arianna_Tessari_19322.ipynb        # Main Jupyter notebook with code
├── FinalProject_Arianna_Tessari_19322.html         # Exported HTML version of the notebook
├── requirements.txt                                # Dependencies for the project (use to recreate environment)
└── README.md                                       # Project README file
```

## Key Files

- FinalProject_Arianna_Tessari_19322.ipynb: The main Jupyter notebook containing the full analysis.
- owid-covid-data.csv: This CSV file serves as the primary dataset, featuring comprehensive COVID-19 data relevant to Europe.
- FinalProject_Arianna_Tessari_19322.html: An exported HTML version of the Jupyter notebook, which provides a detailed report discussing the project's objectives, methodology, findings, and conclusions.
- requirements.txt: The list of Python dependencies required to run the project.

## How to Run

**1. Clone the repository**
```
git clone https://github.com/artessari/ProgrammingProject_COVID-19
cd ProgrammingProject_COVID-19
```

**2. Install Dependencies**

To install the required Python libraries, run:
```
pip install -r requirements.txt
```

**3. Run Jupyter Notebook**

To explore the project interactively, launch the notebook.

## Results

The analysis provides several key insights into the spread and impact of COVID-19 in Europe:

- **Correlation Analysis**: Strong correlations are identified between various features, such as confirmed cases, fatalities, and mobility changes. These relationships highlight how changes in human movement influence the pandemic's trajectory.
- **Regression Models**: Various regression techniques (linear, polynomial, ridge, and random forest) are applied to examine the relationships between different factors and COVID-19 cases and deaths. Ridge and lasso regression, in particular, help identify significant predictors, such as healthcare capacity, population density, and the stringency of government interventions.
- **Clustering and PCA**: Principal Component Analysis (PCA) and clustering techniques reveal patterns and group countries based on shared characteristics like infection rates, containment policies, and healthcare capacity, providing a clearer understanding of the pandemic's regional dynamics.

## Conclusions

This project demonstrates the power of data science and machine learning in analyzing the COVID-19 pandemic in Europe. The findings emphasize the importance of early and stringent containment measures in controlling virus transmission. Moreover, the integration of social and economic data illustrates the broad societal impacts of the pandemic, extending beyond public health to affect economic activity and daily life.

Advanced modeling techniques, such as ridge regression and random forest, enable a deeper understanding of the key factors driving the pandemic, offering insights that can inform future policy decisions. Overall, this study highlights the value of data-driven approaches in navigating complex crises like COVID-19 and underscores the need for robust public health infrastructure to mitigate future global health challenges.

### References

**Our World in Data**
Data Source: [OWID COVID-19 Data](https://covid.ourworldindata.org/data/owid-covid-data.csv)  
