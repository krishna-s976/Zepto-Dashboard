# Zepto-Dashboard

This is a **Zepto Business Overview Dashboard** designed to provide a quick summary of the company's sales, inventory, discounts, and delivery performance across different categories and states. Below is a detailed explanation of every section.

---

# Dashboard Objective

The dashboard helps business managers answer questions such as:

* How much revenue has been generated?
* How many product categories and states are covered?
* Which categories generate the highest revenue?
* Which categories receive the highest discounts?
* Which categories take the longest to deliver?
* Which states contribute the most revenue?
* How much inventory is available compared to product prices (MRP)?

---

# 1. Dashboard Header

The purple strip at the top contains:

* **Zepto Logo**
* **Business Overview** title
* **Category Filter (Dropdown)**

### Purpose

The dropdown allows users to filter the entire dashboard by a selected category. Once a category is selected, every chart updates automatically.

---

# 2. KPI Cards

These cards provide an overall business summary.

### Revenue

**Value:** **122M**

This represents the **total revenue** generated from all products.

Formula:

```
Revenue = SUM(revenue)
```

Interpretation:

* Total business revenue equals **122 Million**.

---

### Category

**Value:** **14**

This shows the total number of product categories.

Examples:

* Cooking Essentials
* Ice Cream
* Chocolates
* Packaged Food
* Dairy
* Beverages

Formula

```
Distinct Count(Category)
```

---

### State

**Value:** **28**

Shows the total number of Indian states included in the dataset.

Formula

```
Distinct Count(State)
```

---

# 3. Revenue by State (Map)

This map visualizes revenue across India.

### What it shows

Each highlighted state contributes to the company's total revenue.

Darker shades indicate higher revenue.

Purpose:

* Identify high-performing states
* Compare regional performance
* Support expansion planning

Example insights:

* Maharashtra may contribute more revenue than Goa.
* Uttar Pradesh may have higher sales than Himachal Pradesh.

---

# 4. Sum of Discount Percent by Category

This horizontal bar chart compares the **total discount percentage** offered across categories.

### X-axis

Total Discount %

### Y-axis

Product Categories

Example

Cooking Essentials → Highest discount

Munchies → High discount

Personal Care → Lower discount

Purpose

* Understand promotional strategies
* Identify categories receiving aggressive discounts

Business Insight

High discounts can:

* Increase sales
* Reduce profit margin

Managers can evaluate whether discounts are producing enough revenue.

---

# 5. Revenue by Category

This is one of the most important charts.

### X-axis

Revenue

### Y-axis

Category

It ranks categories from highest revenue to lowest.

From the dashboard:

Highest revenue comes from:

* Chocolates &...
* Ice Cream &...
* Packaged Food

Lowest revenue:

* Fruits & Vegetables
* Health & Hygiene

Purpose

Identify best-selling product categories.

Business Decision

* Increase inventory for top-selling products.
* Improve marketing for low-performing categories.

---

# 6. Available Quantity and MRP by Category

This clustered column chart compares two measures:

* Available Quantity
* MRP (Maximum Retail Price)

### Purple Bars

Available Quantity

### Gray Bars

MRP

Purpose

Shows whether inventory levels are aligned with product pricing.

Example

A category may have:

* High inventory
* Low MRP

Another category may have:

* Low inventory
* High MRP

This helps inventory managers maintain optimal stock levels.

---

# 7. Average Delivery Time by Category

This horizontal bar chart displays the average delivery time for each product category.

### X-axis

Average Delivery Time

### Y-axis

Category

From the dashboard:

Cooking Essentials

Longest delivery time

Munchies

Also relatively high

Beverages

Lowest delivery time

Purpose

Monitor logistics efficiency.

Business Insight

Categories with higher delivery times may require:

* More warehouses
* Better inventory distribution
* Faster delivery partners

---

# Dashboard Filters

The dropdown in the top-right corner filters all visuals simultaneously.

For example:

Selecting **Ice Cream**

Updates:

* Revenue card
* State map
* Revenue chart
* Delivery time chart
* Discount chart
* Inventory chart

This enables category-specific analysis.

---

# Key Business Insights

Based on this dashboard:

* **Total Revenue:** **122M**, indicating strong overall sales.
* **Business Reach:** Operations span **28 states** and **14 product categories**, showing a broad market presence.
* **Top Revenue Categories:** Chocolates, Ice Cream, and Packaged Food contribute the highest sales.
* **Highest Discounts:** Cooking Essentials and Munchies receive the largest cumulative discounts, suggesting promotional focus.
* **Delivery Performance:** Cooking Essentials has the longest average delivery time, highlighting an area for logistics improvement.
* **Inventory Monitoring:** The comparison of available quantity and MRP helps identify categories where stock levels may not align with product value.

---

# Overall Dashboard Summary (Interview Ready)

> This Zepto Business Overview Dashboard provides a comprehensive view of business performance by tracking key metrics such as total revenue, number of product categories, and state coverage. It visualizes revenue distribution across states and product categories, analyzes discount strategies, compares inventory levels with MRP, and monitors average delivery time by category. Interactive filters allow users to explore specific categories, enabling managers to identify top-performing products, optimize inventory, improve logistics, and make informed business decisions.
