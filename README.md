# Module 7 Project - Linear Regression
## Chelsea Brammer - February 26, 2023

In this module, I'll employ machine learning (ML) and employ a type of supervised learning, simple linear regression, train a model, using all available data and use the resulting model (a best-fit straight line) to make predictions. 

### Task 3
1. Follow the instructions from 10.16 (starting page 414).
2. Note: The data is for the average (daily) high temperature in January over many years.
3. For example, in 1895, the average high temperature in January was 34.2.
4. We only care about this one series of data: the "average high temp in Jan".
5. There's a lot of stats in the title, and it has confused students. Just think of each value as "the temperature" for that year.
6. We'll use all of the data available to build a best-fit line (supervised learning). 
7. We'll use the slope and intercept of the best-fit line to estimate a point out in the future.
8. Use a notebook (rather than interactive mode). 
9. Use pandas DataFrames to plot Celsius vs Fahrenheit 
10. Refresh your understanding of the equation for a line (y=mx +b)
11. Follow the instructions to load NY City January high temperature from a csv file into a DataFrame.
12. Follow the instructions to view head and tail of the file. 
13. Follow the instructions to clean the data.
14. Use describe() to calculate basic descriptive statistics for the dataset. 
15. Use the SciPy stats module linregress function to calculate slope and intercept for the best fit line through the data.
16. Use your results to predict the "average high temp in Jan" for the year 2026. 
17. Follow the instructions and use Seaborn to generate a scatter plot with a best fit line. Set the axes and y limit as instructed.
18. In the same notebook, continue with 15.4 (staring page 620). 
19. This time, we'll use scikit-learn estimator, and we'll practice splitting data for training (to build a model) and testing (testing our model against known values). 
20. Follow the instructions all the way though charting it again with the specified axes.
21. At the end of your notebook add some remarks comparing the two methods. 

### Task 5 - Bonus
1. Practice more machine learning skills by working through 15.5 with the California Housing Dataset.
2. Follow the instructions all the way though loading the data, training and testing the data, visualizing the data, and choosing the best model from the 4 listed. 
3. Customize your presentation and include helpful remarks to "tell a story with data".
4. Execute the notebook.
5. Add/commit/push your changes up to your GitHub repo.