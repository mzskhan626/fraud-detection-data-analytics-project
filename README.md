# Fraud Detection Data Analytics Project

## Overview
Fraud detection is critical for safeguarding financial institutions and e-commerce platforms from significant financial losses. This project analyzes patterns in fraudulent transactions to identify key indicators and relationships, showcasing the power of data analytics in mitigating fraud risks.

## Project Structure
This project follows a systematic data analysis workflow to provide actionable insights:
1. **Project Overview and Domain Frame**: Background on the topic, motivation, and stakeholders.
2. **Problem Statement and Analytical Questions**: Definition of the problem and key questions explored through data analytics.
3. **Data Loading and Setup**: Importing and setting up the dataset and libraries.
4. **Data Taxonomy and Variable Nature**: Classifying variables as categorical or numerical.
5. **Exploratory Data Analysis (EDA)**: Summarizing, aggregating, and cleaning data.
6. **Data Visualization**: Creating insightful and impactful visualizations.
7. **Findings & Conclusion**: Summarizing key insights and takeaways from the analysis.
8. **References**: Listing datasets and tools used in the project.

## Dataset
The dataset contains transactional data with the following features:
- **Profession**: Profession of the cardholder (Doctor, Lawyer, Engineer).
- **Income**: Annual income of the cardholder.
- **Credit Card Number**: Unique identifier for the credit card (excluded from analysis).
- **Expiry**: Credit card expiration date.
- **Security Code**: Security code of the card.
- **Fraud**: Target variable indicating if a transaction is fraudulent (1 for fraud, 0 otherwise).

### Data Source
The dataset was provided as part of course instructions and is sourced from [Kaggle](https://www.kaggle.com/).

## Tools and Libraries
This project leverages the following tools and libraries for data analytics:
- `Pandas`: For data manipulation and analysis.
- `Matplotlib`: For creating clear and impactful visualizations.
- `Seaborn`: For statistical data visualization and enhanced aesthetics.

## Analytical Questions
1. **What are the key indicators in a transaction that signal fraud?**
   - Understanding patterns can improve early fraud detection and risk mitigation.
2. **How do factors such as profession, income, and security codes correlate with fraudulent transactions?**
   - Insights can help focus on high-risk areas for targeted interventions.

## Visualizations
- **Income Distribution**: Histogram with KDE for understanding income spread.
- **Fraud by Profession**: Bar chart highlighting fraud rates across professions.
- **Security Code vs Income**: Scatter plot visualizing relationships between security code and income.
- **Fraud Distribution by Expiry Dates**: Count plot showing fraud patterns based on expiration dates.
- **Correlation Heatmap**: Examines relationships between numerical variables.

## Key Insights
1. Fraud rates vary across professions, with doctors having the highest fraud rates.
2. Income levels influence fraud risks, with lower-income transactions showing higher fraudulent activity.
3. Security codes and expiration dates reveal patterns that can improve fraud detection systems.

