# MIST-4600-Project-2

## Team Name
15061 Group 4

## Team Members
1) Joey Lund [@jl4600](https://github.com/jl4600) 
2) Armon Parsa [@armon222](https://github.com/armon222)
3) Ronit Subramanian [@ronsub101](https://github.com/ronsub101)
4) Kyle Szabo [@kszabo2390](https://github.com/kszabo2390)

## Dataset description
Our dataset details the school attendance rate and student count by different student groups in different school districts in Connecticut for each school year from 2019-2022. We obtained the dataset from the website (https://catalog.data.gov/dataset). Our data set includes the district code and the district name for each school. The dataset then provides the information about the students, their category (ex. race/ethnicity, students with disabilities) and then the student group. Then the data set provides information about the attendance rate of each category from 2019-2022. 


## Question 1

### How does student attendance across Connecticut get affected by different factors that affect students? 

### Importance:
This question is interesting because it allows us to understand which factors have the biggest impact on student attendance in different districts across Connecticut. Influencing bodies such as the government will be able to use this data in order to better inform their decisions on what to focus on. For example, if you see the attendance for English learners is low, the schooling system should improve their existing programs to incentivise students to better participate in classroom activities that help them learn better. Furthermore, students facing homelessness having a low attendance rate could imply that they have extenuating circumstances that prevent them from coming to school. This information could be used for many reasons, such as offering courses at night to accommodate schedules and helping other government programs better assist these individuals. 


![Capture](https://github.com/armon222/MIST-4600-Project-2/assets/62662242/c3978fb8-356a-438d-ab29-025eda98ea01)

### Analysis
The graph illustrates the attendance rates of Students in Connecticut by different student groups. These groups include ethnic groups as well as circumstantial groups such as students with disabilities or students experiencing homelessness. In this visualization, we looked at the attendance rates for the 2021-2022 school year, and results for most of the groups are fairly similar. The median attendance rate for all students was 93%, however the main outlier to this fact is students experiencing homelessness. The median attendance rate for students with homelessness was 83%, 10 percentage points lower than the median for all students. This information is useful to know because it suggests the main problems that this student group may struggle with, such as working a job during school hours, not having transportation to arrive at school, or other factors out of school. Knowing this information can help the school board create new programs to help these students get to school, as well as share information with other government programs that can assist these students. Another thing to highlight, students with high needs have a 2.3% difference in attendance rate on average compared to students without high needs. This could be explained by various factors, such lack of school staffing, poor staff performance, etc. In the future, the schools should try and better prepare their teachers to better accommodate students with higher needs to improve their experience


### Manipulation
We did not have to calculate any new data for this. We put "Student Group" in our columns and "2021-2022 Attendance Rates" in the Rows. We included all of the districts in Connecticut, but we had to exclude the overall Connecticut data (listed under districts) to not affect the data's variance.

## Question 2

### How does Hispanic/Latino population correlate with the population of students who qualify for free/reduced meal prices?

### Importance:
This visualization is important because it shows that the population of Hispanic/Latino students is closely related to the number students that qualify for free or reduced meals in a district. While we cannot do anything about this, it can be useful for government officials to refer to when making policies. This is a systemic issue, and it is important to make this information known.

![Capture](https://github.com/armon222/MIST-4600-Project-2/assets/62662242/222f9a6d-ce5b-42f2-a70d-b79c016943d0)

### Analysis
The graph here illustrates randomly selected school districts in Connecticut and the Student count for the 2021-2022 school year. Each school shows the Hispanic/Latino population and the free/reduced price meal eligibility that each district has. This graph shows a strong correlation for these two student groups for each district. The fact that each district has such similar trends may point towards a systemic problem at the government level. It is very telling that in areas where there is a higher Hispanic population, there tends to be a higher number of students who need free/reduced meal eligibility. Whereas in areas with lower Hispanic populations, the free/reduced price meal eligibility  student group tends to be lower. This further demonstrates a systemic issue in Connecticut that needs immediate action. 

![Capture](https://github.com/armon222/MIST-4600-Project-2/assets/62662242/0a1cbd96-a5b7-40f9-94d0-68b3b8aa1554)

If we compare this with the count of white students (pictured below), we can see that that metric has no clear pattern of correlation with the free/reduced meal eligibility. This goes to show that the number of students who qualify for reduced or free meals is not as simple as a direct correlation with overall student count.



### Manipulation
For this graph we had District Name and Student group in columns and the student count for 2021-2022 in rows. We filtered the districts to 15 that we randomly selected from the full list to make the data more readable. We also filtered to only show the student groups "Hispanic/Latino" and "Free/Reduced Meal Price Eligibility".
