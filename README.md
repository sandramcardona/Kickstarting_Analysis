# Kickstarting_with_Excel

## Review of Kickstarter campaign data based on Launch dates and funding goals.

### Purpose
To analyze and visualize how different campaigns fared in relation to their launch dates and their funding goals based on the kickstarter data.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
The analysis was performed by looking only at the Theater Parent Category in the Kickstarter data. A pivot table was created and the Parent Category and the years were used as filters. The Theater parent category was selected as the main filter. For the Pivot Table fields, the Launch dates were added in the rows section, grouped by month, and the Outcomes were added into the column section to look at the data distributed among these fields. The Live campaigns were filtered out from Outcomes because we are only looking at campaignst that have been completed. A line graph was created to show how the Theater campaigns fared each month. Below is the image with the results for Theather Outcomes versus their Launch months.  

![alt text](https://github.com/sandramcardona/Kickstarting_with_Excel/blob/master/Resources/Theather_Outcomes_vs_Launch.png?raw=true)


### Analysis of Outcomes Based on Goals
The analysis was performed using the funding goals for the subcategory of Plays within the Theather campaigns. A separate sheet was created where the funding goals were separated among different ranges starting at less than $1000 and moving up all the way to greater than $50,000. Then separate columns were created to further review the amount of campaigns that were sucessful, that were canceled and that failed for each of these ranges. Then we created separate columns to find the percentage for each of these outcomes based on the total of campaigns reviewd. Then a line graph was created to show the relationship between the Funding Goal ranges and the percentage for each outcome gathered for each campaign. 
The image below show the line graph created for Outcomes versus Funding Goals. 

![alt text](https://github.com/sandramcardona/Kickstarting_with_Excel/blob/master/Resources/Outcomes_vs_Goal.png?raw=true)

### Challenges and Difficulties Encountered
There was one chanllenge encountered when working with the data that was simple yet important to be able to work with the data properly. The formats for the Launched dates needed to be changed from unix format to month, day and year format. This was done by using the unix conversion formula. This then allow me to use the converted dates for further analysis in the pivot tables and charts. 

Possible challenges that could be encountered when analyzing the Outcomes based on Goals would be to try to determing the goal ranges needed to spread the outcomes so the data can be analyzed properly without missing important clues. If the goal ranges are too close together then we will miss important failures and success marks at different points of the successful and failed campaings. 

## Results

Two conclusions that can be drawn about the Outcomes based on Launch date are the best and worst months to launch a theather campaing. One conclusion is that in the months of May and June Theater campaigns perform the best compared to the other months. The second conclusion is that the months of October and December are the months that have done the worst to launch Theather campaigns.
Based on the Outcomes Goals it can be concluded that the best Theater funding goals range from $35,000 to less than $45,000. Meanwhile, the worst funding goals are above $45,000.
The limitations of the dataset is that some of the campaigns are still live so we can't include them in our total findings leaving us with incomplete information. Another limitation is that the data is old as it stops in 2017 and does not represent current economic changes and trends for recent years so we are basing our analysis on information that is not current. 
Other possible tables and graphs that can be created that can help with further understanding the data will be chart and graphs based on percentages and that include the country or countries where the campaign is looking to be released. I would add on the analysis for Outcomes Based another table to analyze the percent of Successful, fail and canceled campagins and then do a line graph of this percentages.  I would also add country as one of the filters in the different tables and based on the country that the campaign is looking to be released create different tables and charts for each to be able to observed if the country affects the launch dates and the funding goal outcomes. 

