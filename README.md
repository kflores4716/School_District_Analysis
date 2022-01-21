# School_District_Analysis Challenge
Module 4 - Anaconda, Python, Jupyter Notebook, etc.

# School District Analysis
A school board is asking for the grade outcomes of all the High Schools in its district. An initial School District Analysis was created with Maria, a school board associate, in order to determine those outcomes, which include average reading and math grades, as well as the percentage of students who passed only math, only reading, and both math and reading. Additionally, they asked for a further analysis that showed the grade outcomes according to the school size, school spending per student, and school type (charter or district).  

Once this initial analysis was completed, Maria was notified that there was evidence of academic dishonesty among the Thomas High School ninth grade scores. Per the school board’s request, the analysis was updated to remove the tainted grades for the Thomas High School ninth graders and find the same outcomes as before. So, in addition to the results of the initial analysis, there is a second analysis included at the top of the file that contains these new outcomes.

## Seven Major Metrics
There is a total of seven metrics that were determined throughout the school district analysis, and each one is portrayed in at least one of the several data frames throughout the analysis file. Here is a list of those metrics for reference:
1.	District Summary
2.	School Summary
3.	Performance Relative to Other Schools in the District
4.	Math and Reading Scores by grade 
5.	Scores by School Spending 
6.	Scores by School Size 
7.	Scores by School Type 
Below are descriptions as to how those metrics were (or weren’t) changed after replacing the grades of the Thomas High School ninth graders with null values. 

# Results

## - District Summary Analysis

#### Original District Summary

