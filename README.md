# School_District_Analysis
## Overview of the school district analysis
The school board has notified Maria and her supervisor that the students_complete.csv file shows evidence of academic dishonesty of reading and math grades for Thomas High School ninth graders. Although the school board does not know the full extent of the academic dishonesty, they want to uphold state-testing standards and asked to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact. Maria also request a report of how these changes affected the overall analysis.
## Results
 - __How is the district summary affected?__  
 ![district_summary](https://github.com/JosephineYang228/School_District_Analysis/blob/c9a1f7497de080e285fb7e1984da006dd5be2746/Resources/image/district_summary.png)  
 Since we just replaced the 9th graders' score into NaN, the total number of students stay the same, but the average math score change into 78.9 and the revised reading score is 81.9. The percentage of 10th to 12th Thomas graders who pass the math and reading test is 74.8% and 85.7% respectively. Only 64.9% of these graders passed both 2 tests.  
 
 - __How is the school summary affected?__  
![top](https://github.com/JosephineYang228/School_District_Analysis/blob/5f3d96f993bfd670d121e393c656a19b68caf76f/Resources/image/top.png)  
Since we have removed all the 9th graders' info from the csv, I believe the school ranking has not changed. Thomas High School is still the second best school in this distict. 
 
 - __How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?__  
 ![school_summary_o](https://github.com/JosephineYang228/School_District_Analysis/blob/18a32ec3ae4f13b06a5d974987792168ce654f54/Resources/image/school_summary_o.png) 
 ![school_summary_rv](https://github.com/JosephineYang228/School_District_Analysis/blob/18a32ec3ae4f13b06a5d974987792168ce654f54/Resources/image/school_summary_rv.png)  
 It's clear that replace 9th graders' score into NaN could not display the overall performance of Thomas High School fairly. The 10th to 12th graders did a good job in the test that, 90.6% of them pass both of the tests.  
 
 - __How does replacing the ninth-grade scores affect the following:__
   - __Math and reading scores by grade__  
   I believe the only changes after replacement is just the 9th graders at Thomas High School have Nan instead of a grade for both math and reading.  
   
   - __Scores by school spending__  
   ![spending_ranges](https://github.com/JosephineYang228/School_District_Analysis/blob/5f3d96f993bfd670d121e393c656a19b68caf76f/Resources/image/spending_ranges.png)  
   It's interesting to find it seems the more spending per student the less score they get in the tests. Maybe $584 could be consider as a good per student spending.  
   
   - __Scores by school size__  
   ![size_summary](https://github.com/JosephineYang228/School_District_Analysis/blob/5f3d96f993bfd670d121e393c656a19b68caf76f/Resources/image/size_summary.png)  
   It's clear that small size schools do better than the larger ones. Students may have more attentions from the teachers which would benefit to their school performance.  
   
   - __Scores by school type__  
   ![type_summary](https://github.com/JosephineYang228/School_District_Analysis/blob/5f3d96f993bfd670d121e393c656a19b68caf76f/Resources/image/type_summary.png)  
   Since Charter schools have a 36% higher overall passing percentage than District schools.The performance of Charter schools is much better than Distict schools. 
## Summary
Relacing the 9th graders' scores with NaN caused Thomas High School's overall passing percentages and average scores to plummet. However, after removing all info of Thomas High School 9th graders, Thomas High School regained its high average scores and retained its position as the number two school in the District. It seems replacement is not a good method in this case.
## Others
This challenge is really hard for me when I was just in the 4th week of this Bootcamp. Thus I choose to skip it at that time. However, after I finished all other work and turn back to this case, things is not challenging for me anymore. I believe it's a good thing to prove my pandas' knowledge is much better than 4 months ago. :)
