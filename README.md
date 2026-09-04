# Exploratory-Data-Analysis-Project

 Real Estate Price Analysis & Exploratory Data Analysis (EDA)

An end-to-end exploratory data analysis and feature valuation project built using Python, Pandas, Matplotlib, and Seaborn. This project analyzes real estate listings across major Indian cities to uncover what truly influences residential property prices.

## 📌 Project Overview

In this project, I performed an exploratory data analysis on real estate housing records (`dataset_2.csv`), cleaned missing attributes, built comparative visual charts, and trained an OLS regression alongside an ensemble Random Forest model to determine the exact price drivers of residential properties.

---

## 🔍 Key Insights & Findings

* **Living Space is King (~79.4% Importance):** Property square footage (Area_SqFt) has an $r = 0.86$ correlation with valuation. On average, each extra square foot adds approximately **₹165** to the property's cost.
* **Property Archetype Premiums:**
  * **Villas** command the highest market valuation (~₹70.5 Lakhs average), commanding an estimated **₹1.22 Lakh premium** over apartments of comparable size and age.
  * **Duplexes** (~₹62.8 Lakhs) and **Independent Houses** (~₹62.4 Lakhs) form the mid-to-upper bracket, while **Apartments** (₹57.3 Lakhs) provide the lowest entry threshold.
* **Geographic Disparities:** NCR cities lead overall real estate valuations—**Delhi** (avg. ₹66.8 Lakhs) and **Gurugram** (avg. ₹65.6 Lakhs) sit at the top. Fast-growing Tier-2 markets like **Kanpur** (avg. ₹57.1 Lakhs) and **Prayagraj** (avg. ₹56.8 Lakhs) trade at an average discount of ₹70,000–₹90,000 compared to the capital region.
* **Value of Security & Finishing:**
  * Homes located in **Gated Societies** carry a premium of **₹33,700** over baseline street types.
  * Moving from an **Unfurnished** property to a **Furnished** property adds around **₹51,600** in retained valuation.
  * Private swimming pools (`Has_Pool = Yes`) add an extra **~₹34,800** on average.
* **Data Hygiene Note:** Identified 33 missing values across `Area_SqFt`, `Rooms`, and `Furnishing` (2.9% of rows), which were handled cleanly before feeding data into modeling pipelines.

## 📊 Visualizations Included
* **Price Distribution & Histograms:** Evaluated skewness, median values, and overall price distributions across listings.
* **Price vs. Area Scatter:** Mapped property sizes against valuations segmented by property type.
* **Boxplots by Property Type:** Visualized the spread, quartiles, and luxury outliers for villas and independent houses.
* **City-Level Averages:** Ranked average costs across eight metropolitan and Tier-2 cities.
* **Scatter Plot Bubble Table / Dot Matrix:** Visualized inventory concentrations and property availability across furnishing tiers and building designs.

## 🛠️ Tech Stack & Tools
* **Language:** Python
* **Data Wrangling:** Pandas, NumPy
* **Visualization:** Seaborn, Matplotlib
