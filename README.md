# Kickstarting_with_Excel

## Review of Kickstarter campaign data for Louise based on Outcomes Based on Launch dates and goals.

### Purpose
To analyze and then create visualization for how different campaigns fared in relation to their launch dates and their funding goals.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
The analysis was performed by looking only at the Theater Parent Category in the Kickstarter data. Then using the Launch dates it was then grouped by month and then the Outcomes for successful, failed and canceled campaigns was added as well. The Live campaigns were removed because we are only looking at campaignst that have been completed. Then a line graph was created to show how the Theater campaigns fared each month. Below is the image with the results for Theather Outcomes versus their Launch months.  

![alt text](https://github.com/sandramcardona/Kickstarting_with_Excel/blob/master/Resources/Theather_Outcomes_vs_Launch.png?raw=true)


### Analysis of Outcomes Based on Goals
The analysis was performed using the funding goals for the subcategory of Plays within the Theather campaigns. A separate sheet was created where the funding goals were separated among different ranges starting at less than $1000 and moving up all the way to greater than $50,000. Then separate columns were created to further review the amount of campaigns that were sucessful, that were canceled and that failed for each of these ranges. Then we created separate columns to find the percentage for each of these outcomes based on the total of campaigns reviewd. Then a line graph was created to show the relationship betwen the Funding Goal ranges and the percentage for each outcome gathered for each campaign. 
The image below show the line graph created for Outcomes versus Funding Goals. 

![alt text](https://github.com/sandramcardona/Kickstarting_with_Excel/blob/master/Resources/Outcomes_vs_Goal.png?raw=true)

### Challenges and Difficulties Encountered
There was one chanllenge encountered when working with the data that was simple yet important to be able to work with the data properly. The formats for the Launched dates that needed to be changed from unix format to month, day and year format. This was done by using the unix conversion formula. This then allow me to use the converted dates for further analysis using the pivot tables and charts. 

Possible challenges that could be encountered when analyzing the Outcomes based on Goals would be to try to determing the goal ranges needed to spread the outcomes so the data can be analyzed properly without missing important clues. If the goal ranges are too close together then we will miss important failures and success marks at different points of the successful and failed campaings. 

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
Two conclusions that can be drawn about the Outcomes based on Launch date are that May and June 

- What can you conclude about the Outcomes based on Goals?

- What are some limitations of this dataset?

- What are some other possible tables and/or graphs that we could create?

