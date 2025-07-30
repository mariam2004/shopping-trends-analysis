# 🛍️ Shopping Trends Analysis Dashboard

An end-to-end data analytics project to explore customer behavior and purchasing patterns using SQL Server, Python, and Power BI.

---

## 📦 Project Workflow

1. **Data Source & Extraction**
   - Connected to a SQL Server database using **SQL Server Management Studio (SSMS)**.
   - Queried and imported data using Python with the `pyodbc` package.

2. **Exploratory Data Analysis (EDA) & Preprocessing**
   - Cleaned and analyzed data using:
     - `pandas`, `numpy` for data handling  
     - `matplotlib`, `seaborn`, `plotly.express` for visualizations

3. **Customer Segmentation**
   - Applied **KMeans Clustering** to segment customers based on purchasing patterns.
   - Preprocessing used:
     - `StandardScaler`, `OneHotEncoder`
     - `ColumnTransformer` for pipelines
     - `PCA` for cluster visualization in 2D space
     - `silhouette_score` for validation

4. **Dashboard Creation**
   - Built an **interactive Power BI dashboard** to present insights.
   - Integrated slicers, KPIs, and multiple chart types.

---

## 📊 Dashboard Structure

### 🔹 1. Customer Overview

**KPIs:**
- Avg Purchase Amount 💸  
- Avg Age 🎂  
- Gender Distribution ⚥

**Visuals:**
- Pie Chart: Gender Distribution  
- Histogram: Age Distribution  
- Bar Chart: Customers by Frequency of Purchases  
- Donut Chart: Subscription Status %

---

### 🔹 2. Purchase Behavior

**KPIs:**
- Total Sales 💰  
- Average Review Rating ⭐  
- Top Category 🛍️  
- Most Used Shipping Type 🚚

**Visuals:**
- Bar Chart: Sales by Category  
- Bar Chart: Sales by Shipping Type  
- Line/Area Chart: Purchase Amount vs Age  
- Stacked Bar: Shipping Type by Gender

---

### 🔹 3. Seasonality & Timing

**KPIs:**
- Best Performing Season 🌸☀🍁❄  
- Sales Distribution by Season 📈

**Visuals:**
- Pie Chart: Sales by Season  
- Stacked Bar: Shipping Type by Season

---

## 🧠 Tools & Libraries Used

| Tool | Purpose |
|------|---------|
| **SQL Server Management Studio** | Data extraction |
| **Python** | Data cleaning & modeling |
| `pandas`, `numpy` | Data wrangling |
| `matplotlib`, `seaborn`, `plotly.express` | Visualization |
| `scikit-learn` | Clustering & preprocessing |
| **Power BI** | Dashboard development |

---

## 📁 Folder Structure

```bash
├── data/                # shopping_trends.csv
├── notebooks/           # shoptrendsDS.ipynb
├── dashboard/           # shopping trends dashboard.pbix
├── README.md            # Project overview
