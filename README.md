# School_District_Analysis
Repository for school data analysis using python code
## Overview of school district Analysis
Maria, a chief data scientist has been given the task to analyze the multiple school's data to help the school board decide on the funding allocation. She is expected to accomplish the task by following steps below:
Calculate the required metrics using the school data given for reading and math tests of students. The metrics that will aid in decision making are as follows:
- Top 5 and bottom 5 performing schools, based on the overall passing rate
- The average math score received by students in each grade level at each school
- The average reading score received by students in each grade level at each school
- School performance based on the budget per student
- School performance based on the school size 
- School performance based on the type of school

## Resources
**Data Source:** schools_complete.csv , students_complete.csv
**Software:** Python 3.8, Visual Studio Code 1.59

## School District Data Analysis Results

**How is the district summary affected?**

The district summary of the original dataset is as follows:
![Original](/Images/DistrictSummary_Original.png)

The district summary of the dataset after replacement for Thomas School data by NaN is as follows:
![Modified](/Images/DistrictSummary_AfterReplacement.png)

Except for the % Passing Reading score all other scores reduced in the summary calculated after data replacement for Thomas School

**How is the school summary affected?**
The school summary of the original dataset is as follows:
![Original_School_Summary](/Images/SchoolSummary_Original.png)

The school summary of the modified dataset is as follows:
![Modified_School_Summary](/Images/SchoolSummary_AfterReplacement.png)

The Average Math score and Average Reading score came down marginally for Thomas school but the % Passing Score for Math, reading and Overall came down significantly

**How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?**

Refer to the images in the point above. The Average Math score and Average Reading score came down marginally for Thomas school but the % Passing Score for Math, reading and Overall came down significantly from ~90% to ~65%

****How does replacing the ninth-grade scores affect the following:**
**Math and reading scores by grade****
The math and reading scores for 9th graders for Thomas High school is NaN. Other data  remains the same. Refer to the screen shots below. The first one is the result with the replaced dataset and the second one is the result with the original dataset.

Reading scores based on the replaced dataset:

![Replaced_Reading](/Images/ReadingScore_Replaced.png)

Math scores based on the replaced dataset:

![Replaced_Math](/Images/MathScore_Replaced.png)

Reading scores based on the original dataset:

![Original_Reading](/Images/ReadingScore_Original.png)

Math scores based on the original dataset:

![Original_Math](/Images/MathScore_Original.png)

**Scores by school spending**
Refer to screen shots below:

The % Passing reading and % Overall Passing was lower in the replaced dataset for the spending range of 630 - 644 USD

Scores by School spending based on original dataset:

![Original_Scores](/Images/Score_BySchoolSpending_Original.png)

Scores by School spending based on replaced dataset:

![Replaced_Scores](/Images/Score_BySchoolSpending_Replaced.png)

**Scores by school size**

The % Passing reading and % Overall Passing was lower in the replaced dataset for the medium size school (1000 to 2000 students)

Scores by School size based on original dataset:

![Original_Scores](/Images/Score_BySize_Original.png)

Scores by School spending based on replaced dataset:

![Replaced_Scores](/Images/Score_BySize_Replaced.png)

**Scores by school type**

The % Passing reading and % Overall Passing was lower in the replaced dataset for the Charter schools and remained unchanged for district schools

Scores by School type based on original dataset:

![Original_Scores](/Images/Score_ByType_Original.png)

Scores by School type based on replaced dataset:

![Replaced_Scores](/Images/Score_ByType_Replaced.png)


## School Data Analysis Summary
The four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs are as follows:

1. The % Passing Score for reading and % Overall Passing score got reduced for the Charter schools
2. The % Passing Score for reading and % Overall Passing score got reduced for the medium sized schools (having 1000 to 2000 students)
3. % Passing Score for reading and % Overall Passing score got reduced for the schools having spending of 630 to 644 USD per student
4. The Math and Reading scores for Thomas High School got reduced


