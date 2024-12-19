# 📊 **Sales Performance Dashboard**

An interactive sales dashboard built with Python, designed to analyze, visualize, and provide actionable insights into sales performance. This project is part of my journey in learning Python for **data analytics** and **business intelligence**.

---

## 🚀 **Features**
- **🧹 Data Cleaning & Transformation**: Preprocess and clean raw sales data to ensure accurate analysis.
- **📊 Interactive Visualizations**: Dynamic charts for KPIs such as total sales, margin percentage, retailer and company revenue, and sales trends.
- **🔄 Multiple Chart Types**: Choose between **Line Chart**, **Area Chart**, and **Bar Chart** to visualize the data.
- **💡 Key Metrics Display**: Displays essential business metrics like **Total Sales**, **Total Margin**, **Total Transactions**, and **Margin Percentage**.
- **⚙️ Dynamic Filters**: Filter data by year, retailer, company, and month to focus on specific segments.

---

## 🛠️ **Technologies Used**
- **🐍 Pandas**: For data manipulation and transformation.
- **📈 Streamlit**: For building the interactive, user-friendly web-based dashboard.
- **🧹 Preprocessing Scripts**: `Preprocessor.py` for cleaning and processing the data.
- **📊 Matplotlib / Seaborn**: For advanced visualizations (though Streamlit’s built-in charting capabilities are used primarily).

---

## 💻 **Installation & Setup**

### 1. Clone the Repository
```bash
git clone https://github.com/KIRAN-KUMAR-K3/Sales-Performance-Dashboard.git
cd Sales-Performance-Dashboard
```

### 2. Install Dependencies
Ensure Python 3.7+ is installed. Use the `requirements.txt` file to install the necessary dependencies.

```bash
pip install -r requirements.txt
```

### 3. Launch the Dashboard
Run the following command to start the Streamlit app and view the dashboard in your browser.

```bash
streamlit run main.py
```

---

## 📊 **Data**
The project uses a CSV file (`data.csv`) containing sales data, which is loaded and processed for analysis. The data includes the following fields:
- 📅 **Financial Year**
- 🏪 **Retailer**
- 🏢 **Company**
- 💰 **Sales Amount**
- 📊 **Margin**
- 📆 **Financial Month**

---

## 🧮 **Key Metrics & Insights**

- **💵 Total Sales**: Displays the total sales amount based on selected filters.
- **💰 Total Margin**: Shows the total margin from the selected data.
- **🛍️ Total Transactions**: Displays the total number of transactions for the selected period.
- **📈 Margin Percentage**: Shows the margin as a percentage of total sales.

---

## 📊 **Visualizations**
- **📈 Line Chart**: Shows sales trends over time.
- **📊 Area Chart**: Visualizes sales trends with an area fill.
- **📉 Bar Chart**: Displays a bar graph of sales data.

---

## 🎓 **Learning Outcomes**
This project helped me build foundational skills in:
- **🧹 Data Cleaning**: Using pandas to preprocess and transform raw sales data into actionable insights.
- **📊 Data Visualization**: Creating interactive dashboards using Streamlit and generating visualizations.
- **📈 Business Intelligence**: Using data analytics to inform decision-making and business strategies.

---

## 🔮 **Future Improvements**
- **🌐 Real-time Data Integration**: Connect the dashboard to a live database for real-time data analysis.
- **📊 Additional Visualizations**: Adding more visualization types such as **pie charts**, **heatmaps**, and **histograms**.
- **🔐 User Authentication**: Implementing user authentication for personalized dashboard views and restricted access.
- **💡 Enhanced Data Insights**: Provide deeper insights into sales performance with **advanced analytics** and **predictive models**.

---

## 🔗 **Demo**
Check out the live dashboard hosted on Streamlit:  
🌐 [Sales Performance Dashboard Demo](https://sales-performance-dashboard.streamlit.app/)

---

## 📝 **License**
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 🙏 **Acknowledgements**
- **🎉 Streamlit**: For enabling the creation of interactive web-based applications with minimal effort.
- **🐍 Pandas**: For providing robust data manipulation and analysis capabilities.
- **🧹 Preprocessor.py**: Custom script for transforming raw data into usable, structured formats for analysis.
- **📊 Matplotlib / Seaborn**: For generating advanced visualizations when needed.
