# Pandas-Challenge
## [/PyCitySchools](PyCitySchools)
Provides code that runs through a school district's testing data and returns a summary.
Summary includes overview of district data, school specific data, and an overview of the 
specific testing data by school.
Also a quick view of top and bottom schools is given.

### District Summary
Provides a summary overview of the school district's information.
Information includes the total number of schools and students within the district,
the total budget for the district, the average scores for the math and reading test,
and their corresponding pass rates, as well as the overall passing rate for the district.
Numbers are formated using standard American convention for comma placement and currency.

### School Summary
Provides a summary of each individual school's data.
This includes each school's student count, budget, budget per student, and test scoring information.
Allows for quick analysis of school success compared to these metrics.

### Top Performing Schools
Returns the top 5 schools based on their overall passing rate.
Overall Passing rate is the average of both Math and Reading passing rate.

### Bottom Performing Schools
Returns the bottom 5 schools based on the same criteria as the top 5

### Math Scores by Grade
Provides a summary of the average math test scores based on each school and split further into each
grade (i.e. 9th-12th).

### Reading Scores by Grade
Provides a summary of the average reading test scores based on each school and split further into each
grade (i.e. 9th-12th).

### Summary of School Success by Per Student Budget
Provides a summary of testing scores comparing the "Per Student", or average, budget of each school to
their relative testing scores.
Summary looks at groups of schools by intervals of $700 per student and provides the average Math & Reading
score for each group as well as the passing rate for each subject and the overall passing rate (i.e. the 
average of the two).

### Summary of School Success by School Size
Provides a summary of testing scores comparing the school size of each school to their relative testing scores.
Summary looks at groups of schools, 0-1,000 students being classified as small, 1,000-3,000 being classified 
as medium, 3,000-4,000 being classified as large, and provides the average Math & Reading score for each group 
as well as the passing rate for each subject and the overall passing rate (i.e. the average of the two).

## Built-With
* Pandas
* Python
* Jupyter Notebook

## Authors
* Ryan Klueg
