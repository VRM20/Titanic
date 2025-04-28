# 🚢 Titanic Survival Prediction — Exploratory Data Analysis (EDA)

This project performs a detailed exploratory data analysis (EDA) on the famous **Titanic Dataset** from Kaggle.  
The goal is to uncover important patterns and relationships that influence passenger survival.

---

## 📚 Dataset

- **Source:** [Kaggle Titanic: Machine Learning from Disaster](https://www.kaggle.com/c/titanic/data?select=train.csv&utm_source=chatgpt.com)
- **File used:** `train.csv`

---

## 🔍 Steps Performed

1. **Loading the dataset** using Pandas.
2. **Cleaning the data**:
   - Dropped unnecessary columns (`Name`, `Ticket`).
   - Encoded categorical variables (`Sex`, `Cabin`, `Embarked`) using Label Encoding.
3. **Data exploration**:
   - Used `.info()`, `.describe()`, and `.value_counts()` to understand dataset structure and distributions.
4. **Visualizations**:
   - **Pairplot** to explore pairwise relationships.
   - **Heatmap** to visualize feature correlations.
   - **Histograms**, **Boxplots**, and **Scatterplots** for detailed trend analysis.
5. **Observations and Insights**:
   - Gender, fare, and class strongly influenced survival chances.
   - Higher-class passengers (1st class) and females had higher survival rates.
   - Younger passengers had better chances of survival compared to older ones.
6. **Summary of findings** for clear reporting.

---

## 📊 Visualizations Used

- **Pairplot** (`sns.pairplot`)  
- **Heatmap** (`sns.heatmap`)  
- **Histogram** of Passenger Ages  
- **Boxplot** of Passenger Class vs Age  
- **Scatterplot** of Age vs Fare (colored by Survival)

Each visualization is accompanied by **clear markdown observations** explaining key insights.

---

## 📦 Technologies

- Python 🐍
- Pandas
- Seaborn
- Matplotlib
- Scikit-learn (for Label Encoding)

---

## 📈 Project Highlights

- Full step-by-step EDA workflow, ideal for beginners and intermediate data scientists.
- Proper **markdown documentation** under every code block.
- Cleaned, well-organized, and presentation-ready notebook.

---

## ✍️ How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/titanic-eda.git
   ```
2. Open the Jupyter Notebook or `.py` file.
3. Ensure all required libraries are installed (`pandas`, `seaborn`, `matplotlib`, `sklearn`).
4. Run the notebook to see the full analysis.

---

## 📑 License

This project is open-source and free to use.
