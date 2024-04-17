----------------------------------------------------------------------------------------
Netflix Viewing History Projects

This project has 2 parts being manipulating the data as pandas dataframes in Jupyter
Notebook to familiarize myself with the system and using Sql to build a relational
database and execute some generic queries. In the first part I process the data to turn
it into a dataframe, form smaller dataframes to isolate notable data, then print a
couple of graphics to visualize the data. In the second part I connect to a Mysql
workbench to build tables by iterating through the data, and then in a second file I 
generated some queries that you might expect would be run against the database and
output the results as dataframes.
----------------------------------------------------------------------------------------

-How to Run
    The file netflix_viewing.ipynb should run as is with the pandas extension. For the
    other 2 .ipynb files you will need to have Mysql workbench installed including the 
    Python connector. There are a couple of places in both files where I have replaced 
    the password for my workbench with '*****', so if you want to run those files on 
    your own machine, you will need to replace the *'s with your password to your 
    workbench and potentially change some other items such as the host name and user 
    name if they are not the same as mine.