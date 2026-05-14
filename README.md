# Sales & Revenue Analysis Dashboard

> **Thiranex Internship Project — Data Analytics Track**
> Intern: Iqra Raheem | ID: THX-MAY226-5988 | Duration: May–Jun 2026

---

## Overview

A fully interactive, browser-based Sales & Revenue Analysis Dashboard built as part of the Thiranex Data Analytics Internship. The dashboard supports **live CSV data import**, enabling real sales data to be loaded directly from a file — with all charts, KPIs, and tables updating automatically. It also ships with built-in sample data so it works out of the box with no setup required.

---

## Features

| Feature | Description |
|---|---|
| CSV Data Import | Upload any `.csv` file via drag-and-drop or file browser — dashboard updates instantly |
| Sample CSV Download | Download a ready-to-use sample CSV to test the import feature |
| KPI Cards | Total Revenue, Orders, Average Order Value, and Revenue vs Target with live computation |
| Revenue Trend Chart | Monthly actual vs target revenue plotted as an interactive line chart |
| Category Breakdown | Donut chart showing revenue share across product categories |
| Top Products Table | Ranked table of top products with revenue badges and visual share bars |
| Filters | Filter by region and product category — all charts and KPIs update in real time |
| Responsive Design | Works on desktop, tablet, and mobile browsers |

---

## CSV Data Format

The dashboard accepts `.csv` files with the following columns:

| Column | Type | Description |
|---|---|---|
| `month` | Text | Month abbreviation (Jan, Feb, ... Dec) |
| `revenue` | Number | Actual revenue in ₹ for that row |
| `target` | Number | Target revenue in ₹ for that row |
| `orders` | Number | Number of orders |
| `category` | Text | Product category (e.g. Electronics, Clothing) |
| `product` | Text | Product name |
| `units` | Number | Units sold |

**Example row:**
```
Jan,180000,200000,620,Electronics,Wireless Headphones,150
```

> A sample CSV file can be downloaded directly from the dashboard using the **"Download sample CSV"** button.

---

## Tech Stack

- **HTML5** — Structure and layout
- **CSS3** — Styling, responsive grid, transitions
- **JavaScript (Vanilla)** — CSV parsing, data computation, filter interactivity
- **Chart.js v4.4.1** — Line chart and donut chart rendering
- **FileReader API** — Client-side CSV file reading (no server required)
- **Google Fonts** — DM Sans & DM Mono typography

No frameworks. No build tools. No dependencies to install.

---

## Getting Started

### Option 1 — Open locally
1. Clone or download this repository
2. Open `index.html` in any modern browser (Chrome, Firefox, Edge, Safari)
3. The dashboard loads with sample data immediately
4. To use your own data: click **"Choose file"** or drag a `.csv` onto the upload area

```bash
git clone https://github.com/yourusername/sales-dashboard.git
cd sales-dashboard
open index.html
```

### Option 2 — View live demo
> 🔗 [Live Dashboard](https://yourusername.github.io/sales-dashboard)

---

## Dashboard Preview

![Sales & Revenue Dashboard Screenshot](screenshot.png)

---

## How to Use the CSV Import

1. Prepare your `.csv` file with the columns listed above
2. Open the dashboard in your browser
3. Drag and drop the file onto the upload area — **or** click **"Choose file"** to browse
4. All KPIs, charts, and the product table update automatically from your data
5. Use the **Category** filter to slice by product type
6. Click **"Reset to sample"** at any time to return to the built-in demo data

---

## Project Structure

```
sales-dashboard/
│
├── index.html              # Main dashboard (HTML + CSS + JS, all-in-one)
├── screenshot.png          # Dashboard preview image
└── README.md               # Project documentation
```

---

## Learning Outcomes

Through this project, the following data analytics competencies were demonstrated:

| Competency | Implementation |
|---|---|
| Data Import | CSV file upload via drag-and-drop and FileReader API |
| Data Visualization | Line chart (trends), donut chart (categories), bar indicators (products) |
| KPI Tracking | Revenue, orders, AOV, and target variance computed dynamically from data |
| Business Insight Generation | Category breakdowns, product rankings, actual vs target comparison |
| Interactive Filtering | Real-time slicing by category with instant chart and KPI updates |

---

## Internship Details

| Field | Details |
|---|---|
| Organization | Thiranex — Skill Development & Future Tech |
| Role | Intern — Data Analytics |
| Commencement | 15 May 2026 |
| Completion | 14 June 2026 |
| Work Mode | Remote / Project-Based |
| Intern ID | THX-MAY226-5988 |

---

## Contact

**Iqra Raheem**
Data Analytics Intern @ Thiranex
📧 thiranex.internships@outlook.com

---

*All data used in the sample dataset is mock data generated for demonstration purposes only.*
