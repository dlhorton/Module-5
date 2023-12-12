# Mouse Cancer Study Data Analysis

This repository contains the analysis of a mouse cancer study dataset. The dataset includes information about various drug regimens, mouse characteristics, and tumor volume measurements over time.

## Overview

The data analysis covers a range of tasks, including data cleaning, statistical analysis, and visualization. Here's a brief summary of the key findings:

1. **Number of Mice:**
   - There are 249 unique mouse IDs in the dataset.

2. **Duplicate Mice:**
   - Mouse ID 'g989' has duplicate entries at the same timepoints, indicating potential data entry errors.

3. **Cleaned DataFrame:**
   - A clean DataFrame (`clean_df`) is created by dropping the duplicate mouse entries.

4. **Summary Statistics:**
   - Summary statistics (mean, median, variance, standard deviation, and SEM) of the tumor volume for each drug regimen are calculated. The advanced method and aggregation method produce the same results.

5. **Bar Plots:**
   - Bar plots using both Pandas and Pyplot show the total number of rows (Mouse ID/Timepoints) for each drug regimen. The Pyplot version includes rotated x-axis labels.

6. **Pie Plots:**
   - Pie plots using both Pandas and Pyplot show the distribution of female versus male mice.

7. **Quartiles, Outliers, and Boxplots:**
   - The final tumor volume for selected regimens (Capomulin, Ramicane, Infubinol, and Ceftamin) is analyzed for potential outliers. Boxplots are generated to visualize the distribution of tumor volume for each treatment group.

8. **Line Plot:**
   - A line plot of tumor volume vs. time point is generated for a single mouse treated with Capomulin.

9. **Scatter Plot:**
   - A scatter plot of mouse weight vs. the average observed tumor volume for the entire Capomulin regimen is created.

10. **Correlation and Regression:**
    - The correlation coefficient between mouse weight and average observed tumor volume for the entire Capomulin regimen is calculated. A linear regression model is plotted to visualize the relationship between mouse weight and tumor volume.
