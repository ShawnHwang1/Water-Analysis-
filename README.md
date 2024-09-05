# Water-Analysis-
Personal research project on water quality.
# Water Quality Prediction
This project aims to predict water quality based on historical data. Water is a vital resource for life, but its quality is susceptible to various threats, such as acidity, pH, and pollution. Accurate predictions of water quality allow us to identify risks early and take precautionary measures, potentially aiding environmental agencies in decision-making processes, from enacting new regulations to identifying areas of focus.

# Problem Statement
Water quality is affected by multiple factors, including specific conductance, pH, dissolved oxygen, and temperature. Predicting water quality, particularly in regions like Georgia, is important for proactive environmental management. The primary goal of this project is to build models that predict the day-to-day water quality in Georgia using historical data.

# Data Source
The dataset used in this project comes from the National Science Foundation's Water Quality Prediction dataset. It contains historical data from 36 sites in Georgia and includes various water quality indicators such as:
- pH
- Dissolved Oxygen
- Temperature
- Specific Conductance
  
# Water Quality Indicators
- Specific Conductance: Also known as electrical conductivity, this measures water's ability to conduct electricity, influenced by salts and ions. Higher specific conductance can indicate pollution.
- pH: This measures how acidic or basic the water is on a scale of 0-14. According to the US Environmental Protection Agency (EPA), a pH between 6.5 and 8.5 is considered good. Outside this range, water can become problematic.
- Dissolved Oxygen: This measures how much oxygen is present in the water. Higher dissolved oxygen levels support better water quality and life sustainability.
# Analysis Methods
## Exploratory Data Analysis (EDA)
- We performed Exploratory Data Analysis (EDA) on the dataset using multilpe visualizations to understand trends and relationships between variables. These visualizations focus on understanding the relationship between specific conductance, temperature, pH, and dissolved oxygen.

# Modeling Techniques
We applied two key techniques to predict water quality:
## RANSAC Linear Regression
- Explanation: Linear regression creates a fitted line to predict outcomes based on input variables. In this project, linear regression helps predict water quality metrics, which is critical in understanding trends over time.
## K-Nearest Neighbors (K-NN) Regression
- Explanation: K-NN regression utilizes the KNN algorithm to predict values. We applied this method to variables like pH min, specific conductance, temperature mean, and dissolved oxygen mean to predict pH max. Predicting pH max is important because extreme pH levels can have significant effects on water quality and usability.
# What We Want to Know
- The goal is to predict water quality daily for the state of Georgia. Specifically, we want to create a model that predicts pH max based on pH min, specific conductance, temperature, and dissolved oxygen levels.

# Project Structure
Getting Started.
- Download the ipynb file.
- Download the dataset from the UCI Water Quality Prediction Dataset.
- Download the dataset given in the repository.

# Conclusion
- This project provides insights into water quality prediction in Georgia, focusing on factors such as specific conductance, pH, and dissolved oxygen. The use of RANSAC linear regression and K-NN regression allows us to build predictive models that can assist in making informed environmental decisions.
