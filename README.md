# Visualization_Tool_for_Electric_Vehicle_Charge_and_Range_Analysis

Live Dashboard Link- https://public.tableau.com/views/Dashboard_17728228933830/ElectricCarsAnalyticsDashboard?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

📊 Project Overview

The Interactive EV Visualization Tool provides a data-driven environment for exploring electric vehicle performance and charging networks.

The system integrates multiple EV datasets, processes them in Tableau, and publishes interactive dashboards accessible through web interfaces.

Users can:

Explore EV specifications such as top speed, efficiency, and range

Analyze Indian EV market pricing trends

Locate charging stations with compatible connector types

Filter data dynamically by region, connector type, or vehicle brand

Visualize EV ecosystem insights through maps, charts, and treemaps

🏗 System Architecture

The project follows a data analytics pipeline architecture:

1️⃣ Data Source Layer

Raw datasets are collected in CSV/Excel format:

Global EV Specifications

Indian EV Market Prices

Charging Station Locations

2️⃣ Data Processing Layer (Tableau)

The Tableau Data Engine performs:

Data cleaning and formatting

Dataset joining and blending

Geographic role assignment (Latitude / Longitude)

Calculated fields for analytics

Spatial analysis for charging station reachability

3️⃣ Visualization Layer

Interactive dashboards display insights using:

🌍 Geospatial Maps

📊 Bar Charts

🌳 Treemaps

📈 Comparative Analytics

Users can dynamically filter the dashboard by:

Connector Type (AC, DC-001, CCS, etc.)

Region / City

EV Brand

Charging Availability

4️⃣ Web Integration Layer

The Tableau dashboards are embedded into a web portal, allowing users to interact with the analytics through a browser or mobile device.

🔄 Workflow
Data Admin / Analyst
        │
        ▼
Upload EV CSV / Excel Datasets
        │
        ▼
Tableau Data Engine
(Data Cleaning + Joins + Geo Processing)
        │
        ▼
Tableau Dashboard
(Maps + Charts + Filters)
        │
        ▼
Published Web Dashboard
        │
        ▼
End Users (EV Drivers / Buyers)
Interact with filters & explore insights
🛠 Technologies Used
Technology	Purpose
Tableau	Data visualization and dashboard creation
CSV / Excel	Data storage and dataset management
HTML	Web portal interface
Tableau Embed API	Integrating dashboards into the web application
Geospatial Analytics	Mapping charging station locations
📂 Project Structure
EV-Charge-Range-Analysis
│
├── datasets
│   ├── global_ev_specs.csv
│   ├── india_ev_prices.csv
│   └── charging_stations.csv
│
├── dashboard
│   └── ev_dashboard.twbx
│
├── web
│   └── index.html
│
├── images
│   └── architecture.png
│
└── README.md
✨ Key Features

✔ Interactive EV analytics dashboard
✔ Charging station location mapping
✔ EV performance comparison
✔ Dynamic filtering and exploration
✔ Integrated web visualization portal
✔ Real-time interactive user experience
