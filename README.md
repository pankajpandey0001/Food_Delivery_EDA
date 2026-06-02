# Food Delivery Logistics: Exploratory Data Analysis (EDA) 🛵

## Project Overview
This project analyzes a real-world dataset of over 45,000 food delivery operations to evaluate restaurant performance, pinpoint logistical bottlenecks, and optimize delivery execution times. 

## Key Technical Skills Demonstrated
* **Python (Pandas):** Data cleaning, handling missing values, parsing messy timestamp strings, and feature engineering.
* **Feature Engineering:** Calculated precise time-delta variables to isolate restaurant preparation time from actual driver transit time.
* **Data Visualization:** Built heatmaps, boxplots, and distribution charts using **Matplotlib** and **Seaborn** to map out wait times based on traffic density, weather conditions, and time of day.

## Business Insights & Outcomes
1. **Isolated Prep Bottlenecks:** By calculating the exact difference between order placement and driver pickup times, the analysis proved that high traffic density correlates heavily with increased kitchen prep times, not just driver delays.
2. **Traffic Impact on Wait Times:** Visualized how 'Jam' level traffic density pushes median delivery execution times significantly higher, allowing for data-driven recommendations on driver allocation during peak hours.
3. **Weather Delays:** Demonstrated via categorical analysis that adverse weather conditions consistently add quantifiable delays to total delivery execution times.

## How to Run This Project
1. Clone this repository or download the files.
2. Ensure you have the `food_delivery_data.csv` dataset in the same directory as the notebook.
3. Run the Jupyter Notebook (`Food_Delivery_Analysis.ipynb`) in your local environment or Google Colab. All dependencies (`pandas`, `numpy`, `seaborn`, `matplotlib`) are standard.