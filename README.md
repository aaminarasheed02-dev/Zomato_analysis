

# Zomato Data Analysis 🍴

This project involves an exploratory data analysis (EDA) of restaurant data using the Zomato dataset. The analysis focuses on data cleaning, customer engagement metrics, and price distribution using Pandas, NumPy, and Seaborn.

 📌 Project Overview
The objective of this analysis is to:
* Perform data cleaning and preprocessing on restaurant data.
* Identify popular restaurant categories and their market presence.
* Analyze the relationship between pricing, online ordering, and customer ratings.

📊 Key Features & Analysis
The analysis covers several critical data science steps:
* Data Cleaning: Implemented a custom `handleRate` function to clean and convert string-based ratings (e.g., "4.1/5") into numerical values.
* Category Distribution: Visualized the count of various restaurant types (Buffet, Cafes, Dining, etc.) using Seaborn's `countplot`.
* Engagement Analysis:Aggregated total `votes` per restaurant type to determine which categories drive the most customer interaction.
* Top Performance: Filtered the dataset to identify the restaurant with the highest number of customer votes using `.loc`.
* Cost Visualization: Analyzed the `approx_cost(for two people)` to visualize the preferred price range for customers.
* Feature Comparison: Used `Box Plots` to compare ratings for restaurants that offer online ordering versus those that do not.
* Pivot Tables: Created a heatmap to show the relationship between restaurant types and online ordering availability.

🛠️ Tech Stack
* Language:Python
* Libraries: Pandas, NumPy, Matplotlib, Seaborn

 📈 Key Insights
* Online Ordering:Restaurants that accept online orders generally show a higher distribution of positive ratings.
* Popular Types: Delivery and Dining are the most frequent restaurant types in the dataset.
* Engagement: Highly voted restaurants are easily identifiable, helping pinpoint market leaders in terms of popularity.

📂 Repository Structure
* `Zomato_Data_Analysis_Using_Python.ipynb`: The primary Jupyter Notebook containing the code and visualizations.
* `Zomato-data-.csv`: The source dataset used for the analysis.

---

### How to run this locally
1.  Clone the repository:
    ```bash
    git clone https://github.com/your-username/your-repo-name.git
    ```
2.  Install required packages:
    ```bash
    pip install pandas numpy matplotlib seaborn
    ```
3.  Open the `.ipynb` file in Jupyter Notebook or VS Code.
