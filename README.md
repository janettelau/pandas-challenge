# pandas-challenge
**Objective**: To create and manipulate Pandas DataFrames to analyze school and district-wide standardized test results. 
The datasets in the "Resources" folder includes:
- `students_complete.csv`: Each student's gender, grade, school, reading scores, and math scores.
- `schools_complete.csv`: School name, type, size, and budget.
These data are then aggregated to identify trends in school performance.

## Prerequisites
- Visual Studio Code
- Python
- Pandas

## Setup and Usage
1. Clone the `pandas-challenge` repository to your local computer.
2. Navigate to the cloned directory in Visual Studio Code
3. Open the Jupyter Notebook `PyCitySchools.ipynb` in the `PyCitySchools` folder to run and view the analysis.

## Output
The Python script analyzes the data and generates the following DataFrames:
- **District Summary** `district_summary`: A high-level overview of the district's key metrics, including total number of unique schools, total students, total budget, average math and reading scores, and passing rates.
- **School Summary** `per_school_summary`: Summary metrics for each individual school, detailing performance and characteristics, including school name, school type, total students, total school budget, per student budget, average math and reading scores, and passing rates.
- **Highest-Performing Schools by % Overall Passing** `top_schools`: Identifies the top 5 schools with the highest overall passing rates.
- **Lowest-Performing Schools by % Overall Passing** `bottom_schools`: Lists the schools with the lowest overall passing rates.
- **Math Scores by Grade** `math_scores_by_grade`: Average math score for students of each grade level (9th, 10th, 11th, 12th) at each school.
- **Reading Scores by Grade** `reading_scores_by_grade`: Average reading score for students of each grade level (9th, 10th, 11th, 12th) at each school.
- **Scores by School Spending** `spending_summary`: Performance metrics categorized by average spending ranges per student, including average math and reading scores, and passing rates.
- **Scores by School Size** `size_summary`: Performance metrics categorized by school size (small, medium, large), including average math and reading scores, and passing rates.
- **Scores by School Type** `type_summary`: Performance metrics categorized by school type (e.g., charter, district), including average math and reading scores, and passing rates.
