
# Airbnb Listings Data Exploration & Visualization

## Project Overview
- This project performs **Exploratory Data Analysis (EDA)** on **New York Airbnb data** to uncover trends and patterns in rental listings.
- Utilizes **Pandas, NumPy, Matplotlib, Seaborn** for data cleaning, visualization, and analysis.

## Objective
- Analyze room types, prices, and availability across different neighborhoods.
- Understand host behavior and listing patterns.
- Detect potential outliers in prices.
- Provide recommendations for guests and hosts based on insights.

## Dataset
- Contains **20,765 entries** and **22 features** such as `id`, `name`, `host_name`, `neighborhood_group`, `latitude`, `longitude`, `price`, `room_type`, `reviews_per_month`, and `availability_365`.

## Steps and Workflow
1. **Data Cleaning:** Handle missing values, fix data types, and remove outliers.
2. **EDA:** Analyze room type distribution, price trends, neighborhood insights, availability patterns, and review behavior.
3. **Data Visualization:** Use histograms, boxplots, heatmaps, and bar charts to identify key insights.

## Key Findings
- **Manhattan has the most expensive listings**, followed by Brooklyn.
- **Entire homes/apartments dominate the market**, but private rooms are more budget-friendly.
- **Listings with high availability tend to have lower prices and better reviews.**
- **Professional hosts manage multiple listings**, impacting the rental market.

## How to Run This Project
1. Clone the repository:
   ```bash
   git clone https://github.com/najirh/Python-Project-P2-New-York-AirBnb-Listing-2024.git
   ```
2. Install dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn
   ```
3. Run the Jupyter Notebook:
   ```bash
   jupyter notebook day23_airbnb_eda.ipynb
   ```

## Recommendations
- **For Guests:** Choose high-availability listings with good reviews; private rooms in Brooklyn are more affordable.
- **For Hosts:** Improve availability, response rates, and pricing strategies to attract more bookings.

## Future Work
- Use **machine learning** to predict prices based on room type and location.
- Perform **sentiment analysis** on reviews for better guest insights.
- Develop an **interactive dashboard** using Plotly or Tableau for real-time monitoring.

## License
- This project is open-source and licensed under the **MIT License**.

 
