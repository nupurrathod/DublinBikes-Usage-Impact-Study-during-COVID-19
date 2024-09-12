## Project Overview
This project analyzes bike stand usage data across three distinct periods: pre-pandemic, during the pandemic, and post-pandemic. It aims to provide insights into how the pandemic has affected urban mobility, specifically in terms of bike usage in public bike-sharing systems.

## Features
- **Data Preprocessing**: Standardizes data from multiple sources, ensuring consistency across different data formats.
- **Time Series Analysis**: Splits data based on specific dates to categorize into pre-pandemic, pandemic, and post-pandemic periods.
- **Visualization**: Offers visual comparisons of bike stand availability across the three periods to highlight usage trends and potential impacts of the pandemic on public mobility.

## How It Works
1. **Data Loading**: Data is loaded from structured files, with specific columns selected and renamed for consistency.
2. **Data Splitting**: The dataset is split into different periods based on significant pandemic-related dates using regex within the time column.
3. **Aggregation and Visualization**: The data for each period is aggregated and visualized to show trends in bike stand availability, providing a clear picture of how public behavior changed over time.
