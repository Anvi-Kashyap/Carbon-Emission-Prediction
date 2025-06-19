# 🌍 Prediction of CO₂ Emission From Country-Specific Data

## 📌 Introduction

Climate change is one of the most pressing global challenges of our time. One of its main drivers is the emission of greenhouse gases—particularly carbon dioxide (CO₂). Understanding what factors influence CO₂ emissions at a national level can help policymakers and researchers devise better strategies for mitigation.

This project leverages country-specific data to build predictive models that estimate CO₂ emissions based on various socio-economic, environmental, and energy-related indicators. By using real-world data from the World Bank, the project aims to uncover hidden patterns and relationships between national characteristics and their greenhouse gas output.

---

## 📊 Description of the Project

The goal of this project is to analyze and model CO₂ emissions based on a wide range of country-level features. The workflow is divided into two major phases:

### 1. Data Cleaning & Preparation:
- Removal of irrelevant and empty data entries
- Handling missing values and ensuring numerical consistency
- Reshaping the dataset into a format suitable for machine learning

### 2. Data Exploration & Predictive Analysis:
- Visual exploration of relationships between features
- Feature selection and preprocessing
- Training and evaluating machine learning models to predict CO₂ emissions

By the end of this project, a clean, usable dataset is created and used to build predictive models that can estimate CO₂ emissions using various national parameters.

---

## 📂 Description of the Data

The dataset used in this project is the **Climate Change Data** from the **World Bank Group**, covering data for most countries between **1990 and 2011**. It contains a diverse set of indicators related to:

- **Greenhouse Gas Emissions**: CO₂, CH₄, N₂O, etc.
- **Demographics**: Total population, urban population, population growth
- **Economic Indicators**: GDP, GNI, Foreign Direct Investment (FDI)
- **Land Use**: Cereal yield, agricultural land, protected areas
- **Climate Data**: Rainfall, natural disasters
- **Energy**: Energy use per capita
- **Health Infrastructure**: Medical personnel counts

> The original dataset had 28 columns and 13,512 rows, with a mix of structured and unstructured formats. Missing values were represented by both `NaN` and `".."`. Several metadata columns like `'SCALE'`, `'Decimals'`, and `'Series Code'` were identified as non-informative and removed during the cleaning process.

---

## 📈 About Data

- **Source**: [World Bank Climate Change Data](https://datacatalog.worldbank.org/dataset/climate-change-data)
- **Time Range**: 1990 – 2011
- **Countries Covered**: Global dataset (majority of countries)
- **Key Features**:
- Environmental indicators (CO₂ emissions, precipitation)
- Socio-economic indicators (GDP, GNI, urban population)
- Energy and health indicators
- **License**: [Creative Commons Attribution 4.0 International](https://datacatalog.worldbank.org/public-licenses#cc-by)

---

This project not only enhances understanding of the drivers of CO₂ emissions but also provides a predictive modeling framework that can be extended to newer datasets and variables. The trained model could potentially support **policy formulation**, allowing countries to forecast and manage their emissions more effectively.
