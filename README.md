# 🏡 Housing Price Analysis – Exploratory Data Analysis (EDA)

## 📌 Project Overview
This project analyzes the California Housing Dataset to identify the key factors influencing housing prices. The goal is to explore patterns, understand feature relationships, and set a strong foundation for future machine learning models.

The analysis covers:
- Value distribution  
- Correlations  
- Location-based insights  
- Feature impact on price  

---

## 📂 Dataset Description
This dataset includes information about California housing blocks with fields such as:

- **median_house_value**
- **median_income**
- **total_rooms**
- **total_bedrooms**
- **population**
- **households**
- **ocean_proximity**

The mix of numeric and categorical features makes it ideal for regression and geographical analysis.

---

## 🔍 EDA Steps Performed

### **1. Data Cleaning**
- Checked for null values  
- Ensured correct data types  
- Cleaned numerical and categorical columns  

### **2. Univariate Analysis**
- Histograms for key features (house value, income, households)  
- Distribution checks for skewness and outliers  

### **3. Bivariate Analysis**
- Scatterplot: **median_income vs median_house_value**  
- Boxplots comparing house values across ocean proximity  

### **4. Correlation Analysis**
- Correlation heatmap for numerical variables  
- Identified strongest and weakest relationships  

### **5. Categorical Feature Study**
- Bar plot of **ocean_proximity**  
- Distribution across categories  

---

## 📈 Key Insights

### **1. House values are right-skewed**
Most properties fall in the lower price segment, with a long tail of high-value homes.  
This supports applying transformations (like log scaling) for modeling.

### **2. Median income strongly predicts house value**
It shows the highest positive correlation with median house value.  
This confirms income as the most influential socio-economic factor.

### **3. Rooms and household counts have weak predictive power**
Despite common assumptions, these features show only mild relationships with price.  
Their impact is significantly lower than income or location.

### **4. Ocean proximity affects value**
Homes closer to the ocean tend to be more expensive, showing a clear location premium.

### **5. Categorical imbalance exists**
Some ocean proximity categories appear far more frequently, which needs careful handling during model training.

---

## 📌 Conclusion
This EDA provides a solid understanding of the factors that influence California housing prices.  
Key drivers include income and ocean proximity, while household and room counts offer limited predictive value.  
The target variable’s skewness suggests further preprocessing before model development.

The dataset is well-prepared for:
- Feature engineering  
- Regression modeling  
- Predictive analysis  

---

## 📦 Requirements
Dependencies used in the project:
pandas,
numpy,
matplotlib,
seaborn
