# Diwali-Sales-Analysis

## Introduction

This documentation presents a comprehensive analysis of sales data collected during the Diwali festival. The dataset includes information about customers, products, orders, and various demographic details. The primary objective of this analysis is to improve customer experience and increase revenue by extracting meaningful insights from the sales data.

## Data Loading and Cleaning

1. The initial step involved loading the dataset into a Pandas DataFrame. 

2. The dataset, named 'Diwali Sales Data,' contained 11,251 entries with 15 columns. 

3. These columns included information such as User_ID, Customer Name, Product_ID, Gender, Age Group, Age, Marital Status, State, Zone, Occupation, Product Category, Orders, Amount, and two unnamed columns.

4. To ensure a focused analysis, irrelevant or blank columns such as 'Status' and 'unnamed1' were dropped. Additionally, null values in the 'Amount' column were addressed by removing the corresponding rows. Data types were appropriately adjusted, with the 'Amount' column converted to integers.

## Exploratory Data Analysis (EDA)

### Gender Analysis

A bar chart was plotted to visualize the distribution of purchases based on gender. The analysis revealed that the majority of buyers were female, and their purchasing power exceeded that of male customers.

![image](https://github.com/vekasheni/Diwali-Sales-Analysis/assets/146317452/6b1b5ccd-b4ff-4f5e-a984-5b81f28c7b3e)

### Age Group Analysis

A count plot and total amount visualization were generated to understand the distribution of purchases across different age groups. 

The findings indicated that the most active buyers were females in the 26-35 age group.

![image](https://github.com/vekasheni/Diwali-Sales-Analysis/assets/146317452/7d6158a4-64f0-43b3-af22-ab3a53792982)

### State-wise Analysis

The analysis extended to examining the top 10 states contributing to both total orders and total sales. Uttar Pradesh, Maharashtra, and Karnataka emerged as significant contributors to both categories.

![image](https://github.com/vekasheni/Diwali-Sales-Analysis/assets/146317452/b0f84bf5-a8f0-4348-8466-6844348ec7e0)


![image](https://github.com/vekasheni/Diwali-Sales-Analysis/assets/146317452/34ec7d62-228f-4571-b2a8-06df36dc642f)

### Marital Status and Occupation Analysis

Bar charts were used to explore the impact of marital status on purchasing behavior. Married women were identified as a prominent customer segment with high purchasing power. 

Furthermore, the occupation-wise analysis revealed that customers working in IT, Healthcare, and Aviation sectors were predominant.

![image](https://github.com/vekasheni/Diwali-Sales-Analysis/assets/146317452/e7c482c8-478e-47a6-8091-05028d9c55ba)


![image](https://github.com/vekasheni/Diwali-Sales-Analysis/assets/146317452/6f9452a5-38b8-4adf-80fe-a0b10334eaf4)

### Product Category and Product ID Analysis

Sales data was dissected based on product categories and specific product IDs. 

The most sold products belonged to the Food, Clothing, and Electronics categories.

![image](https://github.com/vekasheni/Diwali-Sales-Analysis/assets/146317452/93e88920-98a2-4b0d-a7ed-a5f040f86246)

## Conclusion

The analysis concludes that individuals in the age group of 26-35, particularly married women, residing in states such as Uttar Pradesh, Maharashtra, and Karnataka, and working in sectors like IT, Healthcare, and Aviation, are more likely to purchase products from categories such as Food, Clothing, and Electronics.

## Recommendations

- Targeted marketing campaigns could focus on the identified demographic segments to maximize sales.
- Inventory management strategies can be adjusted to meet the demand for popular product categories.
