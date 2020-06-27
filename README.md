# School_District_Analysis

Here is the list of deliverables for the analysis of the school district: 
       
 -A high-level snapshot of the district's key metrics, presented in a table format
 
 -An overview of the key metrics for each school, presented in a table format
 
 
-Tables presenting each of the following metrics:
 
 
   *  Top 5 and bottom 5 performing schools, based on the overall passing rate
     
     
   * The average math score received by students in each grade level at each school
     
     
  * The average reading score received by students in each grade level at each school
     
  *  School performance based on the budget per student
     
     
   *  School performance based on the school size 
     
     
   *  School performance based on the type of school
   
  
# Resources:


   * Schools_complete.csv
   * Students_complete.csv
   * Jupyter notebook
   
   
# Summary:



 * District Summary:
                   
                   
      ![district summary](https://user-images.githubusercontent.com/65969608/85871825-91f4be00-b794-11ea-9300-d34682553fa3.png)



 
 
 * School Summary:
 
 
      ![school summary](https://user-images.githubusercontent.com/65969608/85873718-22340280-b797-11ea-96eb-27d3c7301d98.png)
 
 
 
 
 * Top 5 and bottom 5 performing schools, based on the overall passing rate:
 
 
      Top Schools:
      
      ![top school](https://user-images.githubusercontent.com/65969608/85873840-51e30a80-b797-11ea-9859-72c0519d23f7.png)
 
 
 
 
 
 
      Bottom Schools:
     ![bottom school](https://user-images.githubusercontent.com/65969608/85874030-9e2e4a80-b797-11ea-83ec-afe374ad3c76.png)

 
 
 
 
 * The average math score received by students in each grade level at each school:
 
 
      ![math score all std](https://user-images.githubusercontent.com/65969608/85874970-1a755d80-b799-11ea-8052-2bced0dba469.png)

 
 
 * The average reading score received by students in each grade level at each school:
 
 
      ![reading for all std](https://user-images.githubusercontent.com/65969608/85875103-54defa80-b799-11ea-924b-0d85989210be.png)

 
 * School performance based on the budget per student:
 
 
      ![budget for each student](https://user-images.githubusercontent.com/65969608/85875960-a50a8c80-b79a-11ea-9dba-66ba05fa76cf.png)


 * School performance based on the school size :
 
 
      ![school size](https://user-images.githubusercontent.com/65969608/85875742-4f35e480-b79a-11ea-8387-e2bea39c465d.png)
 
 
 * School performance based on the type of school:
 
 
      ![school type](https://user-images.githubusercontent.com/65969608/85875814-6d034980-b79a-11ea-99e0-8fe9f6e94012.png)
      
      
      
  
  
  
  # Challenge:
  
  
   
   The goals of this challenge:
   * Correct the students' names so there are no professional prefixes or suffixes.
   
   
   * Replace the reading and math scores for ninth graders at Thomas High School with NaN.
   
   * Recreate the district and school summary DataFrames.
   
        How is the district summary affected?
        
        
        
        How is the school summary affected?
        
        
   * Recalculate the high- and low-performing schools.
   
   
        How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance, relative to the other schools?
        
        
   * Recalculate the scores by grade, scores by school spending, scores by school size, and scores by school type.
   
   
        How does replacing the ninth-grade scores affect the following?
        
        
        Math and Reading Scores by Grade.
        
        
        Scores by School Spending.
        
        
        Scores by School Size.
        
        
        Scores by School Type



 
 # Summary For Challenge:
 
 
 
   * Correct the students' names so there are no professional prefixes or suffixes:
   
   
   ![remove pre](https://user-images.githubusercontent.com/65969608/85878805-ea30bd80-b79e-11ea-8127-cfd21c247f06.png)
   
   
   * Replace the reading and math scores for ninth graders at Thomas High School with NaN:
   
   ![9th Nan](https://user-images.githubusercontent.com/65969608/85878875-046a9b80-b79f-11ea-9f7b-786adee41c8a.png)
   
   
   * Recreate the district and school summary DataFrames:
   
       How is the district summary affected?
       
        After Recreate district Summary, We can see that a small difference in Average math,%passing math,% Passing reading and Overall passing.
       
        ![district summary](https://user-images.githubusercontent.com/65969608/85879042-485da080-b79f-11ea-8bd8-e6037ed2d893.png)
        
        
       
       
       
       
       How is the school summary affected?
       
        Recreate a School Summary Doesn't impact on school summary.
       
       
        ![school summary](https://user-images.githubusercontent.com/65969608/85879113-662b0580-b79f-11ea-867e-93e61df0fb12.png)
        
        
       
        
        
        
* Recalculate the high- and low-performing schools:
     
     
     High Performing Schools:  After Recreate High Performing Schools, Thomas high school removed from  high performing list. 
          
          
     ![top five school](https://user-images.githubusercontent.com/65969608/85879273-b1ddaf00-b79f-11ea-9062-ab525a96923a.png)
     
    
          
          
     Low Performing Schools:  After Recreate low performing School,it doesn't change in list.
          
          
     ![bottom five](https://user-images.githubusercontent.com/65969608/85879339-cde15080-b79f-11ea-951a-056f690679b9.png)
     
     
    
          
          
* Recalculate the scores by grade, scores by school spending, scores by school size, and scores by school type.
   
                   
                   
     Math Score for all Grade:Recalculate the  math scores by grade,Doesn't change for all std.
          
          
          
     ![math for all std](https://user-images.githubusercontent.com/65969608/85879562-38928c00-b7a0-11ea-8467-cf02d9c871cb.png)
     
     
     
          
          
     Reading Score for all Grade:Recalculate the reading scores by grade,Doesn't change for all std.
          
          
     ![math for all std](https://user-images.githubusercontent.com/65969608/85879562-38928c00-b7a0-11ea-8467-cf02d9c871cb.png)
     
     
     
          
          
     Scores by School Spending: After Recreate a School Spending,It was affcted only on Thomas High School.Everything chnaged in Thomas HighSchool.
          
          
     ![school per student](https://user-images.githubusercontent.com/65969608/85880185-341aa300-b7a1-11ea-94bf-fd6b558e3fe8.png)
     
     
     
          
          
     Scores by School Size:After Recreate a School size,It was affcted on Medium size(1000-2000) like in % Passing math,%Passing Reading and  % Overall passing.
          
     ![on school size](https://user-images.githubusercontent.com/65969608/85880297-64624180-b7a1-11ea-8d9d-75f4bf74d0af.png)
     
     
          
     Scores by School Type:After Recreate as School type, It was affcted on Charter type like in  % Passing math,%Passing Reading and  % Overall passing.
          
     ![school type](https://user-images.githubusercontent.com/65969608/85880388-8b207800-b7a1-11ea-9cc8-4b38dedf2a0a.png)
     
     

          
          
          
          
          


          
          
          
          
          




       
       
       

   
   
   
   
   
   
   
