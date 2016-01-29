# R_pasteRowsBySegment

This Script will paste a number of rows from one column using another column as a groupby field.  

It will take a data frame like below and concatenate the Final.Text values by Segment.

######   Segment    Final.Text        randomValues
###### 1 MA21-01   W1572 (2007)           43
###### 2 MA21-01   W1574 (2007)           50
###### 3 MA21-01    W1727 (2007)           24

The above would become a list.
###### $`MA21-01`
#######[1] "W1572 (2007)" "W1574 (2007)" "W1727 (2007)"

This list is later output as text file using function from user 42 from stackoverflow.
