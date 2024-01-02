# Sales Dashboard README

## Overview

This repository contains a Dash web application for visualizing sales and profit data based on a provided dataset. The application leverages Plotly Express for creating interactive visualizations and Dash for building the web interface. Users can explore sales and profit trends over different years, view state-wise performance, and analyze sales and profit by category.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/sales-dashboard.git
   ```

2. Navigate to the project directory:

   ```bash
   cd sales-dashboard
   ```

3. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Ensure you have Python installed on your machine.

2. Run the Dash web application:

   ```bash
   python sales_dashboard.py
   ```

3. Open a web browser and go to [http://127.0.0.1:8051/](http://127.0.0.1:8051/) to access the Sales Dashboard.

4. Interact with the dropdowns and sliders to explore different visualizations based on sales and profit data.

## Code Structure

- `sales_dashboard.py`: The main script containing the Dash application and visualization functions.
- `orders.csv`: The dataset used for sales and profit analysis.
- `requirements.txt`: List of Python packages required for the project.

## Visualizations

### 1. Sales by State

- Select 'Sales by State' from the dropdown menu.
- Use the slider to choose the desired year.
- View a choropleth map showing sales data for each state.

### 2. Profit by State

- Select 'Profit by State' from the dropdown menu.
- Use the slider to choose the desired year.
- View a choropleth map showing profit data for each state.

### 3. Sales and Profit Trends

- Choose between 'Sales' and 'Profit' from the dropdown menu.
- Use the slider to select the desired year.
- Explore line charts depicting quarterly sales and profit trends by category.

## Dependencies

- pandas
- plotly
- dash
- numpy

## License

This Project is unlicensed
