# School District Analysis Applying 

# Overview of the school district analysis 
This project is to use Jypyter Notebook as well as the Pandas library combining Python coding to perform the analysis of school and student data in csv files. This analysis prepares the district summary, the school summary, and the school performance evaluation in average scores and passing rates. Multiple programming tools including methods from Panda and NumPy module were applied to retrieve information, change the data and conduct arithmatic calculations. Further, for special needs this analysis selected the exact information, revised specific numbers in the dataset and recalculated the student scores. The analysis allows to show how these specific changes affected the overall analysis.

# Results
Based on the requirements of the school board, the district's key metrics and each school metrics were prepared to evaluate how factors affect the school performance, like budget per student, school size and school type. More important,  by changing 9th grade scores at Thomas High School, we demonstrate how the critical change affect those analysis results. Logical and comparison operators were applied in the analyzing process to select and revise target data. This project addresses some findings as below.

- How is the district summary affected?
To remove the math and reading scores in 9th grade at Thomas High School (THS) would slightly reduce the average scores as well as the passing pencentage in the entire school disctrict. The overall passing percentage for this school disctrict was reduced from 65.2% to 64.9%.

![district_ori](https://github.com/hankai26/School_District_Analysis/blob/main/Resources/district_original.png)<p align="center">Figure 1. School District Summary without Score Revision at THS</p>

![district_challenge](https://github.com/hankai26/School_District_Analysis/blob/main/Resources/district_challenge.png)
Figure 2. School District Summary with Score Revision at THS


- How is the school summary affected?
The Figure 3 and Figure 4 indicate that the subject change in 9th scores at THS would lead to a slight decrease in the average scores at THS and the passing rate accordingly. That explains why the scores and passing percentage in the entire school district were reduced as we found for the district summary in the above paragraph. The average math and reading scores were changed from 83.42 and 83.85 to 83.35 and 83.90, respectively. The overall passing percentage was reduced from 90.95% to 90.63% by the score revision. Those impact to school summary data is smaller than 1%. One thing needs to be noted that the result data was calculated with more precision to compare the slight difference in the following analysis.

![school_sum_THS_ori](https://github.com/hankai26/School_District_Analysis/blob/main/Resources/school_sum_THS_original.png)
Figure 3. School Summary without Score Revision at THS


![school_sum_THS_challenge](https://github.com/hankai26/School_District_Analysis/blob/main/Resources/school_sum_THS_challenge.png)
Figure 4. School Summary with Score Revision at THS


- How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
The Figure 5 and Figure 6 show the top five schools based on the overall passing performance. The school ranking remains same with score replacing at THS. The overall passing percentage at THS slightly reduced to 90.63%, which was still higher than the following school Griffin High School.

![Top_ori](https://github.com/hankai26/School_District_Analysis/blob/main/Resources/TopSchools_original.png)
Figure 5. Top Five Schools without Score Revision at THS

![Top_challenge](https://github.com/hankai26/School_District_Analysis/blob/main/Resources/TopSchools_challenge.png)
Figure 6. Top Five Schools with Score Revision at THS

- Replacing the ninth-grade scores affect the following results:
    - Math and reading scores by grade
    
    ![math_THS_ori](https://github.com/hankai26/School_District_Analysis/blob/main/Resources/math_THS_original.png)
    ![math_THS_challenge](https://github.com/hankai26/School_District_Analysis/blob/main/Resources/math_THS_challenge.png)

    ![reading_THS_ori](https://github.com/hankai26/School_District_Analysis/blob/main/Resources/reading_THS_original.png)
    ![reading_THS_challenge](https://github.com/hankai26/School_District_Analysis/blob/main/Resources/reading_THS_challenge.png)
    
    - Scores by school spending
    ![spend_sum_ori](https://github.com/hankai26/School_District_Analysis/blob/main/Resources/spending_sum_original.png)
    ![spend_sum_challenge](https://github.com/hankai26/School_District_Analysis/blob/main/Resources/spending_sum_challenge.png)

    - Scores by school size
    ![size_sum_ori](https://github.com/hankai26/School_District_Analysis/blob/main/Resources/size_sum_original.png)
    ![size_sum_challenge](https://github.com/hankai26/School_District_Analysis/blob/main/Resources/size_sum_challenge.png)
    
    - Scores by school type
    ![type_sum_ori](https://github.com/hankai26/School_District_Analysis/blob/main/Resources/type_sum_ori.png)
    ![type_sum_challenge](https://github.com/hankai26/School_District_Analysis/blob/main/Resources/type_sum_challenge.png)

*** There is a bulleted list that addresses how each of the seven school district metrics was affected by the changes in the data 


# Summary

The reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs. The subject revision lead to slight change to the 


Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
*** There is a statement summarizing four changes to the school district analysis after reading and math scores have been replaced 


A high-level snapshot of the district's key metrics, presented in a table format
An overview of the key metrics for each school, presented in a table format
Tables presenting each of the following metrics:
Top 5 and bottom 5 performing schools, based on the overall passing rate
The average math score received by students in each grade level at each school
The average reading score received by students in each grade level at each school
School performance based on the budget per student
School performance based on the school size 
School performance based on the type of school


b) Add a logical operator then another opening parenthesis, then use a comparison operator to retrieve all the rows with ninth grade from the "grade" column 