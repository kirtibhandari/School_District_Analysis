# **School District Analysis**
## **Project Overview**:
We need to provide insights about performance trends and patterns of schools in the district. This analysis is based upon standardized test scores of math and reading , of all the students in these schools, in grades 9th, 10th, 11th and 12th.

To be able to provide insights, we need to calculate values for requested metrics. The results of these metrics will be used by School Board and Supritendent to make informed and strategic decisions at the school and district level. These decision aim towards forming budget and funding priorities for these schools based upon the 

We need to keep in mind FERPA ( Family Educational Rights and Privacy Act), 1974, and ensure that we abide by this Act and treat given data of students with utmost confidentiality.
### **Purpose**:
School board notified about evident academic dishonesty in math and reading scores of grade 9th students from Thomas High School after the original datasets were analysed and desired metrics had been calculated. 

For this analysis, we need to keep the rest of data intact and re evaluate the desired metrics for school board to uphold the state testing results. After we have obtained these new metrics of Schools District Analysis, we need to submit a report about affect of these changes in data on requested metrics for the overall analysis.

We have been given 2 datasets:
1. schools_complete.csv
2. students_complete.csv

Also, we have the metrics for analysis, that have been obtained from original datasets.

We are required to replace the  math and reading scores of grade 9th for 'Thomas High School', in students_complete.csv dataset with 'NaNs', as requested by Chief Data Scientist Maria and then re-analyze the data for below metrics :

- The district summary
- The school summary
- The top 5 and bottom 5 performing schools, based on the overall passing rate
- The average math score for each grade level from each school
- The average reading score for each grade level from each school
- The scores by school spending per student, by school size, and by school type

After having obtained above, for the modified dataset of students, we need to compare the above metrics with the metric values we already have for the original students_complete.csv and present our insight on impact of modification of data on analysis results for the same, when compared with metric values obtained from analysis of original data.
## Results:

