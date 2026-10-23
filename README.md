# Module Two

This module contains Python pandas and matplotlib practice notebooks and datasets covering Series, DataFrames, filtering, handling missing values, grouping, sorting, and data visualization.

## 📂 Folder Structure

```
module_two/
│
├── padas_basics.ipynb
├── first_1_4questions.ipynb
├── Untitled-1.ipynb
├── matplotlib.ipynb
├── movies_analysis.ipynb
│
├── orders.csv
├── new_file.csv
├── TV_Final.csv
├── tv.csv
├── movies.csv
│
└── README.md
```

## 🛠️ Requirements

- Python 3
- pandas
- matplotlib
- numpy
- Jupyter Notebook, or VS Code with the Jupyter extension

Install the libraries with:

```
pip install pandas matplotlib numpy
```

## 📖 Pandas Basics

`padas_basics.ipynb` covers the basics of pandas using `orders.csv`: reading a CSV file, viewing data with `head()`, `tail()`, `info()` and `describe()`, selecting columns, filtering rows, updating values, and dropping rows and missing values.

## 📊 Matplotlib Basics

`matplotlib.ipynb` covers data visualization with Matplotlib:

- Line plots with different markers, line styles, colors and line widths
- Adding a grid with `grid()`
- Bar chart
- Pie chart
- Scatter plot
- Histogram
- Subplots

## 💻 Series and DataFrame Exercises

`first_1_4questions.ipynb` contains the following questions.

**Question 1**
Create a Series from a list. Use `loc[]` and `iloc[]` to access elements, and filter elements greater than 25.

**Question 2**
Create a Series from a dictionary. Use `loc[]` and `iloc[]` to access elements, and filter values greater than 20.

**Question 3**
Create a DataFrame with columns Name, Age and City. Print the entire DataFrame, a row using `loc[]`, and a row using `iloc[]`.

**Question 4**
Filter DataFrame rows where Age > 28 and where City == "Delhi".

## 📝 TV Dataset Exercises

`Untitled-1.ipynb` contains the following questions, based on `TV_Final.csv`.

**Question 1**
Display all rows where the Brand is "SAMSUNG" and the Selling Price is less than 50000.

**Question 2**
Display only the Brand, Size and Rating columns for HD LED products where the Operating System is "Android" and Rating is greater than or equal to 4.0.

**Question 3**
Drop all rows where the Rating column has NaN values.

**Question 4**
Replace all NaN values in the Operating System column with "Unknown".

**Question 5**
Rename the column "Selling Price" to "Current Price" and "Original Price" to "MRP".

**Question 6**
Find how many HD LED products are available for each Brand using `value_counts()`.

**Question 7**
Group the DataFrame by Brand, calculate the sum and average of the price for each brand, and sort in descending order of average price.

**Question 8**
Sort the DataFrame by Current Price in ascending order and then by Rating in descending order.

**Question 9**
Find the top 3 brands with the highest total selling price.

## 🎬 Movie Dataset Analysis (Pandas + Matplotlib)

`movies_analysis.ipynb` uses `movies.csv` to answer the questions below with pandas for the calculations and matplotlib for the charts.

### Dataset columns

| Column | Description |
|---|---|
| `title` | Movie name |
| `release_year` | Year the movie was released |
| `genre` | Main genre |
| `director` | Director's name |
| `budget_million` | Budget in millions of USD |
| `revenue_million` | Box office revenue in millions of USD |
| `rating` | IMDb-style rating out of 10 |

> **Note:** `movies.csv` is a small practice dataset. The budget, revenue and rating values are approximate and are meant for learning, not for real research.

### Questions

**Question 1**
Which movie genres generate the highest average revenue? Use `groupby()` and `mean()`, and show the result as a bar chart.

**Question 2**
Is there a correlation between a movie's budget and its revenue? Use `corr()` and a scatter plot.

**Question 3**
Which movies were the most profitable (Revenue – Budget)? Create a `profit` column, sort it with `sort_values()`, and show the top movies.

**Question 4**
Do movies with higher ratings earn more at the box office? Use `corr()` and a scatter plot of rating vs revenue.

**Question 5**
Which directors consistently produce high-rated movies? Group by director, calculate the average rating, and sort in descending order.

**Question 6**
How has the number of movies released per year changed over time? Use `value_counts()` on the release year and show a line chart.

**Question 7**
Which genre is trending recently (highest growth in number of releases)? Count the movies per genre per year using `groupby()`, then compare recent years with earlier years.

## ▶️ How to Run

1. Clone the repository:
   ```
   git clone https://github.com/shalahthaikkadan/module_two.git
   ```
2. Open the folder in VS Code.
3. Open any `.ipynb` notebook.
4. Keep the CSV files in the same folder as the notebooks, then run the cells from top to bottom.
