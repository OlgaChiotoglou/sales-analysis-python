# Marketing and Statistical Analysis Case Study

### Customer Behavior, Conversion, and Revenue Performance Analysis

This project analyzes customer data to understand how marketing channels, 
customers' browsing behavior influence conversion and revenue.

The goal is to identify patterns in acquisition channels, purchasing behavior, and 
customer engagement that can inform marketing strategy.

The study focuses on:

- Revenue contribution by marketing channel
- Conversion efficiency across acquisition sources
- Customer demographics and purchasing behavior
- The relationship between browsing engagement and purchase activity
- The impact of discounts on transaction value

The project combines exploratory data analysis with statistical testing 
to generate business insights and marketing recommendations.

## Dataset

The dataset consists of three main tables:

**Customers**
- Customer ID
- Age
- Gender
- Country
- Acquisition channel

**Transactions**
- Transaction ID
- Customer ID
- Product category
- Purchase value
- Discount applied
- Date

**Sessions**
- Session ID
- Customer ID
- Traffic source
- Time on site
- Pages viewed
- Converted (yes/no)

## Tools & Technologies

- Python
- Pandas
- Matplotlib
- Seaborn
- Statistical analysis (correlation, hypothesis testing)
- Visual Studio / Jupyter Markdown

## Key Business Questions

This project investigates several important marketing questions:

1. Which marketing channels generate the most revenue?
2. Do conversion rates differ across traffic sources?
3. How do customer demographics influence purchase behavior?
4. What is the relationship between browsing engagement and purchasing?
5. Do discounts significantly affect transaction value?

## Key Insights

- Email marketing generates the highest total revenue.
- Conversion rates are nearly identical across traffic sources (~13%).
- High-conversion channels do not necessarily produce the highest purchase values.
- Discounts significantly reduce average transaction value.
- Converting users tend to spend less time browsing than non-converting visitors, 
  suggesting high purchase intent.

## Full Analysis

The complete analysis, including code, statistical tests, and visualizations, 
is available here:

➡ **[View the Full Analysis](marketing_statistical_analysis.ipynb )**

## Project Structure

project-folder/
│
├── data/
│   ├── customers.csv
│   ├── transactions.csv
│   └── sessions.csv
│
├── marketing_statistical_analysis.ipynb        # Full statistical analysis and visualizations
├── README.md          # Project overview