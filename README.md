# Factors Contributing to Canine Aggression: A Statistical Analysis
**DATA606 Statistics & Probability Project | CUNY Master of Data Science**

## 📌 Project Overview
This project investigates the environmental and demographic factors that influence aggression in dogs. Using data from the **ManyDogs 2024 Project**, an international survey of dog guardians, I conducted a multiple linear regression analysis to identify which variables—such as home environment, origin (shelter vs. breeder), and age—most significantly predict aggressive behavior.

## 📊 Key Research Questions
* Does a dog's physical environment (urban vs. rural) impact aggression scores?
* How do factors like breed purity, age, and the number of other dogs in the household contribute to behavioral outcomes?
* What is the statistical difference in aggression scores between dogs from "shelters" versus those from "rescue" organizations?

## 🛠️ Methodology & Technical Stack
* **Language:** R (Multiple Linear Regression)
* **Data Source:** ManyDogs_2024 International Survey
* **Statistical Methods:** * **Data Wrangling:** Extensive cleaning and handling of missing values (NAs) to preserve data integrity.
  * **Feature Engineering:** Derived a composite "Aggression Score" from a subset of 27 survey responses to provide a more granular dependent variable.
  * **Model Validation:** Assessed regression assumptions including linearity, homoscedasticity, normality of residuals, and absence of multicollinearity (VIF).

## 💡 Key Findings & Insights
* **The "Origin" Effect:** Interestingly, dogs from "shelters" showed an increase in aggression scores, while those from "rescues" showed a decrease. This may suggest differences in socialization environments or resource allocation between the two types of organizations.
* **Environmental Impact:** Dogs in private home settings with multiple other dogs and those of non-purebred status showed higher likelihoods of reactive behavior.
* **Predictive Power:** The final model achieved an **adjusted $R^2$ of ~0.2**. While statistically significant, this highlights the complexity of animal behavior and the need for further quantitative variables.

## 📁 Repository Structure
* `Chen-ProjectWorkingFile.Rmd`: The primary R Markdown file containing the data processing and regression model.
* `Project_Presentation.pptx`: A visual summary of the research goals, methodology, and findings.

---
**Author:** Jessica Chen  
**Date:** December 2025  
**Course:** DATA606 - Statistics and Probability for Data Analytics
