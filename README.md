# visualization-with-matplotlib

- Study was made on 248 mice, (data has 249 mice in which one duplicate mouse id was dropped to prevent additional errors) who were identified with SCC tumors received treatment with a range of drug regimens. 
- Over the course of 45 days, tumor development was observed and measured.  
- The purpose of this study was to compare the performance of Pymaceuticals’ drug of interest, Capomulin, against the other treatment regimens.

* Prepared the data.
* Generated summary statistics.
* Created bar charts and pie charts.
* Calculated quartiles, find outliers, and create a box plot.
* Created a line plot and a scatter plot.
* Calculated correlation and regression between mouse weight and average tumor volume for the Capomulin.

Analysis:

- Analysis was made by merging mouse metadata and study results. One duplicate mouse id was removed from the data.

- Total number of timepoints for all mice tested is more for capomulin and ramicane.

- Male mice(51%) are more than female mice(49%).

- Analysis was made by getting the greatest time point for each mouse for mice treated with Capomulin, Ramicane, Infubinol, Ceftamin. 

- Infubinol has  potential outliers 36.321346 which lower than the lower bound
 
- line plot was generated for tumor volume vs timepoint for one mouse l509 tumor volume got increased intially and then reduced for capomulin treated drug which indicates that capomulin is working.

- The correlation between mouse weight and average tumor volume for the Capomulin regimen is 0.84 which indicates there is strong correlation. 

