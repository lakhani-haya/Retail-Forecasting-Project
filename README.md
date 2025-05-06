# Retail Sales Forecasting using Prophet

This project uses Python and Facebook Prophet to forecast product category sales for a fictional retail dataset. It demonstrates how machine learning and business intelligence can work together to guide smarter inventory and marketing decisions.

---

## Project Objectives

- Forecast next 30 days of sales by product category (e.g., Clothing, Electronics, Beauty)
- Identify seasonal trends and sales anomalies
- Prepare business-ready dashboards for decision-makers using Power BI

---

##  Tools & Technologies Used

| Tool | Purpose |
|------|---------|
| **Python (Pandas, Prophet, Matplotlib)** | Data analysis and forecasting |
| **Prophet** | Time series forecasting per category |
| **Google Colab** | Interactive development environment |
| **Power BI** | Dashboard and KPI visualizations |
| **GitHub** | Project versioning and sharing |

---

## Forecasting Approach

1. Grouped historical sales by `Date` and `Product Category`
2. Built Prophet models per category to generate 30-day forecasts
3. Visualized each forecast and exported future values to `.csv`
4. Prepared Power BI visuals comparing actual vs forecasted performance

---


##  What I Learned

- How to implement time series forecasting for category-level retail sales
- How to export and structure predictive data for business dashboards
- How to integrate ML output into Power BI for executive use

---

## Power BI Dashboard

After generating category-level forecasts using Prophet, I created an interactive dashboard in **Power BI** to compare predicted vs actual sales, specifically for January 2024.

The dashboard includes:
- Forecast vs Actual line chart
- KPI cards for total predicted and actual sales
- Peak sales day comparison
- Forecast deviation (in days)
- Prediction accuracy metric

### Key Takeaways:
- Prophet was trained on 2023 data and used to forecast only January 2024 sales
- Due to smoothing and limited signals, Prophet didn’t capture all peak spikes (e.g., promotional surges)
- This visualization helps stakeholders understand both model performance and forecasting limitations

  <p align="center">
  <img src="images/PowerBI_dashboard.png" alt="Power BI Retail Forecasting Dashboard" width="800"/>
</p>

---

## Connect with Me

If you’d like to collaborate or view more projects, check out:
- [My Portfolio](https://lakhani-haya.github.io)
- [GitHub Profile](https://github.com/lakhani-haya)
- [Email](mailto:hy.lakhanii@gmail.com)
