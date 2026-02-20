# 🍕 Pizza Sales Data Analysis

## Project Overview
This project analyzes pizza sales data to understand customer purchasing behavior, sales performance, and product trends. The objective is to extract meaningful insights that can support business decision-making and improve business strategy.

The analysis was carried out using Python in Jupyter Notebook with data cleaning, merging, visualization, and exploratory data analysis techniques.

---

## Dataset Description
The analysis uses four related datasets:

- **orders.csv** — Contains order dates and times
- **order_details.csv** — Includes quantity and order information
- **pizzas.csv** — Provides pizza size and price details
- **pizza_types.csv** — Contains pizza names and categories

These datasets were merged using common keys such as:

- `order_id`
- `pizza_id`
- `pizza_type_id`

to create a complete dataset for analysis.

---

## Project Workflow

### 1. Data Loading
All datasets were imported individually using pandas.

### 2. Data Inspection
- Checked dataset structure
- Examined column names and data types
- Previewed datasets using `.head()`

### 3. Data Merging
Datasets were combined into a single dataframe to enable comprehensive analysis across orders, pizzas, and customer behavior.

### 4. Exploratory Data Analysis (EDA)
The analysis explored:

- Sales performance
- Pizza popularity
- Revenue trends
- Daily and monthly sales patterns
- Relationship between price, quantity, and revenue

---

## Visualizations Created
The project includes several visualizations such as:

- Pizza sales distribution
- Revenue analysis by pizza size
- Daily sales trends
- Monthly sales patterns
- Popular and least-selling pizzas
- Correlation heatmap showing relationships between numerical variables

---

## Key Insights

### 📊 Revenue Performance
- Total revenue generated during the analyzed period was **₦851,519**, showing strong business performance.
- Large-sized pizzas generated the highest revenue, suggesting customers prefer larger portions or group orders.

### 📅 Sales Trends
- **Fridays recorded the highest sales**, likely due to social activities and end-of-week demand.
- **Sundays showed the lowest sales**, indicating reduced customer activity.
- Monthly variations suggest possible seasonal demand patterns.

### 🍕 Customer Preferences
The most popular pizzas include:
- Classic Deluxe
- Barbecue Chicken
- Hawaiian
- Pepperoni
- Thai Chicken

These items represent strong customer favorites and should remain core menu offerings.

### ⚠️ Product Performance
- Some pizza types recorded low sales and may require marketing promotion or menu review.

### 🔗 Correlation Insight
- Revenue shows a strong positive relationship with quantity sold.
- Price has a weaker relationship with quantity, suggesting demand is not highly price-sensitive.

---

## Overall Business Insights
- Midday and evening periods drive the highest sales.
- Large pizzas contribute the most revenue.
- Fridays are the most profitable business days.
- A small number of pizzas dominate customer preference.
- Underperforming menu items may need strategic adjustments.

---

## Tools and Libraries Used
- Python
- pandas
- matplotlib
- seaborn
- Jupyter Notebook

---
## How to Run the Project

1. Clone this repository:

```bash
git clone https://github.com/Fikunfunmi/pizza-sales-analysis.git
```
  

Open the notebook:
FIKUNAYOMI TOLU OWODOLU - 043- TASK THREE.ipynb

---
## Author
Fikunayomi Tolu Owodolu

---
