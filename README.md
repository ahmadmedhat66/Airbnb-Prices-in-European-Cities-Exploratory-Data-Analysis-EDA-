# Airbnb-Prices-in-European-Cities-Exploratory-Data-Analysis-EDA-
This project is a high–impact, portfolio‑ready exploratory data analysis (EDA) on Airbnb listings across major European cities. The goal is to understand the key determinants of Airbnb pricing by analyzing factors such as room types, cleanliness ratings, satisfaction scores, distance from city center, host attributes, and more.

## 🚀 Project Objectives

* Understand pricing trends across European cities
* Analyze the influence of:

  * Distance from city center
  * Cleanliness rating
  * Guest satisfaction
  * Host attributes (e.g., superhost)
  * Room type
  * Number of bedrooms
* Compare **weekday vs weekend** prices
* Perform feature relationships through visualization
* Build a structured, reproducible EDA workflow

---

## 📁 Dataset

**Source:** Kaggle — *Airbnb Prices in European Cities*
**License:** CC0 (Public Domain — free to use)

The dataset includes separate CSV files for **weekday** and **weekend** listings for several European cities. Each listing contains:

* `realSum` — total listing price
* `room_type`
* `cleanliness_rating`
* `guest_satisfaction_overall`
* `dist` — distance from city center
* `metro_dist`
* `host_is_superhost`
* `bedrooms`
* `person_capacity`
* Location coordinates (`lng`, `lat`)

---

## 🛠️ Tools Used

* **Python** (Pandas, NumPy, Matplotlib, Seaborn)
* Jupyter Notebook
* Git & GitHub

---

## 📚 Project Structure

```
├── EDA_Airbnb_Prices_in_European_Cities.ipynb   # Main analysis notebook
├── data/
│   ├── vienna_weekdays.csv
│   ├── vienna_weekends.csv
│   └── ... other cities
└── README.md
```

---

## 🔍 Key Analyses Performed

### ✔ Price distribution (weekday vs weekend)

### ✔ City‑level comparison

### ✔ Relationship between price and:

* distance from center
* room type
* cleanliness rating
* number of bedrooms
* guest satisfaction

### ✔ Effect of superhost status on pricing



## 📈 Overall Insights

Prices vary dramatically by city, with major tourist capitals being the most expensive.

Secondary European cities provide the best value for money — high satisfaction at lower costs.

Weekend stays are usually more expensive due to tourism-driven demand.

Location is the strongest driver of price. Listings near the city center command a clear premium.

Superhosts charge more, but often deliver better experiences.

Cleanliness heavily impacts both price and satisfaction, showing that guests pay for better-maintained spaces.

Satisfaction is weakly linked to price, meaning expensive does not always mean better.

Distance reduces satisfaction, especially in cities where the city center is a key attraction.


