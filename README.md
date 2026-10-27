# Module Two

Practice notebooks and datasets for learning **data analysis with Python**, using **pandas** to work with data and **matplotlib** to draw charts. This is a good starting point if you are new to either library.

## 📚 What You Will Learn

- **pandas:** Series and DataFrames, reading CSV files, selecting and filtering data, handling missing values, renaming columns, grouping, and sorting
- **matplotlib:** line, bar, pie, scatter and histogram charts, plus subplots and chart styling

## 📂 Folder Structure

```
module_two/
│
├── pandas_basics.ipynb
├── first_1_4questions.ipynb
├── matplotlib.ipynb
├── Task-1 pandas.ipynb
├── Task-1 matplotlib.ipynb
├── Task-2.ipynb
├── Task-2 matplotlib.ipynb
├── Task-3 matplotlib.ipynb
├── Task-practice.ipynb
├── tv_task1.ipynb
│
├── orders.csv
├── new_file.csv
├── movies.csv
├── sales_data_sample.csv
├── Task2.csv
├── TV_Final.csv
├── tv.csv
│
├── .gitignore
└── README.md
```

> The `venv/` folder is a local virtual environment on the author's computer. It is not part of the project, so you create your own (see Getting Started).

## 🧭 Which Notebook Should I Open?

Work through them roughly in this order:

| Order | Notebook | What it is |
|---|---|---|
| 1 | `pandas_basics.ipynb` | Introduction to pandas using `orders.csv` |
| 2 | `first_1_4questions.ipynb` | Practice with Series and DataFrames |
| 3 | `matplotlib.ipynb` | Introduction to charts in matplotlib |
| 4 | `Task-1 pandas.ipynb`, `Task-2.ipynb` | Pandas practice tasks |
| 5 | `Task-1 matplotlib.ipynb`, `Task-2 matplotlib.ipynb`, `Task-3 matplotlib.ipynb` | Matplotlib practice tasks |
| 6 | `tv_task1.ipynb` | Pandas exercises on the TV dataset |
| 7 | `Task-practice.ipynb` | Extra practice |

## 🗃️ Datasets

| File | Description |
|---|---|
| `orders.csv` | Order data used in the pandas basics notebook |
| `TV_Final.csv` | Cleaned TV product data (brand, size, rating, operating system, selling price, original price) |
| `tv.csv` | Original TV product data |
| `movies.csv` | Small movie dataset (title, release year, genre, director, budget, revenue, rating) |
| `sales_data_sample.csv` | Sample sales data |
| `Task2.csv` | Data used in the Task 2 notebook |
| `new_file.csv` | Extra practice data |

> **Note:** `movies.csv` is a small practice dataset. Its budget, revenue and rating values are approximate and meant for learning, not for real research.

## 📖 Pandas Basics

`pandas_basics.ipynb` covers the basics of pandas using `orders.csv`:

- Reading a CSV file
- Viewing data with `head()`, `tail()`, `info()` and `describe()`
- Selecting columns
- Filtering rows
- Updating values
- Dropping rows and missing values

## 📊 Matplotlib Basics

`matplotlib.ipynb` covers data visualization with Matplotlib:

- Line plots with different markers, line styles, colors and line widths
- Adding a grid with `grid()`
- Bar chart
- Pie chart
- Scatter plot
- Histogram
- Subplots

## 🛠️ Requirements

- Python 3.8 or newer
- pandas
- matplotlib
- numpy
- Jupyter Notebook, or VS Code with the Jupyter extension

## 🚀 Getting Started

These steps are for Windows. On Mac or Linux, the only change is the activate command (`source venv/bin/activate`).

1. **Clone the repository**
   ```
   git clone https://github.com/shalahthaikkadan/module_two.git
   cd module_two
   ```
2. **Create and activate a virtual environment** (optional but recommended)
   ```
   python -m venv venv
   venv\Scripts\activate
   ```
3. **Install the libraries**
   ```
   pip install pandas matplotlib numpy jupyter
   ```
4. **Open the folder in VS Code** and install the **Python** and **Jupyter** extensions if prompted.
5. **Open a notebook** (`.ipynb` file), click **Select Kernel** at the top right, and choose the `venv` Python environment.
6. **Run the cells from top to bottom** with the ▶ button or `Shift + Enter`.

