# RFM-Analysis
This repository contains Python code for performing RFM (Recency, Frequency, Monetary) analysis on customer data.
RFM analysis is a technique used to segment customers based on their transaction behavior, allowing businesses to identify and target specific customer groups. The analysis involves calculating three key metrics for each customer: Recency (how recently a customer made a purchase), Frequency (how often a customer makes a purchase), and Monetary Value (how much money a customer spends).

## Key Features:
### Data Preprocessing: 
The code includes steps for loading customer transaction data, converting dates, and calculating RFM metrics.

### Segmentation: 
Customers are segmented into categories such as "Champions," "Potential Loyalists," "Churned" and others based on their RFM scores for comparison and analysis.

### Visualization: 
Visualizations includes interactive charts for different RFM analysis aspects such as bar charts, treemaps, box plots, and correlation matrices to provide insights into customer segments.

### Dash Dashboard: 
A simple web-based dashboard using Dash, where users can dynamically select and view different RFM analysis charts.


## Usage:
### Data Preparation:
* Ensure you have a CSV file with customer transaction data (e.g., rfm_data.csv).
* Update the file path in the code to load your data.
  
### Run the RFM Analysis:
* Execute the Python script to perform RFM analysis on your customer data.

### Explore the Dashboard:
* Launch the Dash web application to interactively explore RFM charts.
  
## Dependencies:
* Python 3.x
* Pandas
* Plotly
* Dash

## Getting Started:
* Clone this repository:
[git clone https://github.com/PreciousEbu/rfm-analysis.git](https://github.com/PreciousEbu/RFM-Analysis.git)
cd rfm-analysis

* Install dependencies:
pip install -r requirements.txt

* Run the RFM Analysis script:
python rfm_analysis.py

* Launch the Dash Dashboard:
python rfm_dashboard.py


## Contributing:
Contributions are welcome! If you find a bug or have suggestions for improvements, please open an issue or create a pull request.

## License:
This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgement
https://thecleverprogrammer.com/2023/06/12/rfm-analysis-using-python/




