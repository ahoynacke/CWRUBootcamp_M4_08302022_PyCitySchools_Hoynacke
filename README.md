# CWRUBootcamp_M4_08302022_PyCitySchools_Hoynacke
Module 4: PyCitySchools with Pandas

## Overview of Project 
Below is a list of delieveables required for the project:
 - The district summary
 - The school summary
 - The top 5 and bottom 5 performing schools, based on the overall passing rate
 - The average math score for each grade level from each school
 - The average reading score for each grade level from each school
 - The scores by school spending per student, by school size, and by school type
 
## Resources
- Data Source: PyCitySchools_Challenge_testing.ipynb and PyCitySchools.ipynb
- Software: Python, Visual Studio Code, Anaconda, Jupyter, Pandas

## Project Background
The school board has notified Maria and her supervisor that the students_complete.csv file shows evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. Although the school board does not know the full extent of the academic dishonesty, they want to uphold state-testing standards and have turned to Maria for help. She has asked you to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact. Once you’ve replaced the math and reading scores, Maria would like you to repeat the school district analysis that you did in this module and write up a report to describe how these changes affected the overall analysis.

## Deliverable 1: Replace Ninth-Grade Reading and Math Scores Results 
<img width="1102" alt="Screen Shot 2022-09-08 at 6 22 35 PM" src="https://user-images.githubusercontent.com/111096384/189236388-89f7f6a5-284f-41e2-bdc8-8047ef333c6b.png">

## Deliverable 2: Repeat the School District Analysis Results 
1. The district summary DataFrame (3 pt)
<img width="919" alt="Screen Shot 2022-09-08 at 6 23 37 PM" src="https://user-images.githubusercontent.com/111096384/189236519-9be48fe6-17f9-4766-9e7d-fd1fb8a73d91.png">

2. The school summary DataFrame (3 pt)
<img width="1111" alt="Screen Shot 2022-09-08 at 6 24 29 PM" src="https://user-images.githubusercontent.com/111096384/189236629-fe652db1-e362-4f5e-a622-dd7318cbcf5e.png">

3. The top 5 performing schools, based on the overall passing rate (2 pt)
<img width="1075" alt="Screen Shot 2022-09-08 at 6 25 42 PM" src="https://user-images.githubusercontent.com/111096384/189236725-7139172c-d32a-49c9-af78-990326e80041.png">

4. The bottom 5 performing schools, based on the overall passing rate (2 pt)
<img width="1105" alt="Screen Shot 2022-09-08 at 6 26 36 PM" src="https://user-images.githubusercontent.com/111096384/189236839-517abfae-7b5e-4963-ab7b-7b1332521b89.png">

5. The average math score for each grade level from each school (3 pt)
<img width="628" alt="Screen Shot 2022-09-08 at 6 27 14 PM" src="https://user-images.githubusercontent.com/111096384/189237096-44e1a082-ec00-4ad1-b1bb-7c3c8fcfa86f.png">

6. The average reading score for each grade level from each school (3 pt)
<img width="658" alt="Screen Shot 2022-09-08 at 6 28 59 PM" src="https://user-images.githubusercontent.com/111096384/189237149-3332778c-8636-4584-a59d-331d7cb6af56.png">

7. The scores by school spending per student (3 pt)
<img width="1188" alt="Screen Shot 2022-09-08 at 6 36 57 PM" src="https://user-images.githubusercontent.com/111096384/189238169-1d8b821a-6f31-4058-9558-2bd44e7a77bb.png">

8. The scores by school size (3 pt)
<img width="947" alt="Screen Shot 2022-09-08 at 6 38 37 PM" src="https://user-images.githubusercontent.com/111096384/189238173-c080cafc-84cf-448a-a467-3a915566b3f7.png">

9. The scores by school type (3 pt)
<img width="766" alt="Screen Shot 2022-09-08 at 6 40 28 PM" src="https://user-images.githubusercontent.com/111096384/189238349-15e8f06d-e10b-4f01-82dc-d8eb789ae605.png">


## Deliverable 3 Requirements Analysis 

#### Overview of the school district analysis:
As shown above executing this analysis will give the user valuable information about the following 
 - The district summary & the school summary
 - The top 5 and bottom 5 performing schools, based on the overall passing rate
 - The average math score for each grade level from each school
 - The average reading score for each grade level from each school
 - The scores by school spending per student, by school size, and by school type

#### The purpose of this analysis is well defined (3 pt).
Results: The purpose of this analysis was to take our orginal data and clean it up. Verify that our data was concise and correct. Between the orginal file and the challenge file (final) there was a slight change in the average scores along with small adjustments to the percentage passing.

#### Bulleted list that addresses how each of the seven school district metrics was affected by the changes in the data (10 pt).
Summary:
Changes were made to each of the following after cleanup: 
 - overall passing rate
 - average math score for each grade level from each school
 - average reading score for each grade level from each school
 - spending budget per student, 
 - student count (school size) 
 - all NANS have been replaced and removed from the data 

#### Statement summarizing four changes to the school district analysis after reading and math scores have been replaced (5 pt).
After the reading and math scores were replaced it adjusted the funding per student along with the overall passing percentage and the average scores. 
