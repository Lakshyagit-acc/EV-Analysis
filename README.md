🚘 EV Analysis Dashboard

A Tableau project analyzing Electric Vehicle (EV) Population Data. This dashboard provides insights into EV adoption trends, vehicle types, range statistics, brand distribution, and eligibility for clean alternative fuel programs.

📂 Dataset

The dataset used contains details of electric vehicles, including:

Vehicle make, model, and year

Electric vehicle type (BEV / PHEV)

Electric range (miles)

Clean Alternative Fuel Vehicle (CAFV) eligibility

Geographic information (State, County, City)

🧹 Data Cleaning

Before visualization, the dataset underwent preprocessing:

Removed duplicates and irrelevant columns (VINs, IDs, etc.)

Handled missing values in postal codes, CAFV eligibility, and electric range

Standardized categorical values (e.g., "TESLA" vs "Tesla")

Converted model year and electric range to numeric data types

Filtered data between 2010 – 2024

📊 Visualizations

Key dashboards in Tableau include:

EV Growth by Year 📈 – Trends in total vehicles from 2010 to 2024

Distribution by EV Type 🔋 – Battery Electric Vehicles (BEVs) vs Plug-in Hybrid EVs (PHEVs)

Average Electric Range ⚡ – Mean range across all registered vehicles

Top Brands 🚗 – Tesla, Nissan, Chevrolet, Ford, BMW, Kia, Toyota

State-wise Adoption 🗺️ – Geographic distribution of EVs in the U.S.

CAFV Eligibility ✅❌ – Classification of vehicles into eligible, not eligible, and unknown

🔎 Key Insights

Total Vehicles Analyzed: ~150,000

Average Range: ~68 miles

BEV vs PHEV: BEVs dominate with 77.6%, while PHEVs are 22.4%

Top Brand: Tesla leads with ~69k vehicles

CAFV Eligibility:

41.8% eligible

11.9% not eligible

46.3% unknown

🛠️ System & Software Requirements

Operating System: Windows / macOS / Linux

Software:

Tableau Desktop / Tableau Public

Python 3.8+ (for preprocessing with pandas, optional)

Git (for version control)

Hardware: 8GB RAM recommended for smooth dashboard interaction

🚀 How to Use

Clone this repository

git clone https://github.com/Lakshyagit-acc/EV-Analysis.git


Open the Tableau workbook (.twbx) or connect the dataset

Explore filters (Year, State, Make, EV Type, CAFV Eligibility)

Interact with maps, charts, and dashboards to gain insights

📌 Future Enhancements

Add forecasting models for EV adoption

Deeper range analysis by battery size & year

Integration with charging infrastructure data

✨ This project provides a clear, interactive view of EV adoption trends in the U.S., empowering policymakers, researchers, and EV enthusiasts with data-driven insights.
