# 🍷 Wine Quality Analysis — Hypothesis Testing

This project explores whether wine quality ratings (4.7, 4.8, and 4.9) differ significantly in terms of chemical properties like **acidity** and **price**. Statistical testing and visual analysis are used to uncover insights that can assist wine certification boards or sommeliers in understanding what affects wine ratings.

---

## 📊 Dataset

The dataset used is `wines_SPA.csv`, which contains the following key features:
- **Source:** [Kaggle Wine SPA](https://www.kaggle.com/) *(Link not included for copyright compliance)*

- `rating` — Wine rating (target variable)
- `price` — Price of wine
- `acidity` — Chemical measure affecting taste
- Other chemical variables

---

## 🧪 Objectives

- Check normality of `price` and `acidity` across different ratings.
- Use **non-parametric hypothesis testing** to determine if differences are statistically significant.
- Visualize patterns using box plots and correlation matrices.

---

## 📌 Key Methods

- **Shapiro-Wilk Test**: Check if data is normally distributed.
- **Kruskal-Wallis Test**: Identify statistically significant differences between rating groups.
- **Box Plots, QQ Plots**: Visual confirmation of distribution patterns.

---

## 🧠 Key Insights

1. Wines with different ratings show distinct patterns in **price** and **acidity**.
2. The distributions are **not normal**, validating the use of **non-parametric tests**.
3. **Kruskal-Wallis** tests showed significant differences (p < 0.05) in both variables.
4. Higher ratings tend to align with higher or more consistent acidity/price levels.

---

## 📷 Visualizations

### ▶️ Count of Wine Ratings
Shows the frequency distribution of different wine ratings.

![Count of Wine Ratings](images/Count%20of%20Wine%20Ratings%20using%20Analysis.png)

---

### ▶️ Distribution of Price and Acidity
Distribution plots to assess the spread and shape of these key variables.

![Distribution](images/Distribution%20of%20Price%20and%20Acidity.png)

---

### ▶️ QQ Plot of Price and Acidity
Used to check for normality visually.

![QQ Plot](images/QQ%20Plot%20of%20Price%20and%20Acidity.png)

---

### ▶️ Box Plot of Price and Acidity by Rating
Clearly shows differences in medians and spread across different wine ratings.

![Box Plot](images/Box%20Plot%20of%20Price%20and%20Acidity%20by%20Rating.png)

---

### ▶️ Correlation between Numeric Variables
Shows the strength and direction of relationships among numeric features.

![Correlation Matrix](images/Correlation%20between%20Numeric%20Variables.png)

---

### ▶️ Pairwise Relationships
Scatterplot matrix visualizing pairwise correlations between features.

![Pairwise Plot](images/Pairwise%20relationships%20between%20Variables.png)

---

## 💻 Technologies Used

- Python 3
- pandas
- seaborn / matplotlib
- scipy / statsmodels

---
   
## 📬 Let's Connect

- **LinkedIn:** [Indu R](https://www.linkedin.com/in/indu-r-3a3767170/)

- ---

## 🙌 Feedback & Support

If you found this project helpful or interesting, feel free to ⭐ star the repository and share your thoughts. Contributions and suggestions are always welcome!


