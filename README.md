# Tidying-Data

#Code Book:
Features - This is the feature file from UCI
Activity_Labels - This function serves to et nmaes/labels for the columns.
subject_test - This provides the results/numbers for the subject tests which will be assigned to each column.
x_test - This specifically codes the x/row values specifically.
y_test - This specifically codes the y/column values specifically.
subject_train, x_train, y_train - The string of values necessary to perform grepl and gsubs on the data along with strsplit.

The script checks for an archive, then a folder. Then, it assigns values to each variable, binding x and y together and naming each column based on the machine learning data.
Then, using the write.Table function, it creates a table for the final result.
