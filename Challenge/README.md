## School District Analysis
### Project Overview
After generating the district's schools' reading and math scores statistics and grouping them based on type, size, and budget categories, one of the school's data was flagged.  Thomas High School's (THS) ninth grade data was flagged for academic dishonesty and therefore the analysis had to be redone.  This involved removing THS's ninth grade data and replacing with 'nan'.  After this was complete, THS's reading and math score statistics were recalculated and the district's schools were re-grouped based on type, size, and budget. 

### Results Analysis
- Based on the updated analysis, the school district summary now shows lower average passing math and reading scores and percentages as seen in the images below.

Original District Summary
<img width="1025" alt="District_Sum_Original" src="https://user-images.githubusercontent.com/85457256/123851175-e4f1db80-d8e8-11eb-9316-338c088f80b4.png">


Updated District Summary
<img width="1011" alt="District_Sum_Updated" src="https://user-images.githubusercontent.com/85457256/123850378-f686b380-d8e7-11eb-9980-116d475b1c9c.png">


- The school summary is mostly the same except that THS has different data reported in the summary after removing the ninth grader's data. For example, THS's original % Passing Math and % Passing Reading were 93.3% and 97.3% respectively.  They now are 93.2% and 97.0% respectively. The % Passing Overall was 90.9% and is now 90.6% without including ninth graders' data.
- Replacing THS's ninth grade reading and math scores does not affect THS relative position in the district. In both analyses THS is the second to the top school based on % Overall Passing data. 
- Replacing THS's ninth grade reading and math scores...
  - Did not affect the math and reading scores for the 10th, 11th, and 12th grades across the schools (as seen in the images below for this section).  The only difference is that THS no longer has data displayed for its ninth graders.

    Original Scores by Grades
    
    <img width="545" alt="Math_Scores_by_Grade_Original" src="https://user-images.githubusercontent.com/85457256/123856577-45841700-d8ef-11eb-9369-e3af9d713a7e.png">
  <img width="447" alt="Reading_Scores_by_grade_Original" src="https://user-images.githubusercontent.com/85457256/123857910-e7583380-d8f0-11eb-863b-8f5596f85b6f.png">

    Updated Scores by Grades
    
    <img width="510" alt="Math_Scores_by_Grade_Updated" src="https://user-images.githubusercontent.com/85457256/123857350-2934aa00-d8f0-11eb-9543-39a61735daa6.png">
    <img width="453" alt="Reading_Scores_by_Grade_Updated" src="https://user-images.githubusercontent.com/85457256/123857367-2d60c780-d8f0-11eb-83a8-04319642236a.png">
    
  - Only affected the $630-644 spending range per student as seen in the tables below.  The majority of the reading and math statistics and passing percentages for this spending category dropped once THS's 9th grade data was not included which shows that the amount spent does not have the slightly higher averages and passing percentages like the original analysis suggested. However, the average reading score rose with the updated data. 
  
    Original Score by School Spending
    <img width="940" alt="Spending_Sum_Original" src="https://user-images.githubusercontent.com/85457256/123859480-b24ce080-d8f2-11eb-9907-018c14144689.png">
    
    Updated Score by School Spending
    <img width="926" alt="Spending_Sum_Updated" src="https://user-images.githubusercontent.com/85457256/123859466-af51f000-d8f2-11eb-8ed5-09c9a147c4fd.png">

  - Only affected the medium size category.  Specifically, within this category, the average reading score rose in the updated analysis while all other categories dropped.  

    Original Score by School Size
    <img width="863" alt="Size_Sum_Original" src="https://user-images.githubusercontent.com/85457256/123860105-7c5c2c00-d8f3-11eb-8735-51227ede25d6.png">
    
    Updated Score by School Size
    <img width="859" alt="Size_Sum_Updated" src="https://user-images.githubusercontent.com/85457256/123860050-69495c00-d8f3-11eb-89b6-758415bb60ab.png">
 
  - Affected charter schools data but not district schools.  Similarily to the other groupings, the average reading score increased after the updated data was used while all other categories dropped. 

    Original Score by School Type
    <img width="818" alt="Type_Sum_Original" src="https://user-images.githubusercontent.com/85457256/123861408-2092a280-d8f5-11eb-9121-e3435bad818e.png">
    
    Updated Score by School Type
    <img width="823" alt="Type_Sum_Updated" src="https://user-images.githubusercontent.com/85457256/123861420-24262980-d8f5-11eb-8298-fef57993d308.png">
    
### Summary
1. Overall,THS's average passing math and reading scores decreased once the ninth grade data was removed.
2. The district's average math and reading score as well as the passing percentages decreased once THS's ninth grade data was removed.
3. The average reading score rose in the $630-644 school spending and the medium school size categories and for charter schools. 
4. The average math score decreased in the $630-644 school spending and the medium school size categories and for charter schools. 
