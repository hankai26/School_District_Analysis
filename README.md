# School_District_Analysis.
Analysis using Pandas

# Overview of the school district analysis: 
This project is to use Jypyter Notebook as well as the Pandas library combining Python coding to perform the analysis of school and student data in csv files. This analysis prepares the district summary, the school summary, and the school performance evaluation in average scores and passing rates. Multiple programming tools including methods from Panda and NumPy module were applied to retrieve information, change the data and conduct arithmatic calculations. Further, for special needs this analysis selected the exact information, revised specific numbers in the dataset and recalculated the student scores. The analysis allows to show how these specific changes affected the overall analysis.

# Results: Using bulleted lists and images of DataFrames as support, address the following questions.
Based on the requirements of the school board, the district's key metrics and each school metrics were prepared to evaluate how factors affect the school performance, like budget per student, school size and school type. More important, to make necessary revision to the 9th grade scores in Thomas High School, it's possible to figure out how the critical change affect those analysis results. Logical and comparison operators were applied offen in the analyzing process to select and revise data. This project addresses some findings as below.

- How is the district summary affected?

![district_ori](https://github.com/hankai26/School_District_Analysis/blob/main/Resources/district_original.png)
![district_challenge](https://github.com/hankai26/School_District_Analysis/blob/main/Resources/district_challenge.png)

- How is the school summary affected?

![school_sum_THS_ori](https://github.com/hankai26/School_District_Analysis/blob/main/Resources/school_sum_THS_original.png)
![school_sum_THS_challenge](https://github.com/hankai26/School_District_Analysis/blob/main/Resources/school_sum_THS_challenge.png)

![school_sum_first5_ori](https://github.com/hankai26/School_District_Analysis/blob/main/Resources/school_sum_first5_original.png)
![school_sum_first5_challenge](https://github.com/hankai26/School_District_Analysis/blob/main/Resources/school_sum_first5_challenge.png)

- How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

![Top_ori](https://github.com/hankai26/School_District_Analysis/blob/main/Resources/TopSchools_original.png)
![Top_challenge](https://github.com/hankai26/School_District_Analysis/blob/main/Resources/TopSchools_challenge.png)

![BottomSchools_ori](https://github.com/hankai26/School_District_Analysis/blob/main/Resources/BottomSchools_original.png)
![BottomSchools_challenge](https://github.com/hankai26/School_District_Analysis/blob/main/Resources/BottomSchools_challenge.png)


- How does replacing the ninth-grade scores affect the following:
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