1. How is the district summary affected?
    
    **Original_District_Summary**
    ![Original_District_Summary](https://github.com/kirtibhandari/School_District_Analysis/blob/main/Resources/original_district_summary.png)
   
    **Modified_Data_District_Summary**
    ![Modified_Data_District_Summary](https://github.com/kirtibhandari/School_District_Analysis/blob/main/Resources/New_district_summary.png)

    - Average math score got reduced by 0.1 units in modified data's analysis compared to original data's analysis.
    - Percentage of students passed in Math reduced by 0.2% in modified data's district summary as compared to original data's analysis.
    - Percentage of students passed in Reading reduced by 0.3% in new data than that in original data.
    - Overall percentage of students who passed in the district, reduced by 0.1% for the new dataset than original.

2. How is the school summary affected?
    
    **Original_School_Summary**
    ![Original_School_Summary](https://github.com/kirtibhandari/School_District_Analysis/blob/main/Resources/original_per_school_summary_format.png)
    
    **Modified_School_District_Summary**
    ![Modified_School_District_Summary](https://github.com/kirtibhandari/School_District_Analysis/blob/main/Resources/new_school_summary_format.png)

- For Thomas High School, in the School Summary, as per the metrics obtained after dropping grade 9th's results, the metrics below got affected as described herewith:

    - Average Math scores for new School Summary got reduced by .067 units approximately than original metric values
    - Average Reading scores increased by .047 units approximately, in modified dataset than the one in original.
    - % Passing Math reduced by .086% , % Passing Reading reduced by 0.290%, % Overall passing reduced by 0.318 % approximately in modified dataset , when compared with original dataset metrics obtained upon analysis.
        
3. How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

    **Original_Top_5_Schools**
    ![Original_Top_5_Schools](https://github.com/kirtibhandari/School_District_Analysis/blob/main/Resources/original_top_5_schools.png)

    **Modified_top_five_schools**
    ![Modified_top_five_schools](https://github.com/kirtibhandari/School_District_Analysis/blob/main/Resources/new_top_5_schools.png)

    Relative to other schools, Thomas High School's still maintained second rank, from the top along with all other schools maintaining their same rank, as they had during the analysis from original data.

    **Original_Bottom_5_Schools**
    ![Original_Bottom_5_Schools](https://github.com/kirtibhandari/School_District_Analysis/blob/main/Resources/original_bottom_5_schools.png)

    **Modified_Bottom_five_schools**
    ![Modified_Bottom_five_schools](https://github.com/kirtibhandari/School_District_Analysis/blob/main/Resources/new_bottom_5_schools.png)

    Same schools were at top and bottom 5 as per modified dataset, as they had in original dataset analysis. Hence, performance or ranking of Thomas High School and others, remained same in original and new analysis.

4. How does replacing the ninth-grade scores affect the following:
    
    - Math and reading scores by grade

        **Original_Math_Scores_by_grade**

        ![Original_Math_Scores_by_grade](https://github.com/kirtibhandari/School_District_Analysis/blob/main/Resources/original_ninth_grade_math_scores_df_formatted.png)

         **Modified_Math_Scores_by_grade**

        ![Modified_Math_Scores_by_grade](https://github.com/kirtibhandari/School_District_Analysis/blob/main/Resources/new_ninth_grade_math_scores_df_formatted.png)

        **Original_Reading_Scores_by_grade**

        ![Original_Reading_Scores_by_grade](https://github.com/kirtibhandari/School_District_Analysis/blob/main/Resources/original_ninth_grade_reading_scores_df_formatted.png)

        **Modified_Reading_Scores_by_grade**

        ![Modified_Reading_Scores_by_grade](https://github.com/kirtibhandari/School_District_Analysis/blob/main/Resources/new_ninth_grade_reading_scores_df_formatted.png)

        By grade, analysis for all grades, for each of the school , remained unaltered. Only the new analysis shows 'NaNs' for grade 9th Math and Reading Scores and no other scores for Thomas High School or any other school got changed.

    - Scores by school spending 
        
    **Original_Scores_by_Spending**

    ![Original_Scores_by_Spending](https://github.com/kirtibhandari/School_District_Analysis/blob/main/Resources/original_spending-formatted.png)

    **Modified_Scores_by_Spending**

    ![Modified_Scores_by_Spending](https://github.com/kirtibhandari/School_District_Analysis/blob/main/Resources/new_spending-formatted.png)

    Values for Scores, by spending, for the specified bins, remain unaltered in analysis for modified dataset as compared to original dataset.

    - Scores by school size

    **Original_Scores_by_Size**

    ![Original_Scores_by_Size](https://github.com/kirtibhandari/School_District_Analysis/blob/main/Resources/original_size_summary_formatted.png)

    **Modified_Scores_by_Size**

    ![Modified_Scores_by_Size](https://github.com/kirtibhandari/School_District_Analysis/blob/main/Resources/new_size_summary_formatted.png)

    Values for Scores, by size, for the specified categories of Small, Medium and Large; remain unaltered in analysis for modified dataset as compared to original dataset.

    - Scores by school type

    **Original_Scores_by_Type**

    ![Original_Scores_by_Type](https://github.com/kirtibhandari/School_District_Analysis/blob/main/Resources/original_school_type_df.png)

    **Modified_Scores_by_Type**

    ![Modified_Scores_by_Type](https://github.com/kirtibhandari/School_District_Analysis/blob/main/Resources/new_school_type_df.png)

    Values for Scores, by school type; remain unaltered in analysis for modified dataset as compared to original dataset.

## Summary: 

This analysis is aimed at deciding the amount of allocation of funds, from the budget, depending upon the performance trend of schools in the district. Since we have been informed that scores for grade 9, of Thomas High School have been dropped due to evidence found , of academic dishonesty. We re evaluated the performance metrics under the desired categories.

These metrics were District Summary, School Summary, Scores of Schools by Grade, By Spending, By Size and by Type.

After having obtained metric values for the above, four major changes in comparison to other minor changes in metric values, in terms of mathematical values of metrics are as follows:

In District Summary,overall Percentage of students passed in Math reduced by 0.2% in modified data's district summary as compared to original data's analysis.

Also, in district summary,overall Percentage of students passed in Reading reduced by 0.3% in new data than that in original data. 

In School Summary, % Passing Reading reduced by 0.290% in the modified dataset compared to original dataset, for Thomas High School. 

Also, in school summary, % Overall passing reduced by 0.318 % approximately in modified dataset , when compared with original dataset metrics obtained upon analysis, for Thomas High School.

Thus, definitely, there was a drop in overall students who passed in math, in reading and overall performance of the district too, reduced by 0.1%. 

Also,  reading passing percentage and Overall passing percentage of school by itself, has dropped.

This might lead to apprehension that if Thomas High School have previously too been involved in academic dishonesty. This might lead to school audit and if it is tracked back, and a pattern is found, it might lead to significant drop when matched starting with last correct/honest scores.