![Original_district_summary](https://user-images.githubusercontent.com/94764735/150594204-061a9c33-b002-450f-bcdc-cab47e370760.png)

#### Updated District Summary

![Updated_district_analysis](https://user-images.githubusercontent.com/94764735/150594235-ff02e150-1fba-4a39-99cc-5e56710d02b7.png)

After replacing the scores of Thomas High School ninth graders with null values, it is apparent that it didn’t affect the final school district analysis summary very much. Upon calculating the average math and reading scores, as well as the passing percentages of the students, the final numbers showed almost the same as before once the decimals were rounded the same as in the first analysis. There was a 0.1-point decrease in the average math scores (rounded to the nearest tenth of a point), but the average reading score along with the percentages (rounded to the nearest whole number) remained the same. This basically means that the average grades of the 9th graders at Thomas High School must have been pretty close to the district averages themselves. Had those 9th graders either excelled or struggled compared to the other students, the removal of their grades would have had a larger impact on the whole district’s averages and percentages. It is also worthwhile to note that there were only 461 total students in the Thomas High School ninth grade class, making up just over 1% of the district’s 39,170-person student body. So even if Thomas ninth graders did excel or struggle more so than they had, it still would have had a very small impact on the entire district’s outcomes.



## - School Summary Analysis

#### Original School Summary

![Original_school_summary](https://user-images.githubusercontent.com/94764735/150594340-1ccc9079-06b0-42cd-800c-64d14a99706a.png)

#### Updated School Summary

![Updated_school_analysis](https://user-images.githubusercontent.com/94764735/150594347-32c05959-8ec1-4f14-a773-15497491e46a.png)

Much like with the district analysis summary, the school summary wasn’t affected much either. The school summary data frame only saw slight changes to Thomas High School’s row of data, and of course all other rows remained the same. Although there were some slight changes to the Thomas High data, they ultimately weren’t significant enough to affect their placing among the other schools in the district. Even without counting their 9th grade class, Thomas High School still maintained a high overall passing percentage. Their average scores and passing percentages did change a bit, but never by more than a few tenths of a point/percentage point. This shows that the Thomas 9th graders were not only about average compared to the entire district, but they were also average when compared to the other students in their school only.



## - Thomas High School Performance Compared to Other Schools

#### Original Highest Performing Schools

![Original_high_performing_schools](https://user-images.githubusercontent.com/94764735/150594454-74a00766-416d-4ee1-9c1b-fa15531bd757.png)

#### Updated Highest Performing Schools

![Updated_High_Performing_Schools](https://user-images.githubusercontent.com/94764735/150594464-f0097a0a-ff7e-494e-ae3c-7e1b326e86cb.png)

As was just described and illustrated above, removing the Thomas High 9th grade scores did not impact Thomas High’s overall performance compared to the other schools in the district. Although they obviously would be dead last in a 9th-grade-only comparison (since they have no 9th grade scores), the averages of the remaining 10th-12th graders kept them at the same position in overall average calculations (second place overall). 



## - Average Math and Reading Scores by Grade

#### Original Math Scores by Grade

![Original_math_scores_by_grade](https://user-images.githubusercontent.com/94764735/150594599-b8ca5713-d0af-4ecc-8906-140d248ddbcd.png)

#### Updated Math Scores by Grade

![Updated_math_scores_by_grade](https://user-images.githubusercontent.com/94764735/150594605-ec9863ba-a0ca-4cae-8ff6-0afce99f7f77.png)

#### Original Reading Scores by Grade

![Original_reading_scores_by_grade](https://user-images.githubusercontent.com/94764735/150594615-9f7c78f8-de3d-4d4e-b0eb-c91214c2fc43.png)

#### Updated Reading Scores by Grade

![Updated_reading_scores_by_grade](https://user-images.githubusercontent.com/94764735/150594626-77fab42e-62c8-4641-ab95-78b44ecb2e1c.png)

Because we only removed the scores of the Thomas 9th graders, and they were just about equal to the school averages, the average scores for the other grades were still pretty close to what they were in the initial analysis. The average math scores did change by a few tenths of a point, but never by more than a half of a point. Descriptive statistics are bound to change at least a little bit when removing part of a data set, but in this case, they remained remarkably similar to what they were before. As a matter of fact, the reading scores, after being rounded to one decimal place, ended up not changing at all.



## - Scores by School Spending

#### Original Scores by School Spending

![Original_spending_summary](https://user-images.githubusercontent.com/94764735/150594944-14ffea85-31da-4d02-973e-04172bad972d.png)

#### Updated Scores by School Spending

![Updated_spending_summary](https://user-images.githubusercontent.com/94764735/150594960-7a14b0e4-a4fd-4906-a5ec-6dff8b8ac480.png)

Even though the ninth graders were cut out of the data set this second go-round, Thomas High School remained in the middle tier of school spending compared to the entire district ($630-$644 per student). And, as has been established, the 9th grade students performed almost exactly average among not only the rest of the students at their school, but among the other students in the district as well. So ultimately, the impact of replacing the Thomas High ninth graders had a very minimal impact on the $630-$644 range. After rounding the updated numbers to one decimal, the values actually didn’t change at all. 



## - Scores by School Size

#### Original Scores by School Size

![Original_size_summary](https://user-images.githubusercontent.com/94764735/150595049-f0a8c120-d63d-44bb-9d09-b9455894e9fb.png)

#### Updated Scores by School Size

![Updated_size_summary](https://user-images.githubusercontent.com/94764735/150595056-a655d20f-ee97-4dc6-9ad7-306359e762ac.png)

Much like with the scores by school spending, removing the 9th graders from Thomas High didn’t affect the end results. Thomas High even remained in the medium sized school grouping. So, because they didn’t change size categories and their school’s average scores were minimally impacted, the district scores by school size didn’t change in the final, rounded figures. Just like what we saw with the scores by school spending.



## - Scores by School Type

#### Original Scores by School Type

![Original_type_summary](https://user-images.githubusercontent.com/94764735/150595111-79724e61-6cf1-448e-af5f-477194cbc2e5.png)

#### Updated Scores by School Type

![Updated_type_summary](https://user-images.githubusercontent.com/94764735/150595123-cc1d0903-4308-4517-ba5e-c6efb3f11c9c.png)

As was the story for both the scores by school spending and scores by school size, the scores when categorized by school type didn’t change after being rounded to their end numbers. Thomas High (still a Charter School) did not affect the overall averages of the Charter Schools in the district with their ninth grader issues. Once again, because Thomas High ninth graders performed almost exactly average when compared to both the school and the district, removing those students had minimal affect on the end results.


# Summary

Although the impact of removing the scores of the Thomas High School ninth graders was minimal, there still were some slight changes to the average scores and passing percentages. As can be seen in the District Analyses just above this paragraph, the unrounded numbers each changed by a few tenths of a point or percentage. The changes to these district numbers were as follows:

-	Average Math Score: This score dropped by about 0.05 points. Although the change is still very minimal, this shows that the Thomas High ninth graders had math scores that were slightly above average.
-	Average Reading Score: This score dropped by about 0.02 points. Again, though the change is small, it means that the Thomas High ninth graders also had reading scores slightly above average.
-	% Passing Math: This dropped by about 0.22%. Since we established that Thomas High ninth graders had above-average math scores (slightly), it only makes sense that the percentage of students passing math would decrease slightly as well.
-	% Passing Reading: This dropped by about 0.15%. Because Thomas High ninth graders were also just above average in reading scores, this drop in the percentage of students passing reading makes sense as well.
-	Due to the drop in passing percentage for both math and reading, the overall passing percentage for the district slightly dropped as well.

With these four major metrics dropping ever-so-slightly in the updated district analysis, it is apparent that Thomas High ninth graders had slightly better grades compared to the rest of the district. is possible that their above-average scores may have something to do with the suspected academic dishonesty that spurred this updated analysis. However, because the supposedly tainted scores were not enough to make a significant difference in the school district’s overall performance, it seems that the academic dishonesty may not be such a big issue in the end.
