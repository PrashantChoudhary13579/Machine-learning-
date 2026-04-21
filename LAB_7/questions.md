On Movies dataset:

Perform following operations;

1. Find the percentage of Missing values in each column.
2. For Columns, "country"and "rating", Replace the Missing value with Most probable value.
3. For "Date_Added" column, Replace NaN with any date in the "Release year" . if Release Year is also  NaN, then drop the row.
4. From Date_Added, Create new columns 'Year_Added' and'Month _Added'.
5. Discretize Rating column into three values only ("Kid", "teen" , "Adult").
6. Plot the number of movies in each rating group by each country.
7. Change the Listed-In column to single valued column by creating multiple columns foe each unique value in that column.
7.Drop all the columns with large number of distinct values and label encode rest of the columns.
8. perform correlation analysis on the rest of the labels.