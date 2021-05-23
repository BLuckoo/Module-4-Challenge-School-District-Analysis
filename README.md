# Module-4-Challenge-School-District-Analysis
#
### **Overview of the Analysis**

This analysis is to compile the data from the PyCity School District Board to determine whether spending per student has an impact on their grades.

The analysis will be based on a dataset provided by the School District Board.

An original analysis was completed but the Board found out that there were some academic dishonesty and hence, a new analysis will be done by isolating those cases.

The analysis will be comprised of the following components:
1. Cleaning the provided dataset by removing professional and gender related prefixes and suffixes 
2. Removing the reading and math scores of the grade 9 students from Thomas High School, where the academic dishonesty was discovered
3. Calculating the average scores and passing rates of all the schools in the district
4. Identifying the top five and the bottom five schools based on the overall passing percentages of the students
5. Calculating the Math and the Reading scores averages of each grade at each school
6. Calculating the average scores based on spending ranges by students
7. Calculating the average scores based on school size
8. Calculating the average scores based on school type
9. Commenting on how the results of the analysis were affected by the academic dishonesty
##
##
### **School District Analysis Findings**

- Using the dataset provided by the Board, there were a total of 39,170 students in all the 15 schools.

- A total of 461 students from the Thomas High School were in the group whereby academic dishonesty were discovered and their Math and Reading scores were removed from the data.

- The 15 schools in the district use a total budget of $24,649,428 to serve the student population and the average passing rate is 64.9%.

  ![image](https://user-images.githubusercontent.com/82583576/119277455-d29bc800-bbed-11eb-8e31-8a17819f32ae.png)
  
##  
- Using sorting functions within Python, a list of the top five schools based on overall passing percentages is as follows:

  ![image](https://user-images.githubusercontent.com/82583576/119277711-2f4bb280-bbef-11eb-8640-7ed43c70facd.png)
  
##  
- Using the same sorting principle as above with a change in the sorting order, a list of the bottom five schools based on overall passing percentages is as follows:
 
  ![image](https://user-images.githubusercontent.com/82583576/119277772-82be0080-bbef-11eb-97f1-ad27d557e88f.png)

##
- The average scores for each grade in each school for Math and Reading were compiled from the dataset using conditional and formatting concepts. The results are as follows:

    - Average Math Scores by School
      
       ![image](https://user-images.githubusercontent.com/82583576/119277946-6a021a80-bbf0-11eb-8977-bda0c877ef97.png)
  ##   
    - Average Reading Scores by School

      ![image](https://user-images.githubusercontent.com/82583576/119277993-a897d500-bbf0-11eb-8084-40ca41eeacc6.png)
##   
   
- By setting up spending ranges based on an analysis of the budget per student amounts, each school was categorized in one spending range. 
  The following table shows the details for each school and which spending range they fall within:
  
##  
  ![image](https://user-images.githubusercontent.com/82583576/119278166-90748580-bbf1-11eb-901c-4076c4c32704.png)
##  
  The above data has been further summarized by grouping the schools based on the spending range they fall within. The table below shows the results of the grouping:
  
##  
  ![image](https://user-images.githubusercontent.com/82583576/119278236-f3feb300-bbf1-11eb-823c-024810c63487.png)
##
- The effect of student population size on the grades was also analyzed. The table below illustrates the result:

##
  ![image](https://user-images.githubusercontent.com/82583576/119278389-f7466e80-bbf2-11eb-9d7c-5caf53712dde.png)
  
##  
  The above data has been summarized by grouping the schools based on their student population size, as follows:
##

  ![image](https://user-images.githubusercontent.com/82583576/119278450-5c01c900-bbf3-11eb-8341-9133fdd09144.png)
  
##

- A compilation and grouping of average scores by school type was also completed. 
  The chart below shows the results:
  
##

  ![image](https://user-images.githubusercontent.com/82583576/119278612-53f65900-bbf4-11eb-9ef6-24549ebfffef.png)

##
### **Summary of the Analysis**

Based on the dataset provided by the School District Board, we can infer the following based on the above analysis:

1. The academic dishonesty that occurred at Thomas High School 9th grade, did not have a significant effect on the overall passing % of the school district as the number of students involved is minimal compared to the whole student population attending all 15 schools. There were only 461 students involved on a total of 39,170 (i.e. 1.1%).

2. The top 5 schools all have an average overall passing grade over 90%.

3. The bottom 5 schools all have an average overall passing grade of over 50%.

4. The overall passing grade percentage is inversely related to the spending budget per student. There may be a need to find out where the spending is being directed.

5. The medium-sized schools, with a student population between 1,000 to 2,000 has the highest overall passing percentage.

6. The charter schools have a much higher overall passing percentage than the district schools, 90% versus 54%.



  


 
      
    

  



