# School_District_Analysis
Module 4 - Anaconda, Python, Jupyter Notebook, etc.
# School District Analysis
A school board is asking for the grade outcomes of all the High Schools in its district. An initial School District Analysis was created with Maria, a school board associate, in order to determine those outcomes, which include average reading and math grades, as well as the percentage of students who passed only math, only reading, and both math and reading. Additionally, they asked for a further analysis that showed these grade outcomes according to the school size, school spending per student, and school type (charter or district).  

Once this initial analysis was completed, Maria was notified that there was evidence of academic dishonesty among the Thomas High School ninth grade scores. Per the school board’s request, the analysis was updated to remove the tainted grades for the Thomas High School ninth graders and find the same outcomes as before, this time just not including Thomas High ninth. So, in addition to the results of the initial analysis, there is a second analysis included at the top of the file that contains these new outcomes.

## Seven Major Metrics
There was a total of seven metrics that were determined throughout the school district analysis. The final data frame contains all of those metrics for each school in the district. Here is a list of those metrics:
1.	Per Student Budget
2.	Average Math Score
3.	Average Reading Score
4.	% Passing Math
5.	% Passing Reading
6.	% Overall Passing
7.	Spending Ranges (Per Student)
Continue reading for descriptions as to how those metrics were (or weren’t) changed after replacing the grades of the Thomas High School ninth graders with null values. 

# Results

## District Summary Analysis
After replacing the scores of Thomas High School ninth graders with null values, it is apparent that it didn’t affect the final school district analysis summary very much. Upon calculating the average math and reading scores, as well as the passing percentages of the students, the final numbers showed almost the same as before once they were rounded to the same decimal places as in the first analysis. There was a 0.1-point decrease in the average math scores (rounded to the nearest tenth of a point), but the average reading score along with the percentages (rounded to the nearest whole number) remained the same. This basically means that the average grades of the 9th graders at Thomas High School must have been pretty close to the district averages themselves. Had those 9th graders either excelled or struggled compared to the other students, the removal of their grades would have had a larger impact on the whole district’s averages and percentages. 

## School Summary Analysis
Much like with the district analysis summary, the school summary wasn’t affected much either. The school summary data frame only saw slight changes to Thomas High School’s row of data, but all other rows remained the same. Although there were these slight changes to the Thomas High data, they ultimately weren’t significant enough to affect their placing among the other schools in the district. Even without counting their 9th grade class, Thomas High School still finished second out of the 15 schools in overall passing percentage. Their average scores and passing percentages did change, but never by more than a few tenths of a point/percentage point. This shows that the Thomas 9th graders not only were about average compared to the entire district, but they were also average when comparing them only to the other students in their school only.

## Thomas High School Performance Compared to Other Schools
As was just described and illustrated above, removing the Thomas High 9th grade scores did not impact Thomas High’s overall performance compared to the other schools in the district. Although they obviously would be dead last in a 9th-grade-only comparison (since they have no 9th grade scores), the averages of the remaining 10th-12th graders kept them at the same position in overall average calculations (second place overall). 



### Average Math and Reading Scores by Grade
It is pretty clear that Thomas High School would be last (or just not included altogether) on the list of scores by grade when looking at just 9th grade scores. However, because we only removed the scores of the Thomas 9th graders, the scores for all the other grades were still pretty similar to what they were in the initial analysis. The math scores did change by a few tenths of a point in grades 10-12, but never by more than a half of a point. The reason for their changes is just that we didn’t include the Thomas High ninth graders in the student body when the averages were calculated. However, as was explained before, the grades for Thomas High ninth were just about average for the whole school, so removing them from the total school averages, again, didn’t have much of an effect. As a matter of fact, the reading scores, after being rounded to one decimal place, ended up not changing at all.

### Average Math and Reading Scores Overall
Because the grades of the Thomas High ninth graders (as a whole) were average compared with the rest of the school, replacing their grades with null values had little affect on Thomas High Schools overall average grades. The school’s average reading and math scores changed by a few tenths of a point, but those changes weren’t enough to move Thomas High up or down in the district rankings. It was the same with their passing percentages for math, reading, and overall. They only changed by a few tenths of a percent, if at all. In the end, Thomas High School remained as the school with the second-highest overall passing percentage in the district.

### Scores by School Spending
Removing those 9th grade scores also had a minimal impact on the scores categorized by school spending. Even though the grades themselves were cut out of the data set this second go-round, the students still attended the same school during the same school year, so Thomas still spent the same amount per student regardless of which way this is analyzed. And, as has been established, the 9th grade students performed almost exactly average among not only the rest of the students at their school, but among the other students in the district as well. Ultimately, the impact of replacing the Thomas High ninth grade scores had a very minimal impact on the $630-$644 range (the range which Thomas High School falls in). After rounding the updated numbers to one decimal, the values didn’t actually change at all. 

### Scores by School Size
 Much like with the scores by school spending, removing the 9th grade scores for Thomas High didn’t affect the end results. Thomas High remained a medium sized school, even after removing the ninth graders. So, because they didn’t change size categories and their school’s average scores were minimally impacted, the district scores by school size didn’t change in the final, rounded figures.

### Scores by School Type
As was the story for both the scores by school spending and scores by school size, the scores when categorized by school type didn’t change after being rounded to their end numbers. Once again, because Thomas High ninth graders performed almost exactly average when compared to both their school and the district as a whole, removing their grades had minimal affect on the end results.
