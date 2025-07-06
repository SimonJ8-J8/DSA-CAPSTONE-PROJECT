# DSA-CAPSTONE-PROJECT 1

# 📊 Project Topic: Amazon Product Sales & Customer Insight Analysis

This project explores a dataset of Amazon electronics accessories to uncover patterns in pricing, discount strategies, product popularity, and customer satisfaction. Built using Microsoft Excel, the analysis reveals data-driven insights that can inform e-commerce and marketing strategies.

## 📁 Dataset Overview

The dataset includes details for multiple products listed on Amazon, including:

| Column               | Description |
|----------------------|-------------|
| `product_id`         | Unique product identifier |
| `product_name`       | Full product name |
| `category`           | Product hierarchy |
| `discounted_price`   | Final sale price |
| `actual_price`       | Original price before discount |
| `discount_percentage`| Discount as a decimal |
| `rating`             | Average customer rating |
| `rating_count`       | Total number of ratings |
| `about_product`      | Summary of product features |
| `review_title`       | Short summary of review |
| `review_content`     | Full review content |
| `img_link`           | Product image |
| `product_link`       | Amazon product URL |


## 🎯 Project Goals

- Analyze product pricing and discount trends
- Evaluate customer satisfaction through ratings and reviews
- Identify top-performing products
- Provide data-backed business recommendations

## 🧠 Key Insights

### 💸 Discount Patterns
- Products are heavily discounted — some up to **90%**.
- The average discount across all products is ~**62%**.
- Most discounted products are generic cables; branded ones offer modest discounts.

### ⭐ Customer Ratings
- High-volume products (10k+ reviews) with ratings above **4.0** dominate sales.
- Example: **boAt Deuce USB 300** – 4.2★ rating with over 94,000 reviews.

### 💬 Review Themes
- Positive: “fast charging”, “durable”, “value for money”
- Negative: “short lifespan”, “not original”, “poor quality”

### 📊 Top Products (based on rating and popularity)
- Products with high ratings and high review counts indicate strong customer trust.
- Discounted items aren’t always low-quality — some are top-rated.

## 🔧 Tools & Techniques

| Tool/Skill         | Usage                          |
|--------------------|---------------------------------|
| **Microsoft Excel**| Data cleaning & exploration     |
| **Pivot Tables**   | Aggregating reviews & ratings   |
| **Formulas**       | AVERAGEIFS, COUNTIFS, VLOOKUP   |
| **Charts**         | Bar, scatter, and histograms    |
| **Storytelling**   | Translating data to insight     |


## 📈 Visualizations

You can create the following charts in Excel:

- **Bar Chart**: Average discount per product category
- **Histogram**: Distribution of product ratings
- **Scatter Plot**: Review count vs. Rating

## 📌 Recommendations

1. **Promote Top-Rated Products**  
   Surface high-rating products on Amazon’s homepage or in ads.

2. **Optimize Discount Strategy**  
   Ideal discount range: **40–60%** — attracts buyers without hurting profit margin.

3. **Improve Product Descriptions**  
   Emphasize keywords like “fast charging”, “durable”, “tangle-free”.

4. **Monitor Negative Trends**  
   Flag products with many complaints or repeated review issues.

## 📝 How to Reproduce

1. Open the dataset in Microsoft Excel.
2. Use Pivot Tables to analyze by `category`, `rating`, `discount_percentage`.
3. Use formulas like:
   ```excel
   =AVERAGEIFS([rating], [rating_count], ">=1000")
   =1 - ([discounted_price] / [actual_price])
Insert charts to visualize key findings.

## 📚 What I Learned

This project helped reinforce skills in:

- Data cleaning and formatting

- Exploratory data analysis using Excel

- Identifying patterns in consumer behavior

- Writing actionable business insights

## 👨‍💻 Author

Dawat Ezra Simon
Aspiring Business Data Analyst
Excel | Power BI | SQL

## 📎 Project Assets

📁 Excel Dataset: Amazon case study.xlsx

📊 Dashboards & Visuals: The visuals are provided in the uploaded files

# 📝 Presentation Summary: 

# 📊 Amazon Product Sales & Customer Insight Analysis

---

## 🎯 Executive Summary

This project explores Amazon product data — specifically electronics accessories — to uncover how **pricing strategies**, **customer feedback**, and **discount patterns** influence **sales performance** and **product success** on the platform.

Using Microsoft Excel for analysis, this project identifies:
- Top-performing products
- Key discount tactics
- Consumer behavior trends
- Actionable insights for business decision-making

---

## 📌 Project Objectives

- 🔍 Analyze pricing and discount strategies
- 🌟 Evaluate customer satisfaction and review trends
- 🛒 Identify high-performing and low-performing products
- 💼 Deliver business recommendations for product marketing and sales optimization

---

## 🗂️ Dataset Overview

| Field                | Description |
|----------------------|-------------|
| `product_name`       | Product title |
| `category`           | Category/subcategory path |
| `discounted_price`   | Price after discount |
| `actual_price`       | Original price |
| `discount_percentage`| % of discount (derived) |
| `rating`             | Average customer rating |
| `rating_count`       | Number of ratings |
| `review_title`       | Summary of customer review |
| `review_content`     | Full review text |

---

## 🔍 Key Findings

### 🏷️ Discounts & Pricing

- **Average discount: 62%**
- Some products discounted up to **90%**, especially in accessories and cables
- Branded items typically offered smaller but more strategic discounts

### 🌟 Customer Feedback

- Most trusted products had **4.0+ ratings** and **10k+ reviews**
- Positive reviews commonly highlight:
  - ✅ “Fast charging”
  - ✅ “Durability”
  - ✅ “Value for money”
- Negative reviews often point to:
  - ❌ “Short life span”
  - ❌ “Not original” items

### 🏆 Best Performing Product Example

- **boAt Deuce USB 300**
  - ⭐ Rating: 4.2
  - 💬 Reviews: 94,000+
  - 💰 Discounted Price: ₹329
  - ✅ Keywords: Fast charging, tangle-free, value

---

## 📈 Insights & Visualization Ideas

| Chart | What it Shows |
|-------|----------------|
| 📊 Bar Chart | Average discount per category |
| 📌 Scatter Plot | Rating vs. Number of Reviews |
| 🧮 Histogram | Distribution of product ratings |
| ☁️ Word Cloud | Most common review terms |

---

## 💡 Business Recommendations

1. **Promote Highly Rated Products**  
   Highlight them in Amazon ads and sponsored listings.

2. **Optimize Discount Ranges**  
   Ideal promotional window: **40%–60%** for sustainable sales without eroding brand value.

3. **Track Product Complaints**  
   Use review data to identify low-performing listings needing quality checks.

4. **Strengthen Descriptions**  
   Feature high-impact phrases like *"fast charging"*, *"tangle-free"*, *"durable cable"* in product titles.

---

## 🧰 Tools Used

| Tool | Purpose |
|------|---------|
| Excel | Data cleaning, formulas, PivotTables |
| Power BI (optional) | Visualization and dashboarding |
| Python (optional) | Advanced bonus or trend analysis |

---

## 📁 File Structure

```plaintext
📦 amazon-product-insight
├── data/
│   └── amazon_case_study.xlsx
├── visuals/
│   └── charts and graphs (optional)
├── README.md
✍️ Author
Simon Justice
📌 Business Data Analyst
🔧 Skills: Excel • Power BI • SQL • E-commerce Analytics



