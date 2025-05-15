# Health Tracking Dashboard

An interactive R Shiny dashboard built to empower retail businesses with data-driven insights through dynamic visualizations and statistical analysis.

---

## Project Description

This project enables deep exploration of sales patterns, category performance, and metric correlations in a retail setting. Built using R Shiny and advanced data visualization tools, it simplifies decision-making for managers, analysts, and executives.

---

## Key Features

### 1. Dynamic Data Visualization
- Interactive scatter plot with real-time filtering
- Category color-coding (selected vs others)
- Automatic outlier detection
- Trend line overlay

### 2. Category Performance Analysis
- One-click filtering by product category
- Compare category vs overall performance
- Identify top and bottom performers

### 3. Statistical Insights Engine
- Metrics calculated on the fly:
  - Mean, standard deviation, skewness
  - Metric correlation
- Trend indicators (positive/neutral/negative)

### 4. Metric Correlation Explorer
- Correlation matrix for:
  - Sales revenue, units sold, profit, customer counts
- Color-coded intensity to indicate correlation strength

---

## 📈 Business Insights

### 🔹 Sales Performance
- Spot top-performing categories
- Detect seasonal patterns & outliers

### 🔹 Inventory Optimization
- Identify products needing restock or promotion
- Reveal stock optimization timing

### 🔹 Marketing Effectiveness
- Connect campaigns to revenue spikes
- Identify valuable customer segments

### 🔹 Operational Efficiency
- Discover periods of volatility
- Flag potential data issues

---

## Technical Implementation

### R Packages Used
- `shiny` – interactive UI
- `ggplot2` – visualizations
- `plotly` – interactive charts
- `dplyr` – data manipulation
- `corrplot` – correlation matrix visualization

### 📊 Dashboard Components

#### Control Panel
- Category dropdown
- Metric and date range selectors
- Trigger update button

#### Visualization Area
- Scatter plots with overlays
- Statistical summaries
- Correlation matrix

####  Insights Section
- Key findings
- Actionable recommendations
- Visual performance cues

---

## Business Value

### For Retail Managers
- Inventory and promotion planning
- Trend-driven decision making

### For Data Teams
- Self-service dashboarding
- Reduced custom report requests

### For Executives
- Strategic overview
- Performance tracking and initiative impact

---

## Sample Use Cases

| Role              | Question                                                   | Dashboard Feature Used                     |
|-------------------|------------------------------------------------------------|--------------------------------------------|
| **Category Manager** | "Which products should we promote?"                         | Category performance comparison            |
| **Inventory Specialist** | "When to increase stock for electronics?"                   | Seasonal sales analysis                     |
| **Marketing Director** | "What drives revenue most?"                                 | Correlation matrix                         |
| **Store Manager**  | "Any unusual transactions this month?"                     | Outlier visualization                      |

---

## 🖥️ Live Preview / Demo

_(Optional – Add link if deployed)_

---

## Folder Structure

```plaintext
Retail-Sales-Analytics-Dashboard
│
├── app.R                      # Main Shiny app
├── www/                      # Custom CSS, JS
├── data/                     # Sample datasets
└── README.md                 # Project overview
