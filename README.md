# Portfolio Data Analytics Project: E-commerce Retail & Netflix Catalog Analysis

Welcome to my end-to-end data analytics repository! This project showcases advanced exploratory data analysis (EDA), automated data cleaning pipelines, and structured executive-level dashboard engineering using Python in a Jupyter Notebook environment. 

The project evaluates two distinct corporate datasets: a transactional E-commerce dataset and a categorical Netflix entertainment catalog.

---

## 🚀 Key Project Highlights
* **End-to-End Pipeline:** Traversed raw data processing, data structural cleaning, variable manipulation, and aggregation.
* **Dual-Industry Analysis:** Uncovered retail sales drivers and streaming content catalog distribution behaviors.
* **Executive Dashboards:** Structured multiple visualizations into unified side-by-side dashboard layout grids within a single Python framework.

---

## 🛍️ 1. E-commerce Retail Performance Dashboard
This phase involved processing a complex transactional retail log, correcting format structural anomalies, and engineering revenue metrics to analyze operational performance.

### Data Cleaning Checklist:
* Dropped records missing crucial customer identification to prevent skewing user demographics.
* Handled negative quantities and unformatted cancellation transactions.
* Created a consolidated `Revenue` metric (`Quantity` * `UnitPrice`).
* Extracted temporal properties (`YearMonth`, `Hour`) to identify buying behavior cycles.

### Visualized Insights:
* **Top Products:** Isolated the top 5 distinct items driving total sales volume and overall revenue.
* **Time-Series Trends:** Mapped monthly revenue trajectories across the financial year.
* **Geographic Breakdown:** Identified the top 5 revenue-generating nations.
* **Hourly Demand:** Modeled order frequencies across a 24-hour cycle to identify peak transaction hours.

---

## 🎬 2. Netflix Content Strategy Dashboard
This section addresses content catalog optimization metrics by analyzing Netflix's distribution of movies, television shows, production regions, and audience target groups.

### Data Cleaning Checklist:
* Imputed critical missing structural records (`director`, `country`, `cast`) safely with `"Unknown"` labels to maintain overall row architecture.
* Cleaned and standardized calendar data fields to extract content addition years.
* Unpacked complex, multi-string genre allocations via structural category exploding.

### Visualized Insights:
* **Content Distribution:** Identified the structural ratio split between Movies (~70%) and TV Shows (~30%).
* **Growth Tracking:** Quantified streaming title uploads over consecutive operating years.
* **Global Output:** Ranked the top 5 global content-producing powerhouses.
* **Genre Dominance:** Tracked and visualized the top 5 most prevalent genres globally using a clean, streamlined palette.

---

## 🛠️ Environment & Technical Toolkit
* **Platform:** Google Colab / Jupyter Notebook System (`.ipynb`)
* **Core Language:** Python
* **Data Manipulation:** Pandas, NumPy
* **Data Visualization:** Matplotlib, Seaborn

---

## 📂 Repository Structure
* `cleaned_ecommerce_retail.csv`: Fully processed, enterprise-ready retail transaction dataset.
* `cleaned_netflix_titles.csv`: Standardized, anomaly-free entertainment media inventory dataset.
* `Ecom_Netflix_Analysis.ipynb`: The master engineering notebook containing data processing scripts and dashboard grid blocks.

---
*Project completed as part of an applied data analytics learning track with AnalystLab Africa.*
