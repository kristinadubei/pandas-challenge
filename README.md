# pandas-challenge

# Background
The scope of this assignment was to analyze the district-wide standardized test results. I was given access to every student's math and reading scores, as well as various information on the schools they attend. The task was to aggregate the data to showcase obvious trends in school performance.

# Process
Using Pandas and Jupyter Notebook, I created a report that includes the following data. The report includes a written description of observable trends based on the data.

### District Summary
Performed the necessary calculations and then created a high-level snapshot of the district's key metrics in a DataFrame.

Included the following:
- Total number of unique schools
- Total students
- Total budget
- Average math score
- Average reading score
- % passing math (the percentage of students who passed math)
- % passing reading (the percentage of students who passed reading)
- % overall passing (the percentage of students who passed math AND reading)

### School Summary
Performed the necessary calculations and then created a DataFrame that summarizes key metrics about each school.

Included the following:
- School name
- School type
- Total students
- Total school budget
- Per student budget
- Average math score
- Average reading score
- % passing math (the percentage of students who passed math)
- % passing reading (the percentage of students who passed reading)
- % overall passing (the percentage of students who passed math AND reading)

### Highest-Performing Schools (by % Overall Passing)
Sorted the schools by % Overall Passing in descending order and displayed the top 5 rows. Saved the results in the DataFrame called "top_schools".

### Lowest-Performing Schools (by % Overall Passing)
Sorted the schools by % Overall Passing in ascending order and displayed the top 5 rows. Saved the results in the DataFrame called "bottom_schools".

### Math Scores by Grade
Performed the necessary calculations and created the DataFrame that lists the average math score for students of each grade level (9th, 10th, 11th, 12th) at each school.

### Reading Scores by Grade
Created the DataFrame that lists the average reading score for students of each grade level (9th, 10th, 11th, 12th) at each school.

### Scores by School Spending
Createed a table that breaks down school performance based on average spending ranges (per student).

Included the following metrics in the table:
- Average math score
- Average reading score
- % passing math (the percentage of students who passed math)
- % passing reading (the percentage of students who passed reading)
- % overall passing (the percentage of students who passed math AND reading)

### Scores by School Size
Created a DataFrame called size_summary that breaks down school performance based on school size (small, medium, or large).

### Scores by School Type
Used the per_school_summary DataFrame from the previous step to create a new DataFrame called type_summary.

# References

The code for this project consists of initial instructions/starter_code provided by the Bootcamp and my solutions, this code does not contain parts of borrowed code, only outside concepts, see links below:

REFERENCE 1:
- nunique(): To count unique occurrences in school names:
  https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.nunique.html

REFERENCE 2:
- drop_duplicates(): Remove duplicates:
  https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.drop_duplicates.html
    
REFERENCE 3:
- squeeze(): To convert DataFrame into Series
  https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.squeeze.html

REFERENCE 4:
- .T (transpose): To flip rows and columns around:
  https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.transpose.html
