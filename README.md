# Data-Gathering-export-in-Python-

A Jupyter notebook demonstrating how to export a Pandas DataFrame to **CSV, Excel, HTML, JSON, and SQL**
using the IPL ball-by-ball `deliveries.csv` dataset (179,078 rows × 21 columns).

## Topics Covered

1. **Intro** – Loading the dataset with `pd.read_csv()` and preparing a DataFrame.
2. **Export to CSV** – Summarizing batsman runs and pivot tables, then writing them out with `to_csv()`, including the `index=False` trick to drop the extra index column.
3. **Export to Excel** – Single-sheet and multi-sheet exports using `to_excel()` and the `pd.ExcelWriter` context manager.
4. **Export to HTML** – Turning a sixes heatmap pivot table into an embeddable `.html` file for blogs/reports via `to_html()`.
5. **Export to JSON** – Building a batting-team-by-batsman runs matrix and saving it with `to_json()`.
6. **Export to SQL** – Pushing the full DataFrame into a MySQL database using SQLAlchemy's `create_engine()` and `to_sql()`.
   
## Goal
The main goal of this section is to understand how to **export data from Python into different file formats and databases**, such as **CSV,
Excel, HTML, JSON, and SQL**. This helps in storing, sharing, and presenting analyzed data, and prepares it for further use in **reporting, visualization, and data analysis workflows**.
