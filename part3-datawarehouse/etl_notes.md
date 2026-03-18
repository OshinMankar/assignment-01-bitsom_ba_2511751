## ETL Decisions

### Decision 1 — Standardizing Date Formats  
Problem: The dataset had dates written in different formats like 29/08/2023, 12-12-2023, and 2023-02-05. Because of this, it would be difficult to sort or analyze data based on time.
Resolution: All the dates were converted into one common format (YYYY-MM-DD) so that it becomes easy to filter, sort, and use them in analysis.

### Decision 2 — Fixing Category Casing  
Problem: The product category names were not consistent. Some were written as "electronics", some as "Electronics", and some in all caps like "ELECTRONICS".
Resolution: All category values were cleaned and converted into one standard format like "Electronics", "Clothing", and "Groceries" to avoid confusion during grouping and analysis.

### Decision 3 — Calculating Revenue  
Problem: The dataset did not have a revenue column, which is important for analysis.
Resolution: A new column called revenue was created by multiplying units_sold with unit_price, so that sales performance can be analyzed properly.
