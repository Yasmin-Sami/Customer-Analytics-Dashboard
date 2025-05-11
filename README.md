# Customer-Analytics-Dashboard
An interactive Power BI dashboard that provides insights into customer demographics, behavior, income, and marketing engagement to support data-driven decision making


---

## 🧹 Data Cleaning Process (from Power Query Editor)
Here is a detailed explanation of each step taken in Power Query to prepare the data:

1. **Added Age**  
   Calculated the age of each customer.

2. **Changed Data Type**  
   Changed column data types to appropriate formats to ensure correct calculations and visualizations.

3. **Filtered Rows**  
   Removed unwanted rows based on conditions to clean the dataset.

4. **Replaced Values**  
   Standardized the dataset by replacing inconsistent values.

5. **Inserted Sum kid+teen**  
   Created a custom column by adding the number of kids and teens to calculate total dependents per household.

6. **Renamed Columns**  
   Renamed several columns to be more descriptive and user-friendly, making it easier to understand the data model and visuals.

7. **Removed Columns**  
   Deleted irrelevant or redundant columns that were not necessary for analysis to improve performance and readability.

8. **Inserted Year of Dt**  
   Extracted the year from a datetime column to allow year-over-year comparison.

---

## 📊 Dashboard Components Explanation

### 🔹 KPI Cards (Top Section)
- **Sum of Income:** Total income from all customers ($116.79M).
- **Sum of Num of Accepted Campaigns:** Total accepted marketing campaigns (997).
- **Sum of Total Amount Spent:** Total money spent by customers (1M).
- **Sum of Num Web Visits/Month:** Total number of monthly web visits (12K).
- **Avg of Age:** Average customer age (56 years).

---

### 🔹 Visualizations

#### • Sum of Income by Country
Bar chart showing total income contributed by customers from each country. Spain has the highest total income, followed by Saudi Arabia and Canada.

#### • Count of Education
Bar chart representing the number of customers per education level:
- Graduation: Most common (1126)
- PhD and Master: Mid-range
- Basic: Least common (54)

#### • Count of Complain
Shows the number of customers who have or haven’t complained. Majority (2215) have not filed any complaints.

#### • Count of Marital Status
Bar chart indicating the distribution of marital status:
- Married: Most common (1444)
- Single: (792)

#### • Purchase Rate by Channel
Pie chart displaying the channel through which customers made purchases:
- Store (50.19%)
- Website (33%)
- Catalog (21%)

#### • Avg Amount Spent on Each Product
Pie chart showing the average amount spent on different product categories in the last two years:
- Wines: Highest average spending (27.57%)
- Followed by Sweets, Gold, and others.

---

### 🔹 Slicers Used in the Dashboard

#### • Year Slicer
Allows users to filter the data by year. When a year is selected, all charts update to show data only for that year.

#### • Total Sons Slicer
Filters customers based on the number of sons they have. Useful for analyzing how family size impacts spending or behavior.

---

## 📷 Report Preview
![Customer Analytics Dashboard](https://github.com/user-attachments/assets/e3aafc9b-fd85-4999-8233-d7cc8f40ab8a)


