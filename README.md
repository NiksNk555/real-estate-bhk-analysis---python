
# 🏠 Real Estate Market Analysis – Nestoria Data

## 📌 Business Problem

The Indian real estate market is vast and dynamic, but fragmented. Buyers struggle to compare properties due to scattered information, inconsistent pricing, and lack of structured data. Property websites often don’t present insights in a way that buyers, sellers, or investors can easily analyze.

This project tackles these challenges by scraping property data from **Nestoria**, cleaning and analyzing it, and presenting **clear insights on pricing, demand, and property trends**. The goal is to bring transparency and help stakeholders make **data-driven decisions**.

---

## 🎯 Project Objectives

* **Understand Property Trends** → Study prices, sizes, cities, and amenities.
* **BHK Demand Analysis** → Identify which BHK types (1BHK, 2BHK, etc.) dominate demand in different cities.
* **Price Insights** → Compare property price ranges, outliers, and per-square-foot variations across cities.
* **Location Trends** → Highlight cities and localities with the most active listings.
* **Market Segmentation** → Distinguish between affordable, mid-range, and luxury segments.
* **Decision Support** → Help buyers, sellers, and investors make informed choices.

---

## 🛠️ Project Workflow

### 1. Web Scraping

* Source: **Nestoria** (real estate listings)
* Tools: `Requests`, `BeautifulSoup`, `Regex`
* Process:

  * Sent requests to extract property details
  * Parsed HTML containers
  * Extracted key fields like:

    * Property Type (Apartment, Plot, Villa)
    * BHK Configuration
    * Price
    * City / Locality
    * Size & Amenities
  * Stored results in **CSV/Excel** for analysis

---

### 2. Data Cleaning & Processing

* Removed duplicates and irrelevant entries
* Standardized price formats (converted Cr/Lakhs)
* Handled missing values in size/amenities
* Converted categorical fields (Property Type, BHK) into structured formats

---

### 3. Exploratory Data Analysis (EDA)

* **Univariate Analysis** → Distribution of property types, BHK counts, and price ranges
* **Bivariate Analysis** → Price vs. BHK, City vs. Price, Locality vs. Demand
* **Multivariate Analysis** → City, property type, and BHK combined to see overall patterns

📊 **Visualizations Used**:

* Bar Charts (Top BHKs, Property Types, Cities)
* Histograms (Price Distribution)
* Boxplots (Price per Sq. Ft. across cities)
* Heatmaps (City-wise BHK and Price trends)

---

## 📊 Key Insights

1. **Property Type Distribution** → Apartments dominate (70%+), Plots ~22%, Villas <6%.
2. **BHK Demand** → 2 BHK leads the market, followed closely by 3 BHK. Luxury (4-5 BHK) is niche.
3. **Price Segmentation** → Most properties fall between ₹50 lakhs – ₹3 crores. Luxury listings (>₹5 cr) exist but are rare.
4. **Regional Trends** →

   * Mumbai leads in **premium pricing** and luxury listings.
   * Pune has **diverse options** (plots, apartments, villas).
   * Nagpur & Nashik remain **most affordable**.
5. **Locality Hotspots** →

   * Mumbai: Chembur, Andheri East, Mulund East
   * Pune: Hadapsar, Lohegaon
   * Nashik: Pathardi Phata
6. **Price per Sq. Ft.** → Mumbai has the highest rates, with wide variations (luxury + budget).

---

## 🚀 Motivation & Purpose

* **For Buyers** → Compare property prices, demand, and affordability ranges.
* **For Sellers** → Understand which configurations and localities attract maximum demand.
* **For Investors** → Spot affordable regions with growing demand for long-term investment.

---

## 📂 Dataset

* **Source**: Scraped from [Nestoria](https://www.nestoria.in)
* **Format**: CSV/Excel
* **Fields**: Property Type, BHK, Price, City, Locality, Size, Amenities
* **Size**: Several hundred listings across multiple cities (Mumbai, Pune, Nashik, Nagpur, etc.)

---

## 🖼️ Sample Visualizations

* 📊 Distribution of Property Prices
* 🏙️ City-wise Property Listings
* 📈 Average Price per BHK across Cities
* 🏡 Property Type Trends (Apartments vs. Plots vs. Villas)
* 💰 Price per Sq. Ft. Distribution by City

---

## 🔑 Conclusion

* **Mumbai** dominates premium housing, with high price per sq. ft.
* **Pune** offers a balanced market with varied property types.
* **Nashik & Nagpur** are budget-friendly markets with consistent pricing.
* **2 BHK** remains the most demanded configuration across cities.
* **Apartments** lead the listings, while **villas are rare**.

Overall, this project shows that real estate data, when cleaned and analyzed, reveals **clear market patterns** that can benefit buyers, sellers, and investors.

---

## 📎 Acknowledgements

* **Nestoria** → Source of property listings
* **Python Libraries** → `Requests`, `BeautifulSoup`, `pandas`, `numpy`, `matplotlib`, `seaborn`
* **Inspiration** → Similar real estate data analysis & Kaggle datasets

