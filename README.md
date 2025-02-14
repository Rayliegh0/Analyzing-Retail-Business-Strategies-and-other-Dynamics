# Digital Analytics for Enhancing E-Commerce Business Performance

---

## Objective
This project aims to analyze customer behavior, sales trends, and product performance to provide actionable insights for optimizing sales, inventory, and marketing strategies in the e-commerce domain.

---

## Business Context
This analysis focuses on enhancing customer experience, increasing sales, and identifying growth opportunities using retail data from **September 2021 to October 2023**. It examines sales, customer demographics, product details, order payments, store information, and customer reviews across **98.68K orders** from **534 stores** and **13 product categories**.

---

## Data Sources
- **Sales Data**: Order details, payments, and product categories.
- **Customer Data**: Demographics and transaction history.
- **Store Data**: Information from 534 stores.
- **Customer Reviews**: Customer sentiment insights.

### Data Overview
- **Orders**: 98.68K total orders
- **Stores**: 534 stores
- **Product Categories**: 13 categories
- **Customer Segments**: High, medium, and low-value customers

---

## Analysis Performed
1. **Data Cleaning and Preparation:**
   - Removed duplicates from multiple tables (e.g., OrderPayments, OrderReview_Ratings, Stores_Info).
   - Recalculated Total Amount in Orders to ensure accuracy.

2. **Customer Segmentation:**
   - Classified customers into high, medium, and low-value segments based on revenue.
   - Performed RFM segmentation to categorize customers into Premium, Gold, Silver, and Standard segments.

3. **Sales & Performance Analysis:**
   - Evaluated sales performance by region, store (e.g., ST103), and product categories (e.g., Toys & Gifts).
   - Conducted Pareto Analysis to identify the top-performing categories.

4. **Behavioral Insights:**
   - Analyzed payment methods, discount-seeking behaviors, and channel usage patterns.
   - Examined behavior of one-time buyers vs. repeat buyers.
   - Investigated discount seekers vs. non-discount seekers.
   - Assessed customer preferences for channels, stores, categories, and payment methods.

5. **Customer Satisfaction Analysis:**
   - Calculated average ratings by category, location, store, product, and month.
   - Identified top-rated and low-rated categories and products.

6. **Sales Trends & Seasonality:**
   - Analyzed sales trends by month, day of the week, quarter, and year.
   - Evaluated seasonal patterns in sales (weekdays vs. weekends).

7. **Category & Product Behavior:**
   - Analyzed category penetration and cross-category sales patterns.
   - Identified the most popular category during the first purchase.
   - Conducted cross-selling analysis to find products frequently bought together.

---

## Key Insights
1. **Store ST103**: Showed significant sales growth, making it a model for other stores.
2. **Customer Segmentation**:
   - **High-Value Customers**: Small base but high profitability.
   - **Low-Value Customers**: High growth potential.
3. **Discount-Seeking Behaviors**: Identified significant discount-seeking behavior, useful for targeted marketing.
4. **Top Product Categories**:
   - **Toys & Gifts** and **Home Appliances** are the highest-performing categories.
   - High cross-selling potential between these categories.

---

## Recommendations
1. **Replicate Successful Strategies**: Use the strategies from **ST103** across other stores.
2. **Customer Conversion**:
   - Implement loyalty programs and personalized offers to increase the lifetime value of low-value customers.
3. **Targeted Campaigns**:
   - Develop customized campaigns for discount seekers and non-seekers.
4. **Cross-Selling Opportunities**:
   - Promote cross-selling between high-demand categories (e.g., Toys & Gifts and Home Appliances).
5. **Payment Method Incentives**:
   - Offer incentives for preferred payment methods (e.g., credit cards) to boost customer retention.

---

## Tools Used
- **SQL**: Data extraction, merging, and analysis from multiple tables.
- **Power BI**: Interactive dashboards and data visualizations.
- **Excel**: Initial data exploration and manipulation.
- **PowerPoint**: Presentation of insights and strategic recommendations.

---

## Challenges Faced
- **Data Cleaning**:
  - Removed duplicates and ensured data consistency across multiple tables.
  - Recalculated total amounts to maintain accuracy in financial metrics.
- **High-Value Customer Base**:
  - Small size of high-value customers posed challenges in driving overall profitability.
  - Focused on converting low and medium-value customers to high-value segments.

---

## How to Use the Project
1. **Clone the Repository**:
   ```sh
   git clone https://github.com/your-username/Digital-Analytics-for-Enhancing-E-Commerce-Business-Performance.git
   ```
2. **Import Data**:
   - Ensure the data files are placed in the working directory.
   - The dataset should include tables such as `Customers`, `OrderPayments`, `OrderReview_Ratings`, `Orders`, `ProductsInfo`, and `Stores_Info`.

3. **Execute the SQL Scripts**:
   - Import the tables into a database management system (e.g., SQL Server or MySQL).
   - Run the SQL scripts sequentially for data cleaning, transformation, and analysis.

4. **Visualizations**:
   - Load the Power BI dashboard to explore the insights visually.

---

## Future Enhancements
1. **Predictive Analytics**:
   - Implement predictive models to forecast sales trends and customer behavior.
2. **Real-Time Data Integration**:
   - Integrate real-time data streams for up-to-date analytics and decision-making.
3. **Enhanced Customer Segmentation**:
   - Apply advanced clustering techniques for more granular customer segmentation.
4. **Recommendation System**:
   - Build a recommendation engine for personalized product suggestions.

---

## Project Impact
This analysis provides strategic insights into customer behavior, sales patterns, and market dynamics. It empowers e-commerce businesses to:
- **Enhance Customer Experience** by understanding preferences and purchasing patterns.
- **Optimize Inventory** based on seasonal trends and product performance.
- **Boost Sales & Profitability** by implementing targeted marketing and cross-selling strategies.
- **Drive Customer Loyalty** through personalized offers and loyalty programs.

---

This project provides a comprehensive solution for understanding digital analytics and e-commerce market dynamics, helping businesses make data-driven strategic decisions to enhance business performance.
