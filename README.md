# Sales Performance Dashboard 📊

An interactive sales dashboard built with Python, designed to analyze, visualize, and provide actionable insights into sales performance. This project is a part of my journey in learning Python for data analytics.

---

## Features
- **Data Cleaning & Transformation**: Preprocess and clean raw sales data for accurate analysis.
- **Interactive Visualizations**: Provides dynamic charts for KPIs such as total sales, margin percentage, retailer and company revenue, and sales trends.
- **Multiple Chart Types**: Users can select between Line Chart, Area Chart, and Bar Chart to visualize data.
- **Metrics Display**: Displays metrics like Total Sales, Total Margin, Total Transactions, and Margin Percentage.
- **Dynamic Filters**: Allows users to filter data by year, retailer, company, and month to analyze specific segments of the data.

---

## Technologies Used
- **Pandas** for data manipulation and processing.
- **Streamlit** for building an interactive, web-based dashboard.
- **Preprocessing** scripts to clean and transform data into meaningful insights.
- **Matplotlib / Seaborn** for generating visualizations (though Streamlit's built-in charting is used here).

---

## Installation & Setup

### 1. Clone the Repository
```bash
git clone https://github.com/KIRAN-KUMAR-K3/Sales-Performance-Dashboard.git
cd Sales-Performance-Dashboard
```

### 2. Install Dependencies
Make sure you have Python 3.7+ installed. Use `requirements.txt` to install necessary dependencies.

```bash
pip install -r requirements.txt
```

### 3. Launch the Dashboard
Run the following command to start the Streamlit app and view the dashboard in your browser.

```bash
streamlit run main.py
```

---

## Data
The project uses a CSV file (`data.csv`) containing sales data, which is loaded and processed for analysis. The data includes fields like:

- Financial Year
- Retailer
- Company
- Sales Amount
- Margin
- Financial Month

---

## Key Metrics & Insights

- **Total Sales**: Displays the total sales amount based on selected filters.
- **Total Margin**: Displays the total margin from the selected data.
- **Total Transactions**: Shows the total number of transactions for the selected period.
- **Margin Percentage**: Displays the margin as a percentage of total sales.

---

## Visualizations
- **Line Chart**: Shows sales trends over time.
- **Area Chart**: Provides a visual representation of sales trends with an area fill.
- **Bar Chart**: Displays a bar graph of sales data.

---

## Learning Outcomes
This project helped me build foundational skills in:
- **Data Cleaning**: Using pandas to preprocess and transform raw sales data into meaningful insights.
- **Data Visualization**: Creating interactive dashboards using Streamlit and generating visualizations.
- **Business Intelligence**: Using data analytics to inform decision-making and business strategies.

---

## Future Improvements
- Integration with a database for real-time data analysis.
- Additional data visualizations such as pie charts and heatmaps.
- User authentication and personalized dashboards.

---

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## Acknowledgements
- **Streamlit**: For making it easy to create web apps for data science.
- **Pandas**: For powerful data manipulation tools.
- **Preprocessor.py**: Custom script for transforming raw data into a usable format.
