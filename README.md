

# Sales Dashboard Application

## Overview

This dashboard visualizes the sales performance, displaying the number of orders and total revenue for selected products. It allows filtering by product type and date range, with the graphs showing monthly sales statistics based on the filtered criteria.

## Prerequisites

To run this dashboard application, you'll need to install the following software:

- **Python 3.x** (Make sure it is installed on your system)
- **pip** (Python package installer)
  
You’ll also need to install several Python packages to support the dashboard. These can be installed using `pip`.

## Installation Steps

1. **Clone the Repository** (if applicable)
   
   If you're running this from a Git repository, clone it with:
   ```bash
   git clone <repository-url>
   cd <repository-directory>
   ```

2. **Install Required Libraries**

   Before running the application, install the required Python packages by running:

   ```bash
   pip install -r requirements.txt
   ```

   If a `requirements.txt` file is not present, you can manually install the necessary libraries. The typical libraries needed are:

   - `dash` - For building dashboards
   - `dash-bootstrap-components` - For styling the dashboard
   - `pandas` - For data manipulation and analysis
   - `plotly` - For creating graphs and visualizations

   Run the following command to install these:

   ```bash
   pip install dash dash-bootstrap-components pandas plotly
   ```

3. **Prepare Your Data**

   Ensure that the dataset you're using is structured appropriately for the dashboard. Typically, a CSV file containing sales data with columns for date, product type, number of orders, and revenue is expected. Modify the paths in the code to point to your data source if needed.

4. **Running the Application**

   To run the dashboard locally, execute the following command from the root directory:

   ```bash
   python app.py
   ```

   This will start a local web server, and you can access the dashboard in your browser by navigating to:

   ```
   http://127.0.0.1:8050/
   ```

5. **Dashboard Filters**

   - **Product Type Filter:** Select product types (e.g., shirts, jackets, trousers) to visualize their sales performance.
   - **Date Range Filter:** Specify the start and end dates to filter the sales data accordingly.

6. **Visualizations**

   The dashboard includes two main visualizations:
   - **Number of Orders per Month:** This line chart shows the monthly number of orders for the selected products.
   - **Total Revenue per Month:** This chart displays the total revenue earned each month for the selected product types.


