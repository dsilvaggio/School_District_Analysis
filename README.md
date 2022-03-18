# School_District_Analysis
## Overview of Analysis
An analysis was performed on data from a city school district in order to determine trends and patterns in school performance and testing proficiency. Math and reading test scores were analyzed, as well as school spending in order to help the school board make decisions regarding budget allotments. While performing our analysis, we were made aware of signs of academic dishonestly in our data set, specifically  among the reading and math grades for Thomas High School ninth grade students. Thus, these scores were removed from the data set and the rest of our analysis was performed.
	
## Results
- After removing the ninth grade data from Thomas High School, the percentage of students who passed math, reading, and who passed both slightly decreased. However, the decrease was only between 0.1% and 0.3%. An overview of the district summary after the ninth grade students have been removed can be seen below:

![This is an image](https://github.com/dsilvaggio/School_District_Analysis/blob/main/Resources/Updated_District_Summary.png) 

- The most noticeable change that occured after removing the ninth grade data for Thomas High was in the school summary. With the ninth grade data included, the percent of students passing math, reading, and both at Thomas High was 66.9%, 69.7%, and 65.1% respectively. An image of the school summary before removing the data can be seen below:

![This is an image](https://github.com/dsilvaggio/School_District_Analysis/blob/main/Resources/THS_including_ninth.png)

- After removing the ninth grade data, these percents increased to 93.2%, 97%, and 90.6%. This was quite a significant increase in the amount of students who passed the two standardized tests, as seen below. Thus, it could be that the perecentage of ninth graders who passed these tests at Thomas High must was significantly low enough in order to pull the percentages down that far. 

![This is an image](https://github.com/dsilvaggio/School_District_Analysis/blob/main/Resources/THS_wo_ninth.png)

- This change in the percent of students who passed both the math and reading standardized tests caused Thomas High School to be ranked as the number two high school in the district when sorted by the overall performance. Previously, they had fallen into the bottom half when their ninth grade scores were included. 
-   When I replace the ninth grade scores with NaN, they were no longer included in the data frame that showed the math and reading scores by grade. This data frame also had replaced the ninth grade scores for Thomas High with NaN. I also noticed that the data frames that compared scores by school spending, school size, and school type were relatively unaffected. 

## Summary
Overall, when removing the ninth grade scores and replacing them with NaN we were able to see a very slight decrease in the math, reading, and overall percentage passing in the district summary. We also saw a significant increase in the percentage of students who passed both the math and reading tests at Thomas High School. The increase in the overall passing percentage for Thomas High School cause them to be ranked amongst the top 5 schools when compared by overall performance on the state tests. Our data frame that allowed us to view both math and reading scores by grade no longer contained a value for ninth grade at Thomas High and instead was replaced with NaN as well. 
