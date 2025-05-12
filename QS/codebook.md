# Students Grading Dataset Codebook

## Dataset Description

The **Students Grading Dataset** is a comprehensive collection of academic performance and behavioral data for 5,000 students. The dataset includes variables capturing demographic details, academic scores, extracurricular activities, stress levels, and other related factors. This dataset is valuable for analysis related to student performance, behavioral patterns, and academic outcomes.

------------------------------------------------------------------------

## Variables Overview

| **Variable Name**            | **R Class**       | **Type of Data** | **Description**                                                                 | **Example Value(s)**                                                 |
|------------------------------|-------------------|------------------|---------------------------------------------------------------------------------|----------------------------------------------------------------------|
| `Student_ID`                 | character         | Categorical      | Unique identifier for each student.                                             | "S1000", "S1001"                                                     |
| `First_Name`                 | character         | Categorical      | First name of the student.                                                      | "Omar", "Maria"                                                      |
| `Last_Name`                  | character         | Categorical      | Last name of the student.                                                       | "Williams", "Brown"                                                  |
| `Email`                      | character         | Categorical      | Email address of the student.                                                   | "[student0\@university.com](mailto:student0@university.com){.email}" |
| `Gender`                     | factor            | Categorical      | Gender of the student ("Male" or "Female").                                     | "Male", "Female"                                                     |
| `Age`                        | numeric (integer) | Continuous       | Age of the student.                                                             | 18, 21, 24                                                           |
| `Department`                 | factor            | Categorical      | Academic department of the student.                                             | "Engineering", "Business", "CS"                                      |
| `Attendance (%)`             | numeric           | Continuous       | Attendance percentage of the student.                                           | 52.29, 75.72, 100                                                    |
| `Midterm_Score`              | numeric           | Continuous       | Score obtained in the midterm exam.                                             | 55.03, 70.51, 99.98                                                  |
| `Final_Score`                | numeric           | Continuous       | Score obtained in the final exam.                                               | 57.82, 69.73, 99.98                                                  |
| `Assignments_Avg`            | numeric           | Continuous       | Average score of assignments.                                                   | 62.09, 74.81, 99.98                                                  |
| `Quizzes_Avg`                | numeric           | Continuous       | Average score of quizzes.                                                       | 50.03, 74.69, 99.96                                                  |
| `Participation_Score`        | numeric           | Continuous       | Score for class participation.                                                  | 0.00, 4.96, 10.00                                                    |
| `Projects_Score`             | numeric           | Continuous       | Score obtained in projects.                                                     | 50.01, 74.98, 100                                                    |
| `Total_Score`                | numeric           | Continuous       | Final total score of the student.                                               | 50.02, 75.39, 99.99                                                  |
| `Grade`                      | ordered factor    | Ordinal          | Final grade of the student ("A" \> "B" \> "C" \> "D" \> "F").                   | "A", "B", "F"                                                        |
| `Study_Hours_per_Week`       | numeric           | Continuous       | Average number of study hours per week.                                         | 6.2, 17.5, 30                                                        |
| `Extracurricular_Activities` | factor            | Categorical      | Whether the student participates in extracurricular activities ("Yes" or "No"). | "Yes", "No"                                                          |
| `Internet_Access_at_Home`    | factor            | Categorical      | Whether the student has internet access at home ("Yes" or "No").                | "Yes", "No"                                                          |
| `Parent_Education_Level`     | ordered factor    | Ordinal          | Highest education level attained by the student's parents.                      | "None", "High School", "Master's"                                    |
| `Family_Income_Level`        | ordered factor    | Ordinal          | Family income level ("Low" \< "Medium" \< "High").                              | "Low", "Medium", "High"                                              |
| `Stress_Level (1-10)`        | numeric (integer) | Continuous       | Stress level of the student on a scale from 1 to 10.                            | 1, 5, 10                                                             |
| `Sleep_Hours_per_Night`      | numeric           | Continuous       | Average number of sleep hours per night.                                        | 4.0, 6.5, 9.0                                                        |

------------------------------------------------------------------------

### Notes:

1.  **Missing Values**: Some variables, like `Attendance (%)` and `Assignments_Avg`, contain missing values (516 and 517 NA values respectively). Appropriate handling is needed before analysis.
2.  **Ordinal Variables**: Variables like `Grade`, `Parent_Education_Level`, and `Family_Income_Level` have an inherent order and should be treated accordingly during analysis.
3.  **Distribution Insights**: Most continuous variables, e.g., `Age`, `Midterm_Score`, and `Stress_Level`, span a wide range, providing opportunities for detailed statistical analysis.

------------------------------------------------------------------------
