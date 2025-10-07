# Airbnb Data Visualization Project

### Project Title

VOIS_AICTE_Oct2025_Kuldeep — Airbnb Data Visualization and Insights

---

## Overview

This project is based on the analysis and visualization of Airbnb open data.
The main purpose is to find patterns and insights about room prices, host activity, and availability across different areas in New York City.
The work focuses on understanding how various factors such as location, property type, and host behavior affect Airbnb listings.

The analysis is performed using Python in Jupyter Notebook.
All visual results like graphs and charts are saved automatically in a folder for easy access and reference.

---

## Objectives

1. Identify different property and room types in the dataset.
2. Find which neighborhood group has the highest number of listings.
3. Check which areas have higher average prices.
4. Understand the relationship between construction year and price.
5. Identify the top 10 hosts by number of listings.
6. Compare verified and non-verified hosts based on reviews.
7. Check the correlation between price and service fee.
8. Study the average review ratings by neighborhood and room type.
9. Analyze host listing count versus availability throughout the year.

---

## Tools and Technologies

* Python
* Jupyter Notebook
* Pandas – for data handling
* NumPy – for numeric calculations
* Matplotlib – for visual plots
* Seaborn – for advanced data visualization
* OpenPyXL – for reading Excel files

---

## Project Files

```
VOIS_AICTE_Oct2025_Kuldeep/
│
├── Airbnb_Analysis.ipynb.ipynb   # Main Jupyter Notebook file
├── Airbnb_Open_Data.xlsx         # Dataset file
├── requirements.txt              # Required Python libraries
├── Airbnb_Charts/                # Folder where charts and graphs are saved
└── README.md                     # Project information file
```

---

## How to Run the Project

1. Clone the project repository

   ```
   git clone https://github.com/Kuldeep1436/VOIS_AICTE_Oct2025_Kuldeep.git
   cd VOIS_AICTE_Oct2025_Kuldeep
   ```

2. Install all dependencies

   ```
   pip install -r requirements.txt
   ```

3. Open Jupyter Notebook

   ```
   jupyter notebook
   ```

4. Run the file `Airbnb_Analysis.ipynb.ipynb` cell by cell.
   After running all cells, all the charts will be automatically saved in the folder `Airbnb_Charts`.

---

## Data Cleaning Process

* Removed duplicate entries
* Dropped columns with insufficient data (`house_rules`, `license`)
* Removed dollar signs and commas from numeric columns
* Fixed spelling errors (e.g., “Brookln” → “Brooklyn”)
* Handled missing values
* Converted incorrect data types to proper formats

---

## Visualizations and Insights

* **Room Type Distribution** – shows which type of listings are most common.
* **Listings by Neighborhood Group** – counts of listings in each borough.
* **Average Price by Neighborhood** – bar chart showing price variation.
* **Price vs Construction Year** – scatter plot showing price trends.
* **Top 10 Hosts** – bar chart showing most active hosts.
* **Verified Hosts Average Rating** – comparison between verified and unverified hosts.
* **Price vs Service Fee** – scatter plot showing correlation.
* **Average Review Rating Heatmap** – review scores across neighborhoods and room types.
* **Host Listings vs Availability** – relationship between host activity and room availability.

All these charts are saved as PNG images in the `Airbnb_Charts` folder.

---

## Key Findings

* Entire homes/apartments make up most of the listings.
* Brooklyn and Manhattan have the highest number of listings.
* Verified hosts usually receive better reviews.
* Listing price and service fee show a strong positive relationship.
* Older properties tend to have slightly lower prices.

---

## Learning Outcome

This project helped in understanding:

* How to clean and process large datasets
* How to visualize and interpret real-world data
* How to automate chart saving in Python
* How to document and organize a data analysis project

---

## Author

**Kuldeep**
VOIS AICTE Internship Project — October 2025
