# 🍽️ Zomato Exploratory Data Analysis (EDA) Project

## 📌 Project Overview
This project focuses on Exploratory Data Analysis (EDA) of a Zomato restaurant dataset using Python. It explores restaurant categories, customer votes, ratings, online ordering, table booking availability, and approximate cost for two people.

The analysis uses Pandas for data preparation and Matplotlib and Seaborn for data visualization.

## 🎯 Project Objectives
- Understand the structure and summary statistics of the dataset.
- Clean and prepare data for analysis.
- Identify missing values and duplicate records.
- Analyze restaurant categories based on votes, ratings, and cost.
- Explore the relationship between ratings, votes, and online ordering.

## 🛠️ Tools & Technologies
- **Python**
- **Jupyter Notebook**
- **Pandas** – Data manipulation and analysis
- **NumPy** – Numerical operations
- **Matplotlib** – Data visualization
- **Seaborn** – Statistical visualization

## 📂 Dataset Overview
The supplied dataset contains **148 records and 7 columns**.

| Column | Description |
|---|---|
| Restaurant Name | Name of the restaurant |
| Online_Order | Online ordering availability |
| Book_Table | Table booking availability |
| Rate | Restaurant rating |
| Votes | Number of customer votes |
| Approx_Cost | Approximate cost for two |
| Listed_In(Type) | Restaurant category |

## 🧹 Data Cleaning
The following data preparation steps were performed:

- Imported the dataset using Pandas.
- Inspected dataset structure using `head()`, `info()`, and `describe()`.
- Converted restaurant ratings from text format (e.g. 4.1/5) into numeric values.
- Standardized column names to lowercase.
- Renamed the cost column to `approx_cost`.
- Checked missing values and duplicate records.

**Data Quality Results:**
- Total records: 148
- Missing values: 0
- Duplicate rows: 0

## 📊 Exploratory Data Analysis (EDA)

The project answers the following 10 business questions:

1. How many customer votes has each restaurant type received?
2. How many restaurants offer table booking?
3. Which five restaurants have the highest number of votes?
4. Is there a relationship between restaurant ratings and customer votes?
5. What is the average rating for each restaurant type?
6. Which restaurant type is most common in the dataset?
7. What ratings do restaurants most commonly receive?
8. Which restaurant type has the highest average cost for two people?
9. Do restaurants offering online ordering have higher ratings?
10. Which restaurant types have more records without online ordering?

### Visualization Techniques
- Pie Chart
- Bar Chart
- Scatter Plot
- Count Plot
- Histogram
- Box Plot
- Heatmap

## 🔍 Key Findings

1. **Most Common Category:** Dining represents 110 out of 148 records (74.3%).
2. **Customer Votes:** Dining received the highest total votes (20,363).
3. **Table Booking:** Only 8 restaurants (5.4%) offer table booking.
4. **Most Voted Restaurant:** Empire Restaurant leads with 4,884 votes, followed by Meghana Foods with 4,401.
5. **Rating & Votes:** A moderate positive correlation exists between ratings and votes (approximately 0.49).
6. **Highest Average Rating:** Other restaurant category has the highest average rating (3.91).
7. **Overall Ratings:** The average rating is 3.63, while the most frequent rating is 3.8.
8. **Highest Average Cost:** Buffet restaurants have the highest average approximate cost for two (671.43).
9. **Online Ordering:** Restaurants offering online ordering have a higher average rating (3.86) than those without it (3.49).
10. **Online Ordering Gap:** Dining has the highest number of records without online ordering (77).

## 📸 Project Visualizations

### Restaurant Votes Analysis
![Restaurant Votes Analysis](images/restaurant_votes.png)

### Table Booking Availability
![Table Booking Availability](images/table_booking.png)

### Rating Distribution
![Rating Distribution](images/rating_distribution.png)

### Online Ordering Analysis
![Online Ordering Analysis](images/online_ordering.png)

### Restaurant Category Heatmap
![Restaurant Category Heatmap](images/restaurant_heatmap.png)

*Replace these image placeholders with the actual charts from the project.*

## 📈 Conclusion
The analysis shows that Dining is the largest restaurant category and receives the highest total customer votes, while Buffet restaurants have the highest average cost for two people.

The Other category has the highest average rating. Table booking is uncommon in this dataset, and restaurants offering online ordering have higher average ratings.

These findings describe only the 148 records included in the supplied dataset and should not be generalized to all Zomato restaurants.

## ▶️ How to Run the Project

1. Clone or download this repository.
2. Install the required Python libraries:

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

3. Place the dataset file `zomato_data(1).csv` in the project directory.
4. Open the Jupyter Notebook.
5. Run the notebook cells to reproduce the analysis and visualizations.

## 👨‍💻 Project Type
**Exploratory Data Analysis | Python | Data Analytics**
