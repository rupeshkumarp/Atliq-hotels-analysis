# Atliq-hotels-analysis  
This project performs data exploration and analysis on hotels booking data, extracting valuable insights about hotel performance, booking trends, revenue generation, and platform distribution.

project Overview:

The notebook analyzes multiple CSV datasets containing:
Booking records (fact_bookings.csv)
Aggregated booking data (fact_aggregated_bookings.csv)
Hotel details (dim_hotels.csv)
Room information (dim_rooms.csv)
Date dimension (dim_date.csv)

Key operations include:

Reading and exploring datasets
Finding unique room categories and booking platforms
Filtering bookings by specific platforms
Counting and visualizing booking distribution across platforms
Analyzing revenue statistics
Cleaning and correcting data (e.g., city name corrections)
Aggregating hotel and city-level insights

Dataset Structure:

fact_bookings.csv — Detailed booking records with room category, booking platform, revenue, etc.

fact_aggregated_bookings.csv — Aggregated booking metrics.

dim_hotels.csv — Hotel details such as category, property name, and city.

dim_rooms.csv — Room categories and details.

dim_date.csv — Date-related information for analysis.

Installation & Setup:

Clone this repository:
     
     git clone https://github.com/<your-username>/<repo-name>.git

Install required dependencies:

     pip install pandas numpy matplotlib
Place the datasets in the datasets folder (as structured in the notebook).

How to Run:

Open Jupyter Notebook:
    jupyter notebook
Open project.ipynb and run all cells to reproduce the analysis.

Example Insights:

Most popular booking platforms and their share.
Revenue distribution (max, min) across bookings.
Number of hotels per city.
Category-wise room and hotel details.

Technologies Used:


Python

Pandas for data manipulation

NumPy for numerical operations

Matplotlib for visualizations
