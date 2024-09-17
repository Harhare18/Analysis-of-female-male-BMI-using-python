**Title:- Data Analysis of Male-Fmale BMI_2020**

Implemented various Python libraries like Pandas, Numpy, Seaborn, and Matplotlib for Data Analysis of Male-Female BMI.

**Implented Steps:-**
1. Imported neceaasry packages/libraries of Python.
2. Loading a dataset as .CVS file name df1(female) and df2(male).
3. Get pereview of both dataset using .head() method.
4. Removed extra column "unnamed: 7 from both the dataset.
5. Rename column name to some readble names of both dataset using .rename() method.
6. Get the infp for each column of both dataset using .info().
7. take a look at the statistical analysis of both dataset using .describe() function.
8. After that let's get started with the visualization.
9. Visualize two histogram subplot for female and male weights using matplotlib.pyplot.subplot on a single plot.
10. Box and Whisker plot with two boxes side by side to get comparison between male and female weights.
11. computed basic aggregations of male female weights such as mead, median, standard deviation, variance and skew.
12. Add new calculated column of BMI in female dataset.
13. created a new version of female dataset by calculating zscore of each column.
14. Visualize a scatter plot matrix  of height, weight, waist circumference, hip circumference, and BMI of the female.
15. Compute Pearson’s and Spearman’s correlation coefficients for all pairs of variables of column from above scatter plot.
16. Compute the waist circumference to height ratio and the waist circumference to hip circumference ratio of the male and female participants by adding two more columns to the males and females matrices.
17. Draw a box-and-whisker plot with four boxes side by side, comparing the distribution of the waistto-height ratio and the waist-to-hip ratio of both male and female participants.
18. Advantages and disadvantages of BMI, waist-to-height ratio, and waist-to-hip ratio.
19. Print out the standardised body measurements for the 5 persons with the lowest BMI and the 5 persons with the 5 highest BMI (e.g., call print for a subset of zfemale comprised of 10 chosen rows.) 
