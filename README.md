# Streaming Platform Exploratory Data Analysis (EDA)

## Project Overview

This project performs Exploratory Data Analysis (EDA) on a Streaming Platform dataset using Python, Pandas, Matplotlib, and Seaborn.

The goal is to understand user behavior, content preferences, customer engagement, subscription trends, ratings, and correlations among different variables.

---

## Dataset Features

The dataset contains the following columns:

- User_ID
- Age
- Gender
- City
- Subscription_Type
- Monthly_Fee
- Watch_Hours
- Movies_Watched
- Series_Watched
- Favorite_Genre
- Rating_Given
- Device
- Membership_Years
- Cancelled

---

## Objectives

This project answers important business questions such as:

- What is the distribution of watch hours?
- Which subscription plan is most popular?
- Which genre attracts the largest audience?
- Do users who watch more content give higher ratings?
- Which factors influence customer satisfaction?
- Which subscription plan generates the highest engagement?
- Are there outliers in viewing behavior?
- What relationships exist between numerical features?

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Visualizations Used

### Distribution Analysis

- Histplot
- KDE Plot

### Categorical Analysis

- Countplot
- Barplot

### Relationship Analysis

- Scatterplot
- Regplot
- Jointplot

### Trend Analysis

- Lineplot

### Outlier Detection

- Boxplot
- Violinplot

### Correlation Analysis

- Heatmap
- Pairplot

### Detailed Observation Analysis

- Stripplot
- Swarmplot

### Multi-dimensional Analysis

- Catplot

---

## Key Insights

### User Engagement

- Premium users generally watch more content.
- Watch hours positively correlate with ratings.

### Customer Satisfaction

- Most ratings are concentrated between 4 and 5.
- Higher engagement often leads to higher ratings.

### Content Preferences

- Certain genres consistently attract larger audiences.
- Some genres receive more favorable ratings.

### Customer Retention

- Lower watch hours are associated with higher cancellation rates.

---

## How To Run

Clone repository:

```bash
git clone https://github.com/Uday-Bholane/Streaming-Platform-EDA.git
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Open notebook:

```bash
jupyter notebook
```

Run:

```text
Streaming-Platform-EDA/Streaming_Platform_EDA.ipynb
```

---

## Author

MCA Student | Aspiring Data Science & Full-Stack Developer

GitHub: https://github.com/Uday-Bholane
