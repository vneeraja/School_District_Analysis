# School_District_Analysis

## Overview of the school district analysis

We will be helping maria, a chief Data Scientist for a city school district, to analyse data on student funding and students standardized test scores. We aggregate the data and showcase trends based on school performance.
Now, The school board has notified Maria and her supervisor that the students_complete.csv file shows evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. 
Maria has asked us to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact.
Once we have replaced the math and reading scores, Maria would like us to repeat the school district analysis and write up a report to describe how these changes affected the overall analysis.

## Results of the Analysis

We have been notified that the reading and math grades for Thomas High School ninth graders have been altered. So first we will replace all the reading and math scores 
of ninth graders with NaN's. Here is the updated students dataset.
![image](https://user-images.githubusercontent.com/111020934/188359243-ab1e4a7c-42e6-4344-aa7d-6424af407877.png)

We will perform our analysis with this updated students dataset.

### How is the district summary affected?

The below is the original school district summary for all students math and reading scores:
![image](https://user-images.githubusercontent.com/111020934/188299514-05bd94d8-008b-439f-9de1-903c752d861a.png)

The below is the school district summary without taking the average math and reading scores for ninth graders of Thomas High School:
![image](https://user-images.githubusercontent.com/111020934/188299525-668b2954-177b-4427-9b22-2fd53180cbcc.png)

While not taking the math and reading scores for ninth graders of Thomas High School, based on our analysis we can conclude the following:
  1. The average math score has dipped by 0.1.
  2. The number of students passing math has dipped by 0.2%.
  3. The number of students passing reading has dipped by 0.1%.
  4. The overall passing percentage of students has dipped by 0.3%.
  
### How is the school summary affected?

The below is the original school summary for all students math and reading scores:
![image](https://user-images.githubusercontent.com/111020934/188360087-4f39c7e7-57df-4432-aa08-d0dfe16b62e3.png)

The below is the school summary without taking the average math and reading scores for ninth graders of Thomas High School:
![image](https://user-images.githubusercontent.com/111020934/188360181-0707fc43-08b0-4027-8703-284121a3676c.png)

While not taking the math and reading scores for ninth graders of Thomas High School, based on our analysis we can conclude the following:
  1. The average math score has dipped by 0.1.
  2. The number of students passing math has dipped by 0.1%.
  3. The number of students passing reading has dipped by 0.3%.
  4. The overall passing percentage of students has dipped by 0.3%.

### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

With an overall passing of 90.6%, the Thomas High School still holds 2nd position in top five performing schools. Below is the screenshot:
![image](https://user-images.githubusercontent.com/111020934/188361137-173e2858-ae9c-48eb-941b-a3809e9347cf.png)

### How does replacing the ninth-grade scores affect the following:

1. Math and reading scores by grade

The average math and reading scores have been replaced with NaN for ninth graders of Thomas High School. All the other graders scores remain unaffected.
Below is the students math score datasets, with and without considering the grades of ninth graders:
![image](https://user-images.githubusercontent.com/111020934/188361941-d85a04b2-61f8-4635-abd8-c954dafb6526.png)
![image](https://user-images.githubusercontent.com/111020934/188362007-f084bd60-65b9-444b-b406-234d1e7e55fc.png)

2. Scores by school spending

There is no change in students scores based on school spending. Below is the dataset of scores by school spending.
![image](https://user-images.githubusercontent.com/111020934/188363159-67729976-4e87-4188-8007-6e42f08e5252.png)

3. Scores by school size

There is a very slight dip in the percentage of students passing reading after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
Below is the scores by school size before and after making changes in scores of ninth graders.
![image](https://user-images.githubusercontent.com/111020934/188363843-46c31263-8fed-4b5d-8551-bd7bcc460c18.png)
![image](https://user-images.githubusercontent.com/111020934/188363882-6471712a-0c5c-4bc7-9e5a-b3acfb1e99de.png)

4. Scores by school type

We do not see any changes in scores by school type before and after making changes in scores of ninth graders.
![image](https://user-images.githubusercontent.com/111020934/188364165-fff591e0-c9fd-4d2e-ac77-f197ea527b59.png)


## Summary: Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.

While performing our analysis, we observed that the average math and reading scores, the percentage of students passing math, reading and the overall passing percentage has dropped in the district and school summary. There is no change in scores when performing analysis for school spending, school size and the type of school.
