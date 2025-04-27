
# Titanic Dataset Analysis 🚢

This project focuses on **cleaning**, **exploring**, and **analyzing** the famous Titanic dataset to uncover meaningful insights about passenger demographics, survival rates, and fare distribution.

---

## 📁 Project Structure
- **Dataset**: Cleaned Titanic dataset (`Cleaned_Titanic_Dataset.csv`)
- **Notebook**: Complete code and analysis (`Titanic_EDA.ipynb`)
- **Visualizations**: Boxplots, heatmaps, and scatterplots created for better understanding

---

## 📌 Key Steps Performed

### 1. Data Loading and Cleaning
- Loaded the dataset using Pandas
- Set `PassengerId` as the index for easier tracking
- Filled missing values in the `Age` column with the median
- Converted `Sex` to categorical data type
- Removed duplicate entries

### 2. Outlier Detection and Removal
- Visualized `Fare` outliers using a boxplot
- Removed extreme `Fare` outliers using both:
  - Custom Fare Range (10–300)
  - IQR (Interquartile Range) method

### 3. Data Exploration and Analysis
- Analyzed Fare distribution
- Computed correlations between important columns (`Fare`, `Pclass`)
- Created visualizations:
  - Boxplot for Fare
  - Scatterplot for Fare vs Passenger Class
  - Heatmap of Correlation Matrix

### 4. Insights
- Strong negative correlation between `Fare` and `Pclass`
- Higher class passengers paid more; lower class passengers paid less
- Outliers significantly impacted the Fare distribution

---

## 📊 Libraries Used
- **Pandas** for data manipulation
- **Seaborn** and **Matplotlib** for visualization
- **NumPy** for numerical operations

---

## 📝 How to Use
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/Titanic-EDA.git
   ```
2. Open the `Titanic_EDA.ipynb` notebook in Google Colab or Jupyter Notebook.
3. Make sure you have the required libraries installed:
   ```bash
   pip install pandas matplotlib seaborn numpy
   ```
4. Run the notebook cells step-by-step to replicate the analysis!

---

## 📢 Future Improvements
- Build predictive models for survival prediction
- Perform deeper feature engineering
- Deploy an interactive dashboard for Titanic dataset visualization



