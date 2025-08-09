# Call Centre Report Dashboard – Excel Project

## Project Overview

This project is an **advanced Excel-based dashboard** designed to analyze and visualize comprehensive call centre operations for actionable insights. Built with interactivity and clarity in mind, the dashboard allows users—such as supervisors, managers, and analysts—to quickly understand agent performance, customer behavior, business trends, and customer satisfaction.

***

## Table of Contents

- Project Overview
- Features
- Dashboard Components Explained
- File Structure
- How to Use the Dashboard
- Customization & Data Import
- Troubleshooting
- Credits

***

## Features

- **KPIs Panel**: Quick snapshot of primary metrics—total calls handled, amounts processed, call durations, average rating, and happy callers.
- **Trend Analysis**: Monthly and weekly call volume trends.
- **Caller Demographics**: Gender split of callers across different cities.
- **Customer Satisfaction**: Distribution of ratings and identification of satisfaction drivers.
- **Agent Performance**: Calls and value processed per agent, agent-specific breakdown by city and user.
- **Drilldown Table**: Detailed, city-wise, agent-wise report for in-depth analysis.
- **Interactive Selection**: Allows highlighting and filtering data for a specific agent or metric, using Excel features.

***

## Dashboard Components Explained

| Component             | Description                                                                                      |
|-----------------------|--------------------------------------------------------------------------------------------------|
| **KPI Tiles**         | Show total calls, amount handled, total duration, average customer rating, happy callers count.  |
| **Call Trend Chart**  | Line graph displaying monthly call numbers to spot peaks and drops.                              |
| **Day-of-Week Bar**   | Calls segmented by each weekday for resource planning.                                           |
| **Demographics Chart**| Stacked bars splitting callers by gender across major cities (Cincinnati, Cleveland, Columbus).  |
| **Rating Histogram**  | Shows volume of various ratings (1–5 stars), revealing satisfaction levels.                      |
| **Agent Breakdown**   | Horizontal bars for each agent—calls handled and total value processed side by side.             |
| **Rep Selector**      | Dynamic slicer to highlight and drilldown into a chosen agent’s data across all charts/tables.   |
| **Detailed Metrics**  | Data table by city, customer ID, and agent, listing calls, values, totals, with agent highlights.|

***

## File Structure

- **Dashboard**: Main worksheet with all visualizations.
- **Data Input**: Sheet(s) where raw call data is entered or imported.
- **Helper Tables/Calculations**: Hidden or auxiliary sheets for summarizations, pivot tables, and formulas.

***

## How to Use the Dashboard

1. **Prepare Data**: Place your call centre data (calls, agents, caller info, ratings, amounts, etc.) in the data input table or sheet as instructed.
2. **Enable Features**: Enable macros and editing in Excel if prompted, for full dashboard interactivity.
3. **Interact**: Use the agent selector (slicer), click charts, or adjust date ranges to filter and focus dashboard metrics.
4. **Analyze**:
   - Spot call trends for busy months or days.
   - See which agents are top performers both in call count and value.
   - Identify cities or customers with frequent contacts or high values.
   - Gauge customer satisfaction through average rating and happy caller numbers.
5. **Present/Export**: Copy visuals or tables into reports, or export dashboard as PDF for sharing.

***

## Customization & Data Import

- **Refresh Data**: After updating data in the input sheet, refresh PivotTables (right-click > Refresh) and linked charts.
- **Modify Layout**: Add/remove visual elements as needed; adjust formulas if KPIs are customized.
- **Add Agents or Metrics**: Update source data; new agents/columns will auto-populate after refresh.
- **Localize**: Adjust currency, formats, and locale settings for region-specific reporting.

***

## Troubleshooting

- **Charts Not Updating**: Refresh all pivots/tables after data import.
- **Broken Formulas**: Check for correct data range and column names.
- **Cannot Select Agent**: Ensure slicers are properly connected to relevant PivotTables.
- **Performance Issues**: For very large datasets, consider summarizing or sampling data before importing.

***

## Credits

Developed by Mehul S V. Inspired by best practices in Excel reporting and dashboard design, following guidance from resources like freeCodeCamp's README template and Excel dashboard tutorials.

***

