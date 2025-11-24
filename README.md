
# 🛒 E-Commerce Customer Behavior & Sales Analysis (Turkey)

## 📂 Project Overview

This project provides a comprehensive analysis of Turkish e-commerce customer behavior and sales using a rich, realistic dataset. The goal is to uncover actionable insights for business growth, customer segmentation, churn prediction, and sales optimization. The project is ideal for data science, analytics, and business intelligence learning.

**Key components:**
- **Data Exploration & Cleaning**: Understand the structure, quality, and key statistics of the dataset.
- **Customer Segmentation**: Use clustering (K-Means) to group customers by behavior and value.
- **Churn Analysis**: Build predictive models to identify customers at risk of leaving.
- **Sales & Product Analysis**: Visualize trends, category performance, and device-based behavior.
- **Actionable Insights**: Generate business recommendations based on findings.

All code and analysis are provided in Jupyter Notebooks for reproducibility and learning.


## 📒 Notebooks in This Project

- **customer_behaviour_analysis.ipynb**: Main notebook for data exploration, feature engineering, and customer segmentation (RFM, clustering, etc.).
- **customer_chun_analysis.ipynb**: Churn analysis and prediction using machine learning (KNN, XGBoost, etc.).
- **data_visualization.ipynb**: Visual exploration of sales, customer demographics, product categories, and trends.


## 🎯 Project Use Cases

You can use this project to:
- Segment customers for targeted marketing
- Predict and reduce customer churn
- Analyze sales trends and product performance
- Build recommendation and CLV models
- Optimize pricing and delivery


## 📁 Dataset Structure
The dataset contains **18 columns** with detailed information on orders, customers, products, transactions, and post-purchase metrics.

### Order Information
- **Order_ID**: Unique identifier for each order (ORD_XXXXXX format)
- **Date**: Transaction date (2023-01-01 to 2024-03-26)

### Customer Demographics
- **Customer_ID**: Unique customer identifier (CUST_XXXXX format)
- **Age**: Customer age (18-75 years)
- **Gender**: Customer gender (Male, Female, Other)
- **City**: Customer city (10 major Turkish cities)

### Product Information
- **Product_Category**: 8 categories (Electronics, Fashion, Home & Garden, Sports, Books, Beauty, Toys, Food)
- **Unit_Price**: Price per unit (in TRY/Turkish Lira)
- **Quantity**: Number of units purchased (1-5)

### Transaction Details
- **Discount_Amount**: Discount applied (if any)
- **Total_Amount**: Final transaction amount after discount
- **Payment_Method**: Payment method used (5 types)

### Customer Behavior Metrics
- **Device_Type**: Device used for purchase (Mobile, Desktop, Tablet)
- **Session_Duration_Minutes**: Time spent on website (1-120 minutes)
- **Pages_Viewed**: Number of pages viewed during session (1-50)
- **Is_Returning_Customer**: Whether customer has purchased before (True/False)

### Post-Purchase Metrics
- **Delivery_Time_Days**: Delivery duration (1-30 days)
- **Customer_Rating**: Customer satisfaction rating (1-5 stars)


## 📈 Key Dataset Statistics
- **Total Records**: 5,000 transactions
- **Date Range**: January 2023 - March 2024 (15 months)
- **Average Transaction Value**: ~450 TRY
- **Customer Satisfaction**: 3.9/5.0 average rating
- **Returning Customer Rate**: 60%
- **Mobile Usage**: 55% of transactions

## 🔍 Data Quality

- ✅ No missing values
- ✅ Consistent formatting across all fields
- ✅ Realistic data distributions
- ✅ Proper data types for all columns
- ✅ Logical relationships between features


## 💡 What You'll Learn & Do
- Clean and explore real-world e-commerce data
- Visualize customer and sales patterns
- Segment customers using clustering (K-Means)
- Predict churn with machine learning (KNN, XGBoost)
- Analyze product, device, and city-level trends
- Generate actionable business recommendations


## 🛠️ Technical Details
- **File Format**: CSV (Comma-Separated Values)
- **Encoding**: UTF-8
- **File Size**: ~500 KB
- **Delimiter**: Comma (,)


## 📚 Column Descriptions

| Column Name | Data Type | Description | Example |
|------------|-----------|-------------|---------|
| Order_ID | String | Unique order identifier | ORD_001337 |
| Customer_ID | String | Unique customer identifier | CUST_01337 |
| Date | DateTime | Transaction date | 2023-06-15 |
| Age | Integer | Customer age | 35 |
| Gender | String | Customer gender | Female |
| City | String | Customer city | Istanbul |
| Product_Category | String | Product category | Electronics |
| Unit_Price | Float | Price per unit | 1299.99 |
| Quantity | Integer | Units purchased | 2 |
| Discount_Amount | Float | Discount applied | 129.99 |
| Total_Amount | Float | Final amount paid | 2469.99 |
| Payment_Method | String | Payment method | Credit Card |
| Device_Type | String | Device used | Mobile |
| Session_Duration_Minutes | Integer | Session time | 15 |
| Pages_Viewed | Integer | Pages viewed | 8 |
| Is_Returning_Customer | Boolean | Returning customer | True |
| Delivery_Time_Days | Integer | Delivery duration | 3 |
| Customer_Rating | Integer | Satisfaction rating | 5 |


## 🎓 Learning Outcomes
By working through these notebooks, you will gain hands-on experience in:
- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- Feature engineering for customer analytics
- Clustering and segmentation
- Churn prediction modeling
- Data visualization and reporting
## 📊 Example Analyses Performed

- **Customer Segmentation**: RFM features, K-Means clustering, segment profiling
- **Churn Prediction**: ML pipelines (KNN, XGBoost), accuracy and classification reports
- **Sales & Product Analysis**: Trend lines, category breakdowns, device/city analysis
- **Visualization**: Correlation heatmaps, scatterplots, histograms, time series
## 📑 How to Use

1. Open the Jupyter notebooks in this repository.
2. Run the cells step by step to reproduce the analysis or adapt for your own use case.
3. Use the dataset files (`ecommerce_customer_behavior_dataset.csv` and `ecommerce_customer_behavior_dataset_v2.csv`) as input.
4. Review the code comments and markdown explanations for learning and insights.


## 📝 Citation

If you use this dataset in your research or project, please cite:

```
E-Commerce Customer Behavior and Sales Dataset (2024)
Turkish Online Retail Platform Data (2023-2024)
Available on Kaggle
```


## ⚖️ License

This dataset is released under the **CC0: Public Domain** license. You are free to use it for any purpose.


## 🤝 Contribution

Found any issues or have suggestions? Feel free to provide feedback!


## 📞 Contact

For questions or collaborations, please reach out through Kaggle.

---


---

**Happy Analyzing! 🚀**

*Keywords: e-commerce, customer behavior, sales analysis, Turkish market, retail analytics, machine learning, data science, customer segmentation, predictive analytics*
