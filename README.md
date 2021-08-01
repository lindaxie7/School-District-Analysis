# School-District-Analysis

## Overview of Project:
The purpose of this project is to analyze the data of an entire School District, such as funding and student grades, to learn new insights and visually provide clear results on each school's performance.

## Results:
The first trial of this analysis included the full set of student data. In the second trial of this analysis, the ninth grade students of Thomas High School had their scores omitted from the calculations. The entire ninth grade class of Thomas High School have had their scores replaced with NaN. 
### How is the district summary affected?
The DataFrame below is a summary representing the District after replacing the ninth graders' scores with NaN.
![Untitled](https://user-images.githubusercontent.com/38533045/127780851-c8b657aa-f74b-4fa8-86e4-59cc5028a936.png)

### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
When the ninth graders' of Thomas High School had their scores omitted from the calculations, the following changes occured:
The overall passing percentages of Thomas High School decreased by 0.11%
The average scores of Thomas High School for math and reading increased by 0.06
For the spending range of $630-644 per student, the overall passing percentage decreased by 0.1%
School rankings are unchanged. Thomas High School is still the second best performing school in the district with an overall passing rate of 90.63% among their tenth through twelfth graders.

### How does replacing the ninth-grade scores affect the following:
#### Math and reading scores by grade
It is found that a students grade level does not affect their scores as much as the school that they attend. The average scores within each school only varries by 1-2% depending on grade level. However, the difference in scores is more apparent when comparing different schools.
![Untitled](https://user-images.githubusercontent.com/38533045/127781393-05788b17-cb2a-4482-b25d-4c35dfc67b23.png)

#### Scores by school spending
It is found that the top performing school in the entire school district (Cabera High School) received $68 less per student than the lowest performing school (Johnson High School). This implies that there are more relevant factors than funding that decide average student scores.
![Untitled](https://user-images.githubusercontent.com/38533045/127781531-ec4e003d-40e4-41b9-b0be-e02cbf3e4d94.png)


#### Scores by school size
When considering School Sizes, "Large" Schools (Over 2,000 Students) have the lowest average scores and passing percentages. The difference in performance between "Small" and "Medium" Size Schools is negligible (approximately 1%). Interestingly, all District schools in this dataset are characterized as "Large" schools. This may be an indication that students in this district learn and perform better in smaller, more intimate settings.
![Untitled](https://user-images.githubusercontent.com/38533045/127781564-0ce0b874-ba6e-47e9-8b3e-c542d05c97ab.png)

#### Scores by school type
The top five schools with the highest overall passing percentages are all Charter schools, whereas the bottom five are all District Schools. Charter schools in this dataset were typically characterized as "Small" and "Medium" size schools. As seen in the DataFrame below, Charter schools have a 36% higher overall passing percentage than District schools.
![Untitled](https://user-images.githubusercontent.com/38533045/127781618-cb533ca8-5516-4de3-b2d4-30095f20c0e5.png)


## Summary:
Relacing the ninth graders' scores with NaN caused Thomas High School's overall passing percentages and average scores to plummet. The district as a whole has also had its average math and reading scores decrease, as well as the overall passing percentage for students. Furthermore, Thomas High School lost its placement as a top five school within this District. However, after updating the total student counts to exclude the Thomas High School ninth graders and omitting their scores from the dataset, Thomas High School regained its high average scores and retained its position as the number two school in the District. 
