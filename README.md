# 🛒 Blinkit Sales Analytics

<div align="center">

![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-Analysis-CC2927?style=for-the-badge&logo=microsoftsqlserver&logoColor=white)
![Status](https://img.shields.io/badge/Status-Complete-success?style=for-the-badge)

**A comprehensive retail analytics project analyzing Blinkit's sales performance, outlet metrics, and product insights using Power BI and SQL.**

[Dashboard Preview](#-dashboard-preview) • [Key Insights](#-key-insights) • [Dataset](#-dataset) • [Analysis](#-analysis)

</div>

---

## 🎯 Project Overview

**Blinkit** (formerly Grofers) is India's leading quick-commerce platform delivering groceries and essentials in minutes. This project analyzes their retail data to uncover:

- 📊 **Sales Performance** – Revenue trends across outlets and products
- 🏪 **Outlet Analytics** – Performance by location, size, and type
- 🥗 **Product Insights** – Category-wise sales and fat content preferences
- ⭐ **Customer Ratings** – Quality metrics across the product range

---

## 📈 Dashboard Preview

<div align="center">

| KPI Highlights |
|----------------|
| 💰 **Total Sales Analysis** |
| 📦 **Item Performance Metrics** |
| 🏬 **Outlet Comparison** |
| 📍 **Location-wise Breakdown** |

</div>

### Dashboard Features

```
┌─────────────────────────────────────────────────────────────────┐
│  📊 BLINKIT SALES DASHBOARD                                     │
├─────────────────────────────────────────────────────────────────┤
│                                                                 │
│  ┌──────────────┐  ┌──────────────┐  ┌──────────────┐           │
│  │ Total Sales  │  │ Avg Sales    │  │ Items Sold   │           │
│  │   $1.20M     │  │    $141      │  │    8,523     │           │
│  └──────────────┘  └──────────────┘  └──────────────┘           │
│                                                                 │
│  ┌─────────────────────────────────────────────────────┐        │
│  │  Sales by Outlet Type        │  Sales by Location   │        │
│  │  ████████████ Supermarket T1 │  ████ Tier 1         │        │
│  │  ████████ Supermarket T2     │  ████████ Tier 2     │        │
│  │  ████ Grocery Store          │  ████████████ Tier 3 │        │
│  └─────────────────────────────────────────────────────┘        │
│                                                                 │
│  ┌─────────────────────────────────────────────────────┐        │
│  │  Fat Content Analysis   │  Item Type Distribution   │        │
│  │  ○ Low Fat: 65%         │  🥬 Fruits & Vegetables   │        │
│  │  ○ Regular: 35%         │  🥫 Canned Goods          │        │
│  │                         │  ❄️ Frozen Foods          │        │
│  └─────────────────────────────────────────────────────┘        │
└─────────────────────────────────────────────────────────────────┘
```

---

## 🔑 Key Insights

### Sales Distribution

| Metric | Finding |
|--------|---------|
| **Top Outlet Type** | Supermarket Type 1 drives highest revenue |
| **Best Location Tier** | Tier 3 cities show strong sales volume |
| **Popular Fat Content** | Low Fat products lead consumer preference |
| **Outlet Age Impact** | Established outlets (2000-2010) perform better |

### 🏆 Top Performing Categories

| Rank | Item Type | Performance |
|------|-----------|-------------|
| 🥇 | Fruits and Vegetables | Highest Volume |
| 🥈 | Snack Foods | High Margins |
| 🥉 | Household Items | Consistent Sales |
| 4️⃣ | Frozen Foods | Growing Segment |
| 5️⃣ | Health and Hygiene | Steady Demand |

---

## 📂 Dataset

**File:** `blinkit.json` (119,000+ records)

### Data Dictionary

| Column | Description | Example |
|--------|-------------|---------|
| `Item Identifier` | Unique product ID | FDX32, NCB42 |
| `Item Type` | Product category | Fruits and Vegetables |
| `Item Fat Content` | Fat classification | Low Fat, Regular |
| `Item Weight` | Product weight (lbs) | 15.1, 11.8 |
| `Item Visibility` | Display allocation % | 0.10, 0.008 |
| `Outlet Identifier` | Store ID | OUT049, OUT018 |
| `Outlet Size` | Store size category | Small, Medium, High |
| `Outlet Location Type` | City tier | Tier 1, Tier 2, Tier 3 |
| `Outlet Type` | Store format | Supermarket Type1, Grocery Store |
| `Outlet Establishment Year` | Year founded | 1998-2022 |
| `Total Sales` | Revenue generated | 145.47, 115.34 |
| `Rating` | Customer rating | 1-5 |

---

## 🔍 Analysis Dimensions

### By Outlet Characteristics

```
┌─────────────────────────────────────────────────────┐
│                   OUTLET ANALYSIS                   │
├─────────────────────────────────────────────────────┤
│                                                     │
│  📏 BY SIZE          🏪 BY TYPE                    │
│  ├── Small           ├── Supermarket Type 1         │
│  ├── Medium          ├── Supermarket Type 2         │
│  └── High            ├── Supermarket Type 3         │
│                      └── Grocery Store              │
│                                                     │
│  📍 BY LOCATION      📅 BY ESTABLISHMENT YEAR      │
│  ├── Tier 1          ├── 1998-2005 (Mature)         │
│  ├── Tier 2          ├── 2006-2015 (Growth)         │
│  └── Tier 3          └── 2016-2022 (New)            │
│                                                     │
└─────────────────────────────────────────────────────┘
```

### By Product Attributes

| Dimension | Categories |
|-----------|------------|
| **Fat Content** | Low Fat, Regular, LF |
| **Item Types** | 16 categories including Dairy, Snacks, Beverages |
| **Visibility** | Product shelf space allocation |
| **Weight** | Product size variations |

---

## 🛠️ Tools & Technologies

<div align="center">

| Tool | Purpose |
|------|---------|
| ![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat-square&logo=powerbi&logoColor=black) | Interactive Dashboard |
| ![SQL](https://img.shields.io/badge/SQL-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white) | Data Analysis Queries |
| ![Excel](https://img.shields.io/badge/Excel-217346?style=flat-square&logo=microsoftexcel&logoColor=white) | Data Preprocessing |

</div>

---

## 🚀 Getting Started

### Prerequisites
- Power BI Desktop
- SQL Server / Any SQL Database
- JSON support for data import

### Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/Shubham-Raj-1503/blinkit-analysis.git
   ```

2. **Import the data**
   ```sql
   -- Load blinkit.json into your database
   -- Or directly import into Power BI
   ```

3. **Open the dashboard**
   - Launch `Blinkit Analysis.pbix` in Power BI Desktop
   - Refresh data connections if needed

---

## 📊 Business Recommendations

| Strategy | Target | Expected Impact |
|----------|--------|-----------------|
| **Expand Tier 3 Presence** | New outlet locations | Capture growing market |
| **Optimize Low Fat Range** | Product assortment | Align with health trends |
| **Supermarket T1 Replication** | Store format | Scale top performer model |
| **Visibility Optimization** | Shelf placement | Boost underperforming items |

---

## 📁 Project Structure

```
📦 blinkit-analysis
├── 📊 Blinkit Analysis.pbix      # Power BI Dashboard
├── 📄 Query Doc.docx             # SQL Queries Documentation  
├── 📋 blinkit.json               # Raw Dataset (119K+ records)
├── 🎨 Blinkit Analysis.key       # Keynote Presentation
└── 📖 README.md                  # Project Documentation
```

---

## 🔮 Future Enhancements

- [ ] Time-series forecasting for sales prediction
- [ ] Customer segmentation analysis
- [ ] Inventory optimization recommendations
- [ ] Real-time dashboard with live data feeds
- [ ] Machine learning for demand prediction

---

## 🤝 Contributing

Contributions are welcome! Feel free to submit issues or pull requests.

---

## 📄 License

This project is licensed under the MIT License.

---

<div align="center">

**Built with 💛 for retail analytics**

![Blinkit](https://img.shields.io/badge/Blinkit-FFDC00?style=for-the-badge)

*Delivering insights in minutes!* ⚡

</div>
