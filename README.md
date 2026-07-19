# Clean and Visualize Real-World Data

## Titanic Dataset - Data Cleaning & Visualization

This repository contains my solution for the **Clean and Visualize Real-World Data** assignment as part of the **Neurofive Machine Learning Track**.

The project demonstrates how to clean real-world data, handle missing values, detect outliers, and create meaningful visualizations before building machine learning models.

---

## Project Structure

```
clean-and-visualize-real-world-data/
│
├── .venv/
├── .gitignore
├── .python-version
├── clean-and-visualize-titanic-data.ipynb
├── main.py
├── pyproject.toml
├── README.md
├── train.csv
└── uv.lock
```

---

## Dataset

- **Name:** Titanic - Machine Learning from Disaster
- **Source:** Kaggle
- **File:** `train.csv`

---

## Technologies Used

- Python 3.11
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## Project Objectives

- Load and explore the Titanic dataset
- Identify missing values
- Clean the dataset
- Detect outliers
- Create data visualizations
- Analyze which features influence passenger survival

---

## Data Cleaning

The following preprocessing steps were performed:

- Filled missing values in the **Age** column using the median.
- Filled missing values in the **Embarked** column using the mode.
- Removed the **Cabin** column due to a large number of missing values.
- Verified that the cleaned dataset contains no remaining missing values.

---

## Visualizations

The notebook includes the following visualizations:

- Histogram (Age Distribution)
- Boxplot (Fare Outliers)
- Bar Chart (Survival by Gender)
- Correlation Heatmap

These visualizations help understand the dataset before applying machine learning techniques.

---

## Key Findings

- The **Fare** column contains several outliers.
- Female passengers had a significantly higher survival rate than male passengers.
- Passenger class also influenced survival.
- Most passengers were between 20 and 40 years old.
- The cleaned dataset is ready for further machine learning analysis.

---

## Files

| File | Description |
|------|-------------|
| `clean-and-visualize-titanic-data.ipynb` | Complete notebook containing data cleaning, visualization, and analysis |
| `train.csv` | Titanic dataset |
| `README.md` | Project documentation |

---

## How to Run

Clone the repository:

```bash
git clone https://github.com/<your-username>/clean-and-visualize-real-world-data.git
```

Navigate to the project folder:

```bash
cd clean-and-visualize-real-world-data
```

Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

Start Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```
clean-and-visualize-titanic-data.ipynb
```

Run all cells to reproduce the analysis.

---

## Learning Outcomes

Through this project, I learned how to:

- Work with real-world datasets
- Handle missing values effectively
- Detect outliers using boxplots
- Create informative visualizations
- Perform exploratory data analysis (EDA)
- Interpret patterns before building machine learning models

---

## Author

**Muhammad Faiz Rasheed**

BS Computer Science Graduate

Aspiring Machine Learning Engineer

---

## Acknowledgements

- Kaggle for providing the Titanic dataset.
- Neurofive Solutions for the Machine Learning Track assignment.