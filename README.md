# Methods-to-process-excel-data
# Author: Jing Yang
# Contact: jyangcm@connect.ust.hk

This projects include all methods for me to process excel data in R, I uploaded these for recording or may help someone.

For the code "How to calculate the average of 24 sheets in an excel"

Background: There are 24 sheets (also 24 parallels) in an excel. Take two columns of data from each sheet and calculate the average of the 24 parallels. A table with two columns (average) of data will be generated.

For the code "Split the number and name which are in one column to calculate the average of every groups"

Background: Text with names and numbers in the same column, there are four groups of abcd, each group has 6 parallels, 45 times of data are recorded, and the average of the 45 times of data in the four groups of abcd is calculated.

Solution: First manually select the required 45 times of data, cbind() them into a table, then use a for loop to select the numbers, and average each row.
