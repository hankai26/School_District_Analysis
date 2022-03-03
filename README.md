# School District Analysis Applying 

# Overview of the school district analysis 
This project is to use Jypyter Notebook as well as the Pandas library combining Python coding to perform the analysis on school and student data in csv files. This analysis prepared the district summary, the school summary, and the school performance evaluation in average scores and passing rates. Multiple programming tools including methods from Panda and NumPy modules were applied to retrieve information, change the data and conduct arithmetic calculations. Further, for special needs this analysis selected the exact information, revised specific numbers in the dataset and recalculated the student scores. The analysis allows us to show how these specific changes affected the overall analysis.

# Results
Based on the requirements of the school board, the district's key metrics and each school metrics were prepared to evaluate how factors affected the school performance, like budget per student, school size and school type. More importantly,  by changing 9th grade scores at Thomas High School, we demonstrate how the critical change affected those analysis results. Logical and comparison operators were applied in the analyzing process to select and revise target data. This project addresses some findings as below.

- How is the district summary affected?
To replace the math and reading scores in 9th grade at Thomas High School (THS) would slightly reduce the average math scores as well as the passing percentage in the entire school district. The overall passing percentage for this school district was reduced from 65.2% to 64.9%.

![district_ori](https://github.com/hankai26/School_District_Analysis/blob/main/Resources/district_original.png)<p align="center">**Figure 1. School District Summary without Score Revision at THS**</p>


![district_challenge](https://github.com/hankai26/School_District_Analysis/blob/main/Resources/district_challenge.png)<p align="center">**Figure 2. School District Summary with Score Revision at THS**</p>


- How is the school summary affected?
Figure 3 and Figure 4 indicate that the subject change in 9th scores at THS would lead to a slight decrease in the average scores at THS and the passing rate accordingly. That explains why the scores and passing percentage in the entire school district were reduced as we found for the district summary in the above paragraph. The average math scores decreased from 83.42 to 83.35. While, the average reading scores increased from 83.85 to 83.90. The overall passing percentage was reduced from 90.95% to 90.63% by the score revision. Those impact to school summary data is smaller than 1%. One thing needs to be noted that the result data was calculated with more precision as needed to compare the slight difference in the following analysis.

![school_sum_THS_ori](https://github.com/hankai26/School_District_Analysis/blob/main/Resources/school_sum_THS_original.png)<p align="center">**Figure 3. School Summary without Score Revision at THS**</p>


![school_sum_THS_challenge](https://github.com/hankai26/School_District_Analysis/blob/main/Resources/school_sum_THS_challenge.png)<p align="center">**Figure 4. School Summary with Score Revision at THS**</p>


- How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
Figure 5 and Figure 6 show the top five schools based on the overall passing performance. The school performance ranking remains same with score replacing at THS. The overall passing percentage at THS slightly reduced to 90.63%, which was still higher than the following school Griffin High School.

![Top_ori](https://github.com/hankai26/School_District_Analysis/blob/main/Resources/TopSchools_original.png)<p align="center">**Figure 5. Top Five Schools without Score Revision at THS**</p>

![Top_challenge](https://github.com/hankai26/School_District_Analysis/blob/main/Resources/TopSchools_challenge.png)<p align="center">**Figure 6. Top Five Schools with Score Revision at THS**</p>

- Replacing the ninth-grade scores affect the following results:
    - Math and reading scores by grade
    The average math and reading score in 9th grade at THS were replaced by NaN and became unavailable after the score was replaced. The scores in other grades remain the same.
    ![math_THS_ori](https://github.com/hankai26/School_District_Analysis/blob/main/Resources/math_THS_original.png)
    
    **Figure 7. Math Scores by Grade without Score Replacement at THS**

    ![math_THS_challenge](https://github.com/hankai26/School_District_Analysis/blob/main/Resources/math_THS_challenge.png)
    
    **Figure 8. Math Scores by Grade with Score Replacement at THS**

    ![reading_THS_ori](https://github.com/hankai26/School_District_Analysis/blob/main/Resources/reading_THS_original.png)
    
    **Figure 9. Reading Scores by Grade without Score Replacement at THS**

    ![reading_THS_challenge](https://github.com/hankai26/School_District_Analysis/blob/main/Resources/reading_THS_challenge.png)
    
    **Figure 10. Reading Scores by Grade with Score Replacement at THS**
    
    - Scores by school spending
    The budget per student at THS is $638, calculated earlier in the school summary table (Figure 3 & 4). Comparing Figure 11 and Figure 12 we could notice that the average math and reading scores for the Schools with spending range of $631 - $645 were slightly different with and without score replacing at THS, changing from 78.52 and 81.62 to 78.50 and 81.64, respectively.
    ![spend_sum_ori](https://github.com/hankai26/School_District_Analysis/blob/main/Resources/spending_sum_original.png)<p align="center">**Figure 11. Math and Reading Scores by School Spending without Score Replacement**</p>

    ![spend_sum_challenge](https://github.com/hankai26/School_District_Analysis/blob/main/Resources/spending_sum_challenge.png)<p align="center">**Figure 12. Math and Reading Scores by School Spending with Score Replacement**</p>

    - Scores by school size
    The total student at THS is 1,635 listed in the school summary table (Figure 3 & 4). Comparing Figure 13 and Figure 14 we could noticed that the average math and reading scores for medium size school (1000 - 2000 students) were slightly different comparing the results before and after score replacing, changing from 83.37 and 83.86 to 83.36 and 83.87, respectively, which was consistent to the school summary analysis.
    
    ![size_sum_ori](https://github.com/hankai26/School_District_Analysis/blob/main/Resources/size_sum_original.png)<p align="center">**Figure 13. Math and Reading Scores by School Size without Score Replacement**</p>

    ![size_sum_challenge](https://github.com/hankai26/School_District_Analysis/blob/main/Resources/size_sum_challenge.png)<p align="center">**Figure 14. Math and Reading Scores by School Size with Score Replacement**</p>

    
    - Scores by school type
    THS is a Charter school as listed in the school summary table (Figure 3 & 4). The change in average math and reading scores after replacing 9th grade scores in different types of schools was consistent with the previous results, showing decrease in math scores and increase in reading scores at Charter schools. The results at District remain the same.

    ![type_sum_ori](https://github.com/hankai26/School_District_Analysis/blob/main/Resources/type_sum_ori.png)<p align="center">**Figure 15. Math and Reading Scores by School Type without Score Replacement**</p>

    ![type_sum_challenge](https://github.com/hankai26/School_District_Analysis/blob/main/Resources/type_sum_challenge.png)<p align="center">**Figure 16. Math and Reading Scores by School Type with Score Replacement**</p>


# Summary

The reading and math scores for the 9th grade at THS have been replaced with NaNs. The subject revision led to slight changes to the math scores and reading scores. The results are well presented in the seven data frame matrixes. Without considering the scores in 9th grade at THS, the average math scores slightly decreased and the average reading scores slightly increased at THS. The passing rate also decreased a little bit. Then change or trend keeps consistent with that in the category of school spending in the range of $631 - $645, and that in the medium size schools (1000-2000 students), as well as that in the Charter school category.

The scores and passing rate with and without score replacement at THS do not show much difference. The school performance ranking also has not changed. It indicates that there's no significant influence on scores and passing rates when replacing the 9th scores at THS.
