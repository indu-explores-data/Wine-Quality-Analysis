# 🍷 Wine Quality Analysis — Hypothesis Testing

This project explores whether wine quality ratings (4.7, 4.8, and 4.9) differ significantly in terms of chemical properties like **acidity** and **price**. Statistical testing and visual analysis are used to uncover insights that can assist wine certification boards or sommeliers in understanding what affects wine ratings.

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

## 🔍 Key Insights & Outcomes
- Wines with different ratings show distinct patterns in **price** and **acidity**.
- The distributions are **not normal**, validating the use of **non-parametric tests**.
- **Kruskal-Wallis** tests showed significant differences (p < 0.05) in both variables.
- Higher ratings tend to align with higher or more consistent acidity/price levels.
- Wine ratings are significantly associated with chemical properties, suggesting that quality is influenced by measurable factors.
- Variability in price and acidity indicates that both factors contribute differently to perceived quality.
- Visualizations such as box plots and pairwise plots clearly illustrate differences among rating groups.
- These insights can help sommeliers, wine producers, and certification boards make informed decisions.

---

## 💻 Technologies Used

- Python 3
- pandas
- seaborn / matplotlib
- scipy / statsmodels
- **Environment:** Jupyter Notebook

---

## 💻 Setup & Installation Instructions

Follow these steps to set up the project locally and run the analysis:

**1. Clone the Repository:**
Open a terminal or command prompt and run:  
   ```bash
   git clone https://github.com/indu-explores-data/Wine-Quality-Analysis.git
   ```
**2. Navigate to the Project Directory:**
   ```
   cd Wine-Quality-Analysis
   ```
**3. Create and Activate a Virtual Environment (Recommended):**
   ```
   python -m venv venv
   ```
   **Windows:**
   ```
   venv\Scripts\activate
   ```
   **Mac/Linux:**
   ```
   source venv/bin/activate
   ```
**4. Install Required Libraries:**
   ```
   pip install pandas seaborn matplotlib scipy statsmodels jupyter
   ```
**5. Launch Jupyter Notebook:**
   ```
   jupyter notebook
   ```
**6. Open `Wine_Quality_Analysis.ipynb` and run all cells to reproduce the analysis.**

----

## ▶️ Usage / How to Run

- Open **Wine_Quality_Analysis.ipynb** in Jupyter Notebook.
- Run all cells sequentially to reproduce the analysis.
- Visualizations and statistical results are embedded within the notebook.
- Key insights can be found in the final sections and the images/ folder.

---

## 🔗 Connect with Me

Let’s connect on LinkedIn for project discussions or data-driven collaborations:

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Profile-blue?logo=linkedin)](https://www.linkedin.com/in/indu-r-3a3767170/)

---

## 🙌 Feedback & Support

If you found this project helpful, please ⭐ star the repository and share your thoughts. Suggestions and contributions are always welcome!
