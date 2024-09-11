# Excel-challenge
Assignment 1

## Crowdfunding Campaign Analysis ##

### Project Overview ###
This project involves modifying and analyzing sample-project data from an Excel workbook to uncover market trends in crowdfunding campaigns. The analysis includes creating new columns, applying conditional formatting, generating pivot tables and charts, and performing statistical analysis:

**Conditional Formatting:**
- Fill each cell in the outcome column with a different color based on whether the campaign was successful, failed, cancelled, or is currently live.

**New Columns:**
- Percent Funded: Calculate how much money a campaign made relative to its initial funding goal. Apply a three-color scale conditional formatting (red at 0, green at 100, blue at 200).
- Average Donation: Calculate the average amount each project backer paid.
- Parent Category and Sub-Category: Split the Category and Sub-Category column into two separate columns.

**Pivot Tables and Charts:**
- Create a pivot table to count the number of campaigns that were successful, failed, cancelled, or are currently live per category. Generate a stacked-column pivot chart that can be filtered by country.
- Create another pivot table to count the number of campaigns that were successful, failed, cancelled, or are currently live per sub-category. Generate a stacked-column pivot chart that can be filtered by country and parent category.

**Date Conversion:**
- Convert Unix timestamps in the deadline and launched_at columns to Excel’s date format. Create new columns named Date Created Conversion and Date Ended Conversion for these conversions.

**Additional Pivot Table and Chart:**
- Create a pivot table with a column of outcome, rows of Date Created Conversion, values based on the count of outcome, and filters based on parent category and years. Generate a pivot-chart line graph to visualize this table.

### Report ###

**Create a report in Microsoft Word answering the following questions:**
- What are three conclusions that can be drawn about crowdfunding campaigns?
- What are some limitations of this dataset?
- What are some other possible tables and/or graphs that could be created, and what additional value would they provide?

### Additionals ###

**Goal Analysis:**
- Create a new sheet with columns for Goal, Number Successful, Number Failed, Number Cancelled, Total Projects, Percentage Successful, Percentage Failed, and Percentage Cancelled.
- Populate these columns using the COUNTIFS() formula and calculate the percentages.
- Create a line chart to graph the relationship between goal amount and chances of success, failure, or cancellation.

**Statistical Analysis:**
- Evaluate the number of backers of successful and unsuccessful campaigns by creating a summary statistics table.
- Calculate the mean, median, minimum, maximum, variance, and standard deviation for the number of backers.
- Determine whether the mean or median better summarizes the data and if there is more variability with successful or unsuccessful campaigns.

### Conclusion ###
This project provides insights into the trends and factors affecting the success of crowdfunding campaigns. By analyzing the data and creating visualizations, we can better understand the dynamics of crowdfunding and identify areas for improvement.