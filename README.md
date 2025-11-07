
#  Customer Marketing Insights Dashboard

##  Overview

The **Customer Marketing Insights Dashboard** is built using **Power BI** to analyze customer behavior, spending trends, and marketing effectiveness.  

It enables data-driven decision-making by providing insights into key customer segments, total spending, and engagement across multiple channels.

---

##  Key Metrics

| Metric | Description |

|---------|--------------|
| **Total Customers** | 2,240 |

| **Total Spending** | 1M |

| **Average Spending** | 605.80 |

| **Response Rate** | 0.15 |

These KPIs summarize the overall performance of the marketing and sales data.


---

##  Dashboard Insights
- **Marital Status Distribution:** Married customers form the largest group (38.57%), followed by Together and Single categories.
- 
- **Spending by Year of Birth:** Customers born between 1950–1980 have the highest total spending, representing a mature, high-value segment.
- 
- **Purchase Channels:** Strong correlation between Store, Catalog, and Web Purchases — showing multi-channel engagement.
-  
- **Product Correlation:** Higher Wine spending aligns with higher Fruit spending, indicating premium buying preferences.
-  
- **Recency Effect:** “Recent” customers contribute more spending than “Old” customers — suggesting effective recent marketing campaigns.

---

## ⚙️ Technical Implementation

###  DAX Measures

Key DAX formula used:

```DAX
Response Rate = DIVIDE(SUM(Marketing[Responses]), COUNT(Marketing[CustomerID]), 0)
```
This measure calculates customer engagement by dividing the total number of responses by the total number of customers.

###  Visuals Used

- KPI Cards – Display Total Customers, Total Spending, Average Spending, and Response Rate
- 
- Bar Chart – Store vs. Web/Catalog Purchases
- 
- Pie Chart – Customers by Marital Status
- 
- Line Chart – Total Spending by Year of Birth
- 
- Scatter Plot – Relationship between Wine and Fruit Spending  

---

##  Interactive Features

**Slicers added for:**

- Marital Status
- 
- Recency Bucket (Moderate, Old, Recent)
-  
- Education Level  

These slicers allow users to explore data dynamically and filter insights by customer attributes.

---

##  Conditional Formatting & Design

- Applied conditional formatting to highlight high-performing customer segments.
-  
- Color-coded charts for clear differentiation between demographic and spending categories.
-  
- Clean, dashboard-style layout optimized for readability and analysis.

---

##  Conclusion

The **Customer Marketing Insights Dashboard** consolidates key metrics and customer patterns into one interactive report.  

It helps marketing teams:

- Identify top-performing customer segments
-  
- Track multi-channel purchase trends
- 
- Refine campaign strategies based on engagement
- 
- Make informed, data-driven business decisions  

---

##  Project Information

**Tool Used:** Microsoft Power BI  

**Data Source:** Customer Marketing Dataset 

**Author:** *Rohan Ingle*  

**Date:** November 2025  


