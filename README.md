# **E-commerce Sales Performance Analysis**

## **Introduction**
E-commerce businesses generate large volumes of transactional data, including orders, customers, employees, products, and sales channels. Analyzing this data is essential for identifying top-performing employees, loyal customers, seasonal trends, pricing strategies, and areas for operational improvement.

This project leverages **SQL-based analysis** to evaluate sales performance across multiple dimensions, including employees, customers, products, regions, and time periods. The analysis focuses on **Northwind Traders**-style data, which includes orders, order details, products, categories, customers, and employees.

The objective is to answer critical business questions such as:
- Who are the top employees driving revenue?
- Which customers generate the most revenue?
- What seasonal or monthly trends exist in sales performance?
- How do discounts, pricing, and product categories affect profitability?
- Which products and regions contribute the most to revenue growth?

---

## **About the Dataset**
The dataset consists of multiple interrelated tables:
- **Orders:** Contains order date, customer ID, employee ID, and shipping details.
- **OrderDetails:** Includes quantity, unit price, and discounts for each product in an order.
- **Customers:** Holds customer information such as name, location, and country.
- **Employees:** Lists sales representatives handling orders.
- **Products:** Contains product names, categories, and unit prices.
- **Categories:** Groups products into categories for analysis.

### **Key Attributes:**
- `OrderID`, `OrderDate`, `CustomerID`, `EmployeeID`
- `ProductID`, `Quantity`, `UnitPrice`, `Discount`
- `CustomerName`, `City`, `Country`
- `CategoryName`

---

## **Analysis Questions (EDA Questions)**
The SQL queries address the following key questions:

1. **Total Sales by Employee**  
   Which employees generate the highest total sales?  

2. **Top 5 Customers by Revenue**  
   Who are the top revenue-generating customers?

3. **Monthly Sales Trend (1997)**  
   How does monthly sales fluctuate in a given year?

4. **Order Fulfillment Time**  
   What is the average time taken to fulfill an order for each employee (based on estimated shipping days)?

5. **Sales for Customers in London**  
   Which London-based customers generate the most sales?

6. **Customers with Multiple Orders on the Same Date**  
   Identify customers placing multiple orders on the same day.

7. **Average Discount per Product**  
   Which products receive the highest average discount?

8. **Products Ordered by Each Customer**  
   List all products ordered by each customer along with total quantities.

9. **Employee Sales Ranking**  
   Rank employees based on total revenue generated.

10. **Sales by Country and Category**  
    How do product categories perform across different countries?

11. **Year-over-Year Sales Growth**  
    Calculate percentage growth in sales for each product across years.

12. **Order Quantity Percentile**  
    Determine percentile rank of each order based on total quantity.

13. **Products Never Reordered**  
    Identify products purchased only once (never reordered).

14. **Most Valuable Product by Revenue in Each Category**  
    Find the top revenue-generating product in every category.

15. **Complex Orders Analysis**  
    Identify orders exceeding $100 in value and containing a product with at least a 5% discount.

---

## **Findings**

### ✅ **1. Top Employees by Sales**
- Certain employees significantly outperform others in total sales, indicating the importance of targeted performance incentives and training.

### ✅ **2. Top 5 Customers**
- The top 5 customers contribute a large share of total revenue, suggesting the need for **customer loyalty programs** and **personalized marketing** for these accounts.

### ✅ **3. Seasonal & Monthly Trends**
- Sales fluctuate by month, with some months showing consistent dips. This suggests an opportunity to implement **seasonal promotions** and **dynamic pricing strategies**.

### ✅ **4. Discounts Impact**
- Products with higher average discounts may erode profit margins. Companies need to **review discount policies** and balance them against profitability.

### ✅ **5. Category & Geographic Insights**
- Some categories dominate in specific countries, indicating **regional demand variations** and potential for **localized campaigns**.

### ✅ **6. Repeat Orders & Loyalty**
- Customers placing multiple orders on the same date represent **high engagement** opportunities and can be targeted for **subscription models**.

### ✅ **7. High Revenue Products**
- A few products contribute disproportionately to revenue, suggesting the importance of **stock prioritization** and **premium variant launches**.

---

## **Strategic Recommendations**

### ✅ 1. **Employee Performance Management**
- Reward top-performing employees through **bonuses and recognition programs**.
- Provide **sales training and mentorship** to lower-performing employees.

### ✅ 2. **Loyalty and Retention Programs**
- Design **VIP programs** for top customers.
- Offer **exclusive deals and early access** to high-value customers.

### ✅ 3. **Seasonal Campaigns**
- Launch **flash sales** and **holiday discounts** in low-performing months.
- Use **predictive analytics** for inventory stocking during peak months.

### ✅ 4. **Optimize Discount Policies**
- Limit excessive discounts on high-demand products.
- Introduce **volume-based discounting** for wholesale buyers instead of flat discounts.

### ✅ 5. **Category and Regional Strategy**
- Focus marketing efforts on **high-performing categories by region**.
- Expand distribution networks in **high-revenue countries**.

### ✅ 6. **Product Strategy**
- Bundle **high-margin products** with popular items.
- Promote **top-performing products** aggressively through online and offline channels.

### ✅ 7. **Data-Driven Decision-Making**
- Build **real-time dashboards** for monitoring sales KPIs.
- Implement **AI-driven forecasting** to predict demand and optimize inventory.

---

## **Conclusion**
The SQL-driven analysis of the e-commerce dataset provides valuable insights into **employee productivity**, **customer behavior**, **seasonal patterns**, and **product performance**. By implementing the recommended strategies, businesses can achieve **higher profitability**, **stronger customer loyalty**, and **better resource allocation**.
