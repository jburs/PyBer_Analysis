# PyBer_Analysis Report

## Background and Results

### Purpose
Create a DataFrame that summarizes the key ride-sharing metrics by city type. Display the trends in weekly total fares on a multiple-line graph for each city type. 

### Technical Analysis
Python was used with Pandas, and Numpy to generate the data for the summary. Data for rides, drivers, and fares was summed for each city type, and is displayed in the results tab below. This data was then grouped by date and city type. After sorting into weekly brackets, it was plotted on a multiple-line graph using MatPlotLib. 

### Results
The results are shown below, visualized in the multiple-line plot, and summarized in the dataframe. 
![Fig8.png]( https://github.com/jburs/PyBer_Analysis/blob/master/analysis/Fig8.png)
![summary_df.PNG]( https://github.com/jburs/PyBer_Analysis/blob/master/analysis/summary_df.PNG)

### Summary
Lower fares are seen in the Urban cities, however the huge volume of riders and drivers allows Urban cities to make up roughly 2/3’s of the weekly fares. This is followed by the Suburban, then Rural city types, with riders/drivers decreasing, and fares increasing as we go from larger populations, to small populations. 


## Challenges Encountered and Overcome

### Challenges and Difficulties Encountered

The main challenge when the programing the analysis was manipulating the data frames to have the proper time index. Then sorting the data by city time, and resampling to a sum the fares into weekly amounts. 

The analysis itself went very smoothly, however it can become difficult to keep the numerous data frames organized when creating and reformatting numerous new data frames from multiple pre-existing data frames

The multiple line graph was visualized easily with matplotlib. The challenging part arose when formatting the x-axis to display the months as words instead of shorthand numbers. With some research the axis was formatted, and a link is provided in the code for the reference used. 

### Technical Analyses Used
The documentation for matplotlib and pandas, as well as google was used to overcome the above challenges. 


## Recommendations and Next Steps

### Recommendations for Future Analysis

### Additional Analysis 1

The data can be further transformed into daily trends. 
The previous method can be reused, resampling into daily instead of weekly. This will can produce an analysis that can show the trends in weekday vs weekend, or a Monday-Sunday breakdown. 

### Additional Analysis 2

Top grossing cities within each city type. To create this analysis, we can group the data into city types, then find the total fare for the top few, and bottom few cities within each type. From here we generate summary statistics for each of the top cities, then combine then into three data frames by city type. This will provide insight into the differences between the top and bottom cities within each city type, and potentially allow up to find ways to improve the bottom cities.  

* Technical Steps
