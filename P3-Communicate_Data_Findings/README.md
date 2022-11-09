# **Students Performance**: Data Exploration

## Dataset

The data consists of information regarding 1000 students, including gender, race/ethnicity, parental level of education, lunch, test preparation, and other information about students' scores in three different types of subjects.
The dataset can be found [here](https://www.kaggle.com/datasets/whenamancodes/students-performance-in-exams).


## Summary of Findings

During the exploration phase, I discovered the following relationships:

* The 3 score variables have a slightly left-skewed distribution with some low scores and a peak between 60 and 80.  
* A strong linear relationship between the student's scores, which meant that having information about a student's performance in one subject can be really helpful in predicting its results in the other subjects.
* A correlation between the parental level of education and the student's performance in the three subjects, which indicates that the more educated the student's parents are, the better their children's outcomes will be.
* Students who completed the preparation course outperformed those who didn't.
* Students with standard lunch performed better than those with free or reduced lunch.
* Females performed better than males in reading and writing, whereas males performed better in mathematics.
* Group D and  E have the highest mean scores.
* A negative correlation between race/ethnic group size and the percentage of completed preparation courses.
* The correlation between the parental level of education and each subject score seemed to be slightly stronger for students who completed the preparation course.
* For the same gender and across all subjects, the trend between student performance and parental level of education remains very similar.
* For the same lunch option and across all subjects, the trend between student performance and parental level of education remains very similar.



## Key Insights for Presentation

In the presentation I started with introducing the pairwise relationship between the score variables and their distributions using a pairplot and a heatmap, afterwards, I introduced each of the categorical variables that showed a direct strong effect on the students' performance along with the appropriate plot that best captured the nature of the relationship. 
