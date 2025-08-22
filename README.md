<h1>Hospitality Data Analysis</h1>

This project performs data exploration and analysis on hospitality booking data, extracting valuable insights about hotel performance, booking trends, revenue generation, and platform distribution.

<h1>Project Overview</h1>

<h2>The notebook analyzes multiple CSV datasets containing:</h2>

Booking records (fact_bookings.csv)

Aggregated booking data (fact_aggregated_bookings.csv)

Hotel details (dim_hotels.csv)

Room information (dim_rooms.csv)

Date dimension (dim_date.csv)

<h2>Key operations include:</h2>

Reading and exploring datasets

Finding unique room categories and booking platforms

Filtering bookings by specific platforms

Counting and visualizing booking distribution across platforms

Analyzing revenue statistics

Cleaning and correcting data (e.g., city name corrections)

Aggregating hotel and city-level insights

<h1>Dataset Structure</h1>

fact_bookings.csv — Detailed booking records with room category, booking platform, revenue, etc.

fact_aggregated_bookings.csv — Aggregated booking metrics.

dim_hotels.csv — Hotel details such as category, property name, and city.

dim_rooms.csv — Room categories and details.

dim_date.csv — Date-related information for analysis.

<h1>Installation & Setup</h1>

<h2>Clone this repository:</h2>

            https://github.com/rupeshkumarp/Atliq-hotels-analysis.git


<h2>Install required dependencies:</h2>

          pip install pandas numpy matplotlib


Place the datasets in the datasets folder (as structured in the notebook).

<h1>How to Run</h1>

Open Jupyter Notebook:

          jupyter notebook


Open project.ipynb and run all cells to reproduce the analysis.


<h1>Technologies Used</h1>

Python

Pandas for data manipulation

NumPy for numerical operations

Matplotlib for visualizations
NumPy for numerical operations

Matplotlib for visualizations
