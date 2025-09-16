# 🏙️ Dubai Rental Properties - Exploratory Data Analysis (EDA)

## 📌 Project Overview
This project performs Exploratory Data Analysis (EDA) on a real-world dataset of rental properties in Dubai and Abu Dhabi.  
The goal is to uncover insights about rental trends, property types, location clusters, and factors influencing rent per square foot.

## 📂 Dataset
- **Rows:** 73,742
- **Columns:** 17  
- Features include: Address, Rent, Beds, Baths, Type, Area_in_sqft, Rent_per_sqft, Furnishing, Purpose, Location, City, Latitude, Longitude, etc.

## 🔍 Key Analyses
- Rent distribution across different property types
- Rent per sqft by City and Type
- Geographical rent clusters using Latitude & Longitude
- Correlation heatmap for numeric variables
- Time-based patterns from listing dates

## 📊 Visualizations
- Histogram of rent values
- Boxplots of rent per sqft by City/Type
- Scatter plot of rent vs area
- Correlation heatmap of numeric variables

## 🛠️ Tools & Libraries
- Python (Pandas, NumPy)
- Matplotlib
- Seaborn
- Scikit-learn (for clustering, optional)

## 🚀 How to Run
1. Clone the repository  
   ```bash
   git clone https://github.com/Robin6551/dubai-rental-eda.git
   cd dubai-rental-eda

   📌 Results

The analysis highlights:

Strong correlation between Rent, Area, and Number of Bedrooms

Rent per sqft varies significantly by City and Property Type

Certain locations form clusters of high rental prices

Time-based insights from Posted_date show listing dynamics
