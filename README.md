# Airline_Performance_Analysis
Development of an interactive Flight Delay Analysis Dashboard using the Airline Reporting Carrier On-Time Performance dataset. The dashboard provides insights into various flight delay categories by month and airline, allowing users to visualize and analyze trends in flight performance over the selected year (between 2010 and 2020).

Dataset Used

The dashboard utilizes the Airline Reporting Carrier On-Time Performance dataset sourced from IBM’s Data Asset eXchange.

Dataset Link: https://lnkd.in/gpRPcdKv

Technologies Used

 📍Python: Used for building the dashboard application and performing data analysis.
 📍pandas: For data processing, reading, and manipulating the dataset.
 📍Dash: A web framework for creating interactive dashboards.
 📍Plotly Express: For generating interactive data visualizations

Dashboard components:

 
Input Year: A field for users to input the year of interest.
 
Visualizations: Five charts displaying:

Monthly average carrier delay by reporting airline.
Monthly average weather delay by reporting airline.
Monthly average national air system (NAS) delay by reporting airline.
Monthly average security delay by reporting airline.
Monthly average late aircraft delay by reporting airline.

charts are organized into three segments:

 Segment 1: Carrier and Weather delays
 Segment 2: NAS and Security delays
 Segment 3: Late Aircraft delays
