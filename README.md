# Used Car Dealership Sales & Inventory Analysis

An interactive, multi-page **Microsoft Power BI** project for exploring used-car dealership listings, inventory, sales-related indicators, pricing, and profitability across five automotive brands.

## Project overview

This project organizes dealership data into a Power BI report with a home page and dedicated brand-analysis pages. It is designed to help users explore vehicle inventory, compare models, and review city-wise and vehicle-category distributions.

### Brands covered
- Tata Motors (dataset brand label: Tata)
- Toyota
- Hyundai
- Maruti Suzuki
- Mahindra

## Dataset

The included CSV contains **1,500 rows** and **17 columns**.

**File:** `data/used_car_marketplace_top5_dataset.csv`

### Fields

| Column | Description |
|---|---|
| `Car_ID` | Unique vehicle/listing identifier |
| `Brand` | Vehicle brand |
| `Model` | Vehicle model |
| `Manufacturing_Year` | Vehicle manufacturing year |
| `Fuel_Type` | Fuel category |
| `Transmission` | Transmission category |
| `KM_Driven` | Distance driven in kilometres |
| `Owner_Type` | Previous-owner category |
| `City` | Listing city |
| `Listed_Price_INR` | Listed price in INR |
| `Purchase_Price_INR` | Purchase price in INR |
| `Selling_Price_INR` | Selling price in INR, where available |
| `Status` | Listing status |
| `Listing_Date` | Date the vehicle was listed |
| `Sold_Date` | Sale date, where available |
| `Car_Age_Years` | Vehicle age in years |
| `Profit_INR` | Profit in INR, where available |

## Dashboard scope

The accompanying project presentation describes these report elements:

### KPI cards
- Total Cars
- Cars Sold
- Cars in Stock
- Total Revenue
- Total Profit
- Average Car Price

### Visual analysis
- Model-wise car count
- City-wise car count
- Average listing price by model
- Fuel type distribution
- Transmission analysis

### Filters and navigation
- City
- Fuel Type
- Transmission
- Home page navigation to brand-specific report pages

### Brand pages
Dedicated analysis pages are described for Tata Motors, Toyota, Hyundai, Maruti Suzuki, and Mahindra.

## Tools and workflow

- **Microsoft Power BI** — report pages, KPI cards, charts, slicers, and navigation
- **Power Query** — data preparation and transformation
- **DAX** — measures and calculations
- **CSV** — source dataset

Suggested workflow:

`Dataset → Data preparation → Measures → Report visuals → Brand-wise exploration`

## Repository structure

```text
Used-Car-Dealership-Sales-Inventory-Analysis/
├── data/
│   └── used_car_marketplace_top5_dataset.csv
├── presentation/
│   └── used_car_dealership_project_presentation.pptx
├── docs/
│   └── data_dictionary.md
├── README.md
├── .gitignore
└── LICENSE
```

## How to use

1. Download or clone this repository.
2. Open Power BI Desktop.
3. Select **Get data → Text/CSV**.
4. Load `data/used_car_marketplace_top5_dataset.csv`.
5. Review data types and prepare the data in Power Query.
6. Create or open the Power BI report and build the KPI cards, visuals, slicers, and brand pages described above.

> **Power BI report file:** The `.pbix` file was not included among the supplied files. Add your actual Power BI report to the repository (for example, `powerbi/used_car_dealership_analysis.pbix`) before claiming that the PBIX is available here.

## Project presentation

See [`presentation/used_car_dealership_project_presentation.pptx`](presentation/used_car_dealership_project_presentation.pptx) for the project overview, objectives, KPI scope, visual design, brand pages, tools, and learning outcomes.

## Notes

- The dashboard metrics listed above are the report's intended KPI scope; this README does not assert evaluated KPI totals.
- Confirm measure definitions, slicer interactions, and cross-filter behavior in Power BI Desktop.
- Dataset brand labels should be retained as provided unless you intentionally standardize them in Power Query.

## Author

**Your Name**  
Add your LinkedIn and GitHub profile links here.
