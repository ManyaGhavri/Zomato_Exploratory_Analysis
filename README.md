# 🍽️ Zomato India Restaurant EDA

This repository provides an Exploratory Data Analysis (EDA) of Indian restaurants using a public Zomato dataset. The goal is to uncover insights into restaurant types, cuisine trends, city-wise performance, and cost-rating dynamics.

---

## 📁 Project Structure

```
📦 Zomato-EDA
├── Indian-Resturants.csv         # Raw dataset
├── zomato_analysis.ipynb         # EDA notebook with code and plots
├── zomato_analysis.html          # HTML version of the notebook
└── README.md                     # Project documentation
```

---

## 🧰 Tools & Libraries Used

This project was developed in Python and makes use of the following libraries:

| Library     | Purpose                                                                 |
|-------------|-------------------------------------------------------------------------|
| pandas      | For loading and cleaning the dataset, and general data manipulation     |
| numpy       | For numerical operations, e.g., mean, percentiles                       |
| matplotlib  | For static plotting (bar charts, box plots, etc.)                       |
| seaborn     | For statistical data visualization (distribution plots, heatmaps)       |
| wordcloud   | To visualize popular cuisines and location names in word cloud format   |
| warnings    | Used to suppress irrelevant warnings during the analysis                |

---

## 📊 Key Features of the Analysis

### 🗂️ 1. Data Loading & Cleaning
- Dataset read with `pandas.read_csv()`
- Handled nulls using `dropna()` and filled values where needed
- Cleaned irrelevant or duplicate entries

### 📌 2. Descriptive Statistics
- Used `df.describe()` to summarize data
- Analyzed rating distribution and cost structure

### 📈 3. Visualization
- `matplotlib.pyplot` and `seaborn` used for:
  - Count plots of restaurant types
  - Box plots of cost across ratings
  - City-wise distribution of restaurants
- `WordCloud` used to show frequent cuisines and cities visually

### 🧭 4. Location Analysis
- Top cities by restaurant count
- Average ratings by city

### 🍲 5. Cuisine Insights
- Most common cuisines served
- Comparison of average cost and ratings by cuisine

### 🧠 6. Business Recommendations
- Suggested cities and cuisine combinations to target
- Observed that online ordering positively influences ratings

---

## 🔍 How to Run

To replicate the results:

### Clone the repo:
```bash
git clone https://github.com/yourusername/zomato-eda.git
cd zomato-eda
```

### Install dependencies:
```bash
pip install pandas numpy matplotlib seaborn wordcloud
```

### Open the notebook:
```bash
jupyter notebook zomato_analysis.ipynb
```

---

## 📌 Key Insights

- **Top Cities**: Bengaluru, Delhi, Hyderabad lead with the highest number of restaurants.
- **Popular Cuisines**: North Indian, Chinese, Fast Food dominate the market.
- **Cost Insights**: Higher cost does not always guarantee better ratings.
- **Online Orders**: Restaurants with online ordering tend to have better customer ratings.

---

## 📬 Contact

- 👩‍💻**Author:** Manya Ghavri 
- 📧**Email:** manyaghavri3211@gmail.com
- 🌐**GitHub:**[GitHub Profile](https://github.com/ManyaGhavri)
- 🔗**Linkedin:** [Linkedin_link](https://www.linkedin.com/in/manya-ghavri-b00773310/)
