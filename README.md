# lannet-coding-test
Data Science test. It contains 3 questions -

1. Write a function in python that inputs a dataframe and identify which columns have date in them. Using these date columns make new columns which are difference between these columns taking 2 at a time. (for instance if there is date1, date2, date3 columns, output should be like date1-date2, date2-date3, date1-date3). For this problem only, print out data in the colab.
Thing to consider
· Date column might have some invalid entries in them
· Date can be of different format throughout the column

2. Write a python function which take a dataframe as input and deals with the issue of outliers in all the continuous variables.
Things to consider:
· It’s up to you on how you want to deal with outliers. You can either remove them or impute them.
· We consider outliers as incorrect entries and not the one which are natural. For example, in the salary column, if there is a value of $1,000,000 then this value can be due to a natural cause (like it’s a salary for a CEO) or it can be a case of incorrect entry (like someone put an extra zero). So, we are only after incorrect entries.
· Function should also identify which columns are continuous so that you can perform outlier removal on these columns
· The code must be very fast so you cannot use multivariate approach which are based on distance calculation between all points.

3. Write a function in python that take dataframe as input and drop columns having Pearson correlation more than 0.85
Thing to consider:
· Code should drop least amount of variable as possible.
