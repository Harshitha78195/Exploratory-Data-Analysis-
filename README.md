# Titanic Dataset: Exploratory Data Analysis (EDA)

This project performs **Exploratory Data Analysis (EDA)** on the Titanic dataset to uncover meaningful patterns, trends, and relationships among features related to passenger survival.

---

##  Objective

The primary goal is to use statistical summaries and visualizations to:
- Understand the structure and distribution of the data
- Identify key features that influence survival
- Discover correlations and potential anomalies
- Generate hypotheses for further modeling

---

##  Tools & Technologies

| Tool           | Purpose                         |
|----------------|---------------------------------|
| Python         | Core programming language       |
| Pandas         | Data manipulation               |
| NumPy          | Numerical operations            |
| Seaborn        | Statistical visualization       |
| Matplotlib     | Basic plotting                  |
| Plotly         | Interactive visualizations      |
| Jupyter Notebook | Interactive analysis platform |

---

##  Project Structure


---

##  Key Analyses Performed

- **Summary Statistics**: Mean, median, standard deviation of numerical features
- **Distribution Plots**: Histograms and boxplots to visualize the spread and detect outliers
- **Correlation Matrix**: Identify inter-feature relationships
- **Pairplots**: Visualize pairwise relationships colored by survival
- **Categorical Analysis**: Countplots for survival vs. Sex and Passenger Class
- **Interactive Scatter**: Plotly-based Age vs Fare analysis by survival

---

##  Dataset Description

The dataset includes demographic and travel information for Titanic passengers.  
Each entry includes features like:
- `Pclass`, `Sex`, `Age`, `SibSp`, `Parch`, `Fare`, `Embarked`, and `Survived`

Dataset Source:  
[Kaggle - Titanic: Machine Learning from Disaster](https://www.kaggle.com/c/titanic/data)

---

##  Sample Insights

- **Female passengers** had a notably higher survival rate than males.
- **First-class passengers** were more likely to survive compared to other classes.
- **Fare and Age** distributions are skewed and contain visible outliers.
- **Survival** correlates strongly with `Sex` and `Pclass`.

---

##  How to Run

### 1. Install Dependencies
```bash
pip install pandas numpy matplotlib seaborn plotly
