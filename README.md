# Module Two

This module contains Python pandas practice notebooks and datasets covering Series, DataFrames, filtering, handling missing values, grouping, and sorting.

## 📂 Folder Structure

```
module_two/
│
├── padas_basics.ipynb
├── first_1_4questions.ipynb
├── Untitled-1.ipynb
│
├── orders.csv
├── new_file.csv
├── TV_Final.csv
├── tv.csv
│
└── README.md
```

## 📖 Pandas Basics

`padas_basics.ipynb` covers the basics of pandas using `orders.csv`: reading a CSV file, viewing data with `head()`, `tail()`, `info()` and `describe()`, selecting columns, filtering rows, updating values, and dropping rows and missing values.

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
