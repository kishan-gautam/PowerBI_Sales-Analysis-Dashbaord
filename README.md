# 📊 Tech Products Sales Dashboard — Power BI

![Dashboard Preview](https://github.com/kishan-gautam/PowerBI_Sales-Analysis-Dashbaord/blob/main/Sales-Dashboard%20Picture.png)

---

## 📌 Overview
An interactive Sales Performance Dashboard built using Power BI,
analyzing tech product sales across multiple countries and product
categories. The dashboard provides actionable business insights
to support data-driven decision making.

---

## 🗄️ Dataset

### customers.csv — 12 records
| Column | Description |
|---|---|
| `customer_id` | Unique customer identifier |
| `first_name` | Customer first name |
| `last_name` | Customer last name |
| `country` | Customer country |
| `state` | Customer state |
| `city` | Customer city |
| `score` | Customer score/rating |

### orders.csv — 100 records
| Column | Description |
|---|---|
| `order_id` | Unique order identifier |
| `order_date` | Date of order |
| `customer_id` | Links to customers table |
| `product_name` | Name of product sold |
| `product_category` | Category of product |
| `quantity` | Units ordered |
| `sales` | Sales value in USD |

---

## 🔗 Data Model
- `orders` table connects to `customers` table via `customer_id`
- Relationship type: **Many to One**

---

## 🛠️ Tools & Techniques Used

| Tool/Technique | Purpose |
|---|---|
| **Power BI Desktop** | Dashboard building |
| **Power Query** | Data cleaning and transformation |
| **DAX** | Custom calculations and measures |
| **CSV files** | Raw data source |

---

## 📊 Dashboard Features

| Feature | Description |
|---|---|
| **KPI Cards** | Total Orders, Total Customers, Total Sales |
| **Line Chart** | Sales trend over time |
| **Bar Chart** | Sales by product name |
| **Donut Chart** | Sales by product category |
| **Timeline Slicer** | Filter data by date range |
| **Country Filter** | Filter by China, Germany, India, US |
| **Category Filter** | Filter by product category |
| **Business Insights** | 3 actionable insight text boxes |

---

## 💡 Key Business Insights

**1. Sales Trend**
> Sales show fluctuations with a major peak around late period,
> suggesting seasonal demand or promotional impact.
> Similar campaigns can be repeated to boost sales.

**2. Top Category**
> Smartphones generate the highest sales (~51%), indicating
> strong customer demand. The company should prioritize
> smartphone inventory and marketing.

**3. Top Product**
> Dell XPS 15 is the top-selling product, contributing the most
> revenue. This product should be promoted further or
> bundled with accessories.

**4. Country Performance**
> Sales vary by country, indicating different market performance.
> Targeted strategies should be applied for underperforming regions.

---

## 📁 Files

| File | Description |
|---|---|
| `dashboard.png` | Screenshot of final dashboard |
| `customers.csv` | Customer data — 12 records |
| `orders.csv` | Orders data — 100 records |
| `tech_sales_dashboard.pbix` | Power BI dashboard file |
| `README.md` | Project documentation |

---

## 🚀 How to Use
1. Download all files
2. Open `tech_sales_dashboard.pbix` in **Power BI Desktop**
3. If data doesn't load — go to **Transform Data → Data Source Settings**
4. Update the path to where you saved the CSV files
5. Click **Refresh** — dashboard will populate automatically

---

## 🎯 Product Categories Analyzed
- 💻 Laptop
- 📱 Smartphone
- 📱 Tablet
- 🏠 Smart Home
- 🎧 Accessory

## 🌍 Countries Analyzed
- 🇺🇸 United States
- 🇨🇳 China
- 🇩🇪 Germany
- 🇮🇳 India

---

*Created by [Kishan Gautam](https://github.com/kishan-gautam)*
