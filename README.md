# Prathmesh-Somanath
Here’s a `README.md` file version for your `main.py` project:

---

# Startup Funding Analysis

This project analyzes startup funding data from a CSV file and visualizes trends, top sectors, top cities, top startups, and investment type distribution.

## 📂 Dataset

The script expects a file named `startup_funding.csv` with at least the following columns:

* **Date dd/mm/yyyy** – Date of funding
* **Amount in USD** – Funding amount (numeric)
* **Industry Vertical** – Sector of the startup
* **City  Location** – Location of the startup
* **Startup Name** – Name of the startup
* **InvestmentnType** – Type of investment

## ⚙️ Features

* Loads and cleans startup funding data
* Converts date and amount formats
* Aggregates monthly funding trends
* Identifies:

  * Top 5 industry sectors by count
  * Top 5 cities by funding amount
  * Top 5 startups by funding amount
* Displays the distribution of investment types
* Generates visualizations using **Matplotlib** and **Seaborn**

## 📊 Visualizations

The script generates the following plots:

1. **Funding Trend Over Time** – Line chart showing monthly total funding
2. **Top 5 Industry Verticals** – Bar chart
3. **Top 5 Cities by Funding** – Bar chart
4. **Top 5 Startups by Funding** – Bar chart
5. **Investment Type Distribution** – Bar chart

## 🛠️ Requirements

Install the required Python libraries:

```bash
pip install pandas matplotlib seaborn
```

## ▶️ Usage

1. Place `startup_funding.csv` in the same directory or update the CSV path in the script.
2. Run the script:

```bash
python main.py
```

3. The script will display summary statistics and show plots.

## 📌 Notes

* The dataset should have proper column names as mentioned above.
* Invalid or missing values will be handled and converted to proper formats when possible.

---


