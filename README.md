# Restaurant_Exploratory_Data_Analysis
# 🍽️ Restaurant Exploratory Data Analysis

This project focuses on performing **data cleaning, preprocessing, and exploratory data analysis (EDA)** on a restaurant dataset.  
The dataset includes order-level details such as dates, products, prices, quantities, payment methods, managers, and cities.  
The analysis provides insights into customer behavior, sales performance, and revenue distribution.

---

## 📂 Dataset Features
The dataset contains the following columns:

- **Order ID** → Unique identifier for each order  
- **Date** → Date of the order  
- **Product** → Food or beverage item ordered  
- **Price** → Price of each product  
- **Quantity** → Number of units ordered  
- **Purchase Type** → Type of order (e.g., Dine-in, Takeaway, Delivery)  
- **Payment Method** → Payment method used (Cash, Card, etc.)  
- **Manager** → Responsible manager for the order  
- **City** → City where the order was placed  
- **Revenue** → Total revenue (calculated as `Price × Quantity`)  

---

##  Steps Performed
1. **Data Cleaning & Preprocessing**
   - Handled missing values  
   - Converted date column to proper datetime format  
   - Removed duplicates and inconsistencies  
   - Created new feature: **Revenue**  

2. **Exploratory Data Analysis (EDA)**
   - Distribution of products, payment methods, and purchase types  
   - Revenue trends over time (daily / monthly)  
   - Top performing products and cities  
   - Manager-wise performance  
   - Correlation between features (Price, Quantity, Revenue)  

3. **Data Visualization**
   - Histograms and bar charts for categorical features  
   - Line charts for revenue trends  
   - Pie charts for payment method distribution  
   - Horizontal bar charts for top products and cities  

---

##  Insights
- Identified the **top-selling products** and cities contributing the most revenue  
- Analyzed **revenue trends** over time to detect growth/decline patterns  
- Observed customer preferences in **payment methods** and **purchase types**  
- Evaluated **manager performance** across different branches  

---

## 📈 Visualizations

Here are some key visualizations from the analysis:

### 1. Features Correlations
![Revenue Trend](https://github.com/rahmasaber123/Restaurant_Exploratory_Data_Analysis/blob/main/Feature_Correlation.png?raw=true )

### 2. Distribution of Payment Methods
![Payment Methods](https://github.com/rahmasaber123/Restaurant_Exploratory_Data_Analysis/blob/main/Payment_Distribution.png?raw=true)

### 3. Top  Products by Quantity
![Top Products](https://github.com/rahmasaber123/Restaurant_Exploratory_Data_Analysis/blob/main/Product_Per_Quantity.png?raw=true )

### 4. Revenue by City
![Revenue by City](https://github.com/rahmasaber123/Restaurant_Exploratory_Data_Analysis/blob/main/Top_Selling_cities.png?raw=true )

---

## 🛠️ Tech Stack
- **Python**  
- **Pandas & NumPy** → Data cleaning & preprocessing  
- **Matplotlib & Seaborn** → Data visualization  
- **Jupyter Notebook** → Interactive analysis  

---

## 🚀 How to Use
1. Clone this repository:
   ```bash
   git clone https://github.com/rahmasaber123/Restaurant_Exploratory_Data_Analysis
## AUTHOR
 RAHMA SABER ABBAS
