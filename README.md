# School_District_Analysis
## Overview of Analysis
An analysis was performed on data from a city school district to determine trends and patterns in school performance and testing proficiency. Math and reading test scores were analyzed, as well as school spending to help the school board make decisions regarding budget allotments. While performing our analysis, we were made aware of signs of academic dishonesty in our data set, specifically among the reading and math grades for Thomas High School ninth-grade students. Thus, these scores were removed from the data set and the rest of our analysis was performed.
	
## Results
- After removing the ninth-grade data from Thomas High School, the percentage of students who passed math, reading, and who passed both slightly decreased. However, the decrease was only between 0.1% and 0.3%. An overview of the district summary after the ninth-grade students have been removed can be seen below:

![This is an image](https://github.com/dsilvaggio/School_District_Analysis/blob/main/Resources/Updated_District_Summary.png) 

- The most noticeable change that occurred after removing the ninth-grade data for Thomas High was in the school summary. With the ninth grade data included, the percent of students passing math, reading, and both at Thomas High was 66.9%, 69.7%, and 65.1% respectively. An image of the school summary before removing the data can be seen below:

![This is an image](https://github.com/dsilvaggio/School_District_Analysis/blob/main/Resources/THS_including_ninth.png)

- After removing the ninth-grade data, these percentages increased to 93.2%, 97%, and 90.6%. This was quite a significant increase in the number of students who passed the two standardized tests, as seen below. Thus, it could be that the percentage of ninth-graders who passed these tests at Thomas High was significantly low enough to pull the percentages down that far. 

![This is an image](https://github.com/dsilvaggio/School_District_Analysis/blob/main/Resources/THS_wo_ninth.png)

- This change in the percentage of students who passed both math and reading standardized tests caused Thomas High School to be ranked as the number two high school in the district when sorted by the overall performance. Previously, they had fallen into the bottom half when their ninth-grade scores were included. 
-   I then proceeded with the rest of my analysis with the ninth-grade test scores from Thomas High removed. When I replace the ninth-grade scores with NaN, they were no longer included in the data frame that showed the math and reading scores by grade. This data frame also had replaced the ninth-grade scores for Thomas High with NaN. I then compared student's test scores to school spending, school size, and school type to see if any trends were affecting how students were scoring on standardized tests. To group schools by their spending budget per student, I first ran a statistical analysis to see the mean and standard deviation. This allowed me to create 4 different categories in which to group the schools by their spending budget per student. I then created a data frame that showed the mean test score percentage for each category group. The data frame with my four different category groups can be seen below:
 
 ![This is an image](https://github.com/dsilvaggio/School_District_Analysis/blob/main/Resources/Scores_By_Spending.png)
 
 Surprisingly, this data frame shows that the schools who spent the least amount of money per student (<$584) actually performed the highest overall on state testing. 
- The next trend I was interested in was whether or not the school size had any influence on student's scores. I again created 3 different categories based on the number of students enrolled at the school and grouped the high schools into one of these three categories. I created a new data frame that showed the mean test score percentage for each test score based on the 3 different categories. This new data frame and the three categories I chose can also be seen below:

![This is an image](https://github.com/dsilvaggio/School_District_Analysis/blob/main/Resources/Scores_By_Size.png)

Based on this chart, I was able to see that the small and medium-sized schools had a much higher overall passing percentage on the state tests than the large schools.
- The last analysis I performed was grouping the schools based on their school type, charter, or district. I created my final data frame that compared these two school types and their mean passing percentage for each test. The charter school's overall passing percentage was much higher than the district school percentage. 

![This is an image](https://github.com/dsilvaggio/School_District_Analysis/blob/main/Resources/Scores_By_School_Type.png)

## Summary
Overall, when replacing the ninth-grade scores at Thomas High with NaN we were able to see a very slight decrease in the math, reading, and overall percentage passing in the district summary. We also saw a significant increase in the percentage of students who passed both math and reading tests at Thomas High School. The increase in the overall passing percentage for Thomas High School cause them to be ranked amongst the top 5 schools when compared by overall performance on the state tests. The data frame that allowed us to view both math and reading scores by grade no longer contained a value for ninth-grade at Thomas High and instead was replaced with NaN as well. 
