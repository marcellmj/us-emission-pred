# Bachelor Thesis: Machine Learning-Based Feature Importance Analysis of Power Plant Emissions Across U.S. States

Air pollution from power plants is a major environmental concern, with emissions of CO2, NOx,
and SO2 contributing to climate change and air quality issues. While machine learning has shown
promise in predicting these emissions, the roles of specific features and their interactions within models are not
well understood, particularly across different regulatory and geographic contexts. This
thesis applies and compares machine learning and explainable AI techniques to understand how features like fuel type, plant
technology, heat input, or regulatory frameworks influence emissions across different U.S. states.
By comparing feature importance across states, the project additionally provides insights into how (and if) these models could be used to identify regional emission drivers and policy effectiveness.

### Repo Structure
This project is divided into three main parts:

1. [Preliminary Data Processing](/01_Preliminary_Data_Processing/README.md)  
   Early data transformation and merging for general analysis.

2. [Exploratory Data Analysis (EDA)](/02_EDA/README.md)  
   Temporal, distributional, and relational exploratory analysis.

3. [Machine Learning Modeling](/03_ML_Modeling/README.md)  
   Model-specific preprocessing, performance evaluation, and xAI application.

[Additional_Visualizations.ipynb](/Additional_Visualizations.ipynb) contains the code for three additional visualizations that were used in the paper or presentation.

[ba-thesis.pdf](/ba-thesis.pdf) and [presentation.pdf](/presentation.pdf) contain the final thesis and presentation work.

### Data Sources:

United States Environmental Protection Agency (EPA), “Clean Air Markets Program Data (CAMPD),” Apr. 2025, Washington, DC: Office of Atmospheric Protection, Clean Air and Power Division. [Online] Available: [https://campd.epa.gov](https://campd.epa.gov) [Accessed on: 2025-05-30]

United States Energy Information Administration (EIA), “Form EIA-860 detailed data with previous form data (EIA-860A/860B),” Jun. 2025. [Online] Available: [https://www.eia.gov/electricity/data/eia860/](https://www.eia.gov/electricity/data/eia860/)  [Accessed on: 2025-07-01].
  
Iowa State University — Iowa Environmental Mesonet, “Automated Surface Observing System (ASOS) Network,” 2025. [Online] Available: [https://mesonet.agron.iastate.edu/ASOS/](https://mesonet.agron.iastate.edu/ASOS/) [Accessed on: 2025-06-26]

---
### Supplementary Information:
Provides some additional information in the form of official guides about the hourly emissions data provided by the EPA's CAMPD and its regulatory background.

- The [CAMPD Glossary](https://campd.epa.gov/help-support/glossary) provides definitions and example values of the data supplied by CAMPD [1].

- The [Plain English Guide to the Part 75 Rule](https://www.epa.gov/power-sector/emissions-monitoring-and-reporting) offers a simplified overview of 40 CFR Part 75. While it is not a substitute for the full regulatory text, it serves as a helpful resource for general understanding [2].

**Sources:**  

[1] United States Environmental Protection Agency (EPA), "Glossary — Clean Air Markets Program Data (CAMPD)", Apr. 2025. [Online] Available: [https://campd.epa.gov/help-support/glossary](https://campd.epa.gov/help-support/glossary) [Accessed: 2025-08-23]

[2] United States Environmental Protection Agency (EPA), "Emissions Monitoring and Reporting — Plain English Guide to the Part 75 Rule", Jun. 2009. [Online] Available: [https://www.epa.gov/power-sector/emissions-monitoring-and-reporting](https://www.epa.gov/power-sector/emissions-monitoring-and-reporting) [Accessed: 2025-08-23]

