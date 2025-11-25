# Customer Behavior & Sales Insights

## SQL Data Analysis Project

## Project Overview

This project analyzes customer purchasing behavior and revenue trends using SQL.  
The dataset includes detailed transaction information such as gender, age, products, pricing, discounts, shipping method, and subscription status.

The project answers 13 business-focused questions, each supported by SQL results and visualizations.

---

## Dataset Fields

Key columns used in this analysis include:

- customer_id
- age
- gender
- item_purchased
- category
- purchase_amount_usd
- discount_applied
- discount_percentage
- shipping_type
- subscription_status
- purchase history for loyalty segmentation

---

# Analysis & Findings

## 1. Revenue by Gender

Finding:  
Male customers generated more total revenue than female customers.

---

## 2. Customers Using Discounts but Spending Above Average

Number of such customers: **21**

---

## 3. Top 5 Products by Highest Average Rating

| Rank | Product |
| ---- | ------- |
| 1    | Gloves  |
| 2    | Sandals |
| 3    | Boots   |
| 4    | Hat     |
| 5    | Skirt   |

---

## 4. Average Purchase Amount by Shipping Type

Sorted from highest to lowest:

1. 2-Day Shipping
2. Express
3. Next Day Air
4. Store Pickup
5. Standard
6. Free Shipping

---

## 5. Spending Comparison Between Subscribers and Non-Subscribers

| Subscription | Customers | Avg Spend | Total Revenue |
| ------------ | --------- | --------- | ------------- |
| Yes          | 1053      | 59.49     | 62,645        |
| No           | 2847      | 59.87     | 170,436       |

Insight:  
Non-subscribers contribute higher total revenue, while average spending per customer is nearly the same.

---

## 6. Top Products Purchased with Discount

### Most purchases with discount applied:

| Product | Purchases |
| ------- | --------- |
| Pants   | 4837      |
| Sweater | 4610      |
| Hat     | 4596      |
| Coat    | 4470      |
| Dress   | 4368      |

### Highest average discount percentage:

| Product  | Discount % |
| -------- | ---------- |
| Hat      | 50%        |
| Sneakers | 49%        |
| Coat     | 49%        |
| Sweater  | 48%        |
| Pants    | 47%        |

---

## 7. Customer Segmentation Based on Loyalty

| Segment             | Count |
| ------------------- | ----- |
| Loyal Customers     | 1375  |
| Returning Customers | 1269  |
| New Customers       | 1179  |
| Unclassified        | 77    |

---

## 8. Top 3 Most Purchased Items in Each Category

### Accessories

| Rank | Product    | Orders |
| ---- | ---------- | ------ |
| 1    | Jewelry    | 171    |
| 2    | Sunglasses | 161    |
| 3    | Belt       | 161    |

### Clothing

| Rank | Product | Orders |
| ---- | ------- | ------ |
| 1    | Blouse  | 171    |
| 2    | Pants   | 171    |
| 3    | Shirt   | 169    |

### Footwear

| Rank | Product  | Orders |
| ---- | -------- | ------ |
| 1    | Sandals  | 160    |
| 2    | Shoes    | 150    |
| 3    | Sneakers | 145    |

### Outerwear

| Rank | Product | Orders |
| ---- | ------- | ------ |
| 1    | Jacket  | 163    |
| 2    | Coat    | 161    |

---

## 9. Most Expensive Items by Category

| Category    | Highest Price | Second Highest |
| ----------- | ------------- | -------------- |
| Accessories | Sunglasses    | Jewelry        |
| Clothing    | Sweater       | Dress          |
| Footwear    | Sandals       | Sneakers       |
| Outerwear   | Jacket        | Coat           |

---

## 10. Top Colors Purchased per Season

### Fall

1. White
2. Turquoise
3. Charcoal

### Spring

1. Red
2. Lavender
3. Brown

### Summer

1. Peach
2. Pink
3. Gold

### Winter

1. Gray
2. Magenta
3. Orange

---

## 11. Subscription Likelihood Among Repeat Buyers

| Subscription | Repeat Buyers |
| ------------ | ------------- |
| No           | 2583          |
| Yes          | 980           |

Insight:  
Most frequent buyers are not subscribed, representing potential for targeted conversion campaigns.

---

## 12. Revenue Contribution by Age Group

| Age Group   | Total Spending |
| ----------- | -------------- |
| Young Adult | 62,143         |
| Middle Aged | 59,197         |
| Adult       | 55,978         |
| Senior      | 55,763         |

Young adults generate the highest overall revenue.

---

# Final Insights

- Male customers generate higher revenue overall.
- Average spending between subscribers and non-subscribers is nearly identical.
- Young adults contribute the largest share of total revenue.
- Many frequent customers are not subscribed, indicating an opportunity to increase membership conversion.
- Seasonal and product purchase trends can aid future inventory and promotional planning.
