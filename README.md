# Uber Trip Analysis — Power BI

An end-to-end Power BI project that analyzes Uber trip data to uncover booking trends, revenue patterns, trip efficiency, vehicle performance, location demand, and time-based booking behavior.

## Key Features

- **Overview Dashboard** — Tracks Total Bookings, Total Booking Value, Average Booking Value, Total Trip Distance, Average Trip Distance, and Average Trip Time.
- **Vehicle Type Analysis** — Compares bookings, booking value, average booking value, and trip distance across vehicle types.
- **Payment & Trip Type Analysis** — Analyzes booking patterns across payment methods and day/night trip types.
- **Location Analysis** — Identifies frequent pickup/drop-off locations, farthest trips, top 5 booking locations, and preferred vehicles by pickup location.
- **Time Analysis** — Examines booking patterns using 10-minute pickup-time intervals, day-of-week trends, and an hour-by-day heatmap.
- **Dynamic Measure Selection** — Allows users to switch between Total Bookings, Total Booking Value, and Total Trip Distance across visualizations.
- **Interactive Slicers** — Enables filtering by date, city, and other available dimensions.
- **Drill-Through Analysis** — Allows users to move from summary visuals to detailed trip records.
- **Bookmarks** — Provides additional dashboard views and data-detail interactions.
- **Conditional Formatting** — Highlights high and low KPI values in vehicle-level analysis.

## Prerequisites

To explore or modify this project, you will need:

- **Microsoft Power BI Desktop**
- **Microsoft Excel** for viewing the source datasets
- The `.pbix` Power BI report
- The provided Excel datasets

## Installation

Clone the repository:

```bash
git clone https://github.com/<your-username>/Uber-Trip-Analysis-PowerBI.git
```

Navigate to the project directory:

```bash
cd Uber-Trip-Analysis-PowerBI
```

Open the Power BI report:

```text
Dashboard/Uber_Analysis_Dashboard.pbix
```

The project uses the provided Uber trip and location datasets as its source data.

## Usage

Open the Power BI report in **Power BI Desktop**.

The dashboard contains three main analytical sections:

### Overview Analysis

Provides a high-level view of Uber trip performance through KPIs and interactive visualizations. The analysis covers vehicle type, payment type, trip type, day, and location.

### Time Analysis

Analyzes trip demand over time using:

- 10-minute pickup-time intervals
- Day-of-week trends
- Hour-by-day heatmap
- Dynamic measures for bookings, booking value, and trip distance

### Details

Provides detailed trip-level records through a grid view and drill-through functionality. Users can select a data point in another dashboard and drill through to the related records.

## Tech Stack

| Technology | Purpose |
|---|---|
| **Power BI** | Dashboard development, visualization, data modeling, and analytics |
| **DAX** | Measures and dynamic calculations |
| **Power Query** | Data transformation and preparation |
| **Microsoft Excel** | Source data storage |
| **Power BI Bookmarks** | Dashboard state and navigation |
| **Power BI Drill-through** | Detailed record-level analysis |

## Project Structure

```text
Uber-Trip-Analysis-PowerBI/
│
├── Dashboard/
├── Dataset/
├── Problem-Statement/
├── Screenshots/
└── README.md
```

### Dashboard

Contains the Power BI report with the Overview, Time Analysis, and Details sections.

### Dataset

Contains the Uber trip details and location datasets used for the analysis.

### Problem-Statement

Contains the original business requirements and dashboard specifications.

### Screenshots

Contains screenshots of the completed Power BI dashboards for viewing directly from GitHub.

## Business Outcomes

The project is designed to help stakeholders:

- Identify booking and revenue trends
- Understand trip distance and duration patterns
- Detect peak and off-peak demand periods
- Compare vehicle performance
- Identify high-demand locations
- Understand customer trip patterns
- Support pricing and resource allocation decisions

This project demonstrates practical skills in data analysis, visualization, and business intelligence using Power BI.
