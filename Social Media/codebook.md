# Codebook for "Students Social Media Addiction" Dataset

## Dataset Description

This dataset captures information about students' demographics, social media habits, and the effects of social media usage on their academic, mental, and social aspects. It includes 705 observations, each representing a unique student, and provides insights into the relationship between social media usage and various factors such as academic performance, sleep, mental health, and relationships.

------------------------------------------------------------------------

## Variable Description

| Variable Name                  | Data Type   | Description                                                                        | Example Values                       |
|--------------------------------|-------------|------------------------------------------------------------------------------------|--------------------------------------|
| `Student_ID`                   | Integer     | Unique identifier for each student.                                                | 1, 2, 3                              |
| `Age`                          | Integer     | Age of the student in years.                                                       | 18, 19, 20                           |
| `Gender`                       | Categorical | Gender of the student.                                                             | Female, Male                         |
| `Academic_Level`               | Categorical | Current academic level of the student.                                             | High School, Undergraduate, Graduate |
| `Country`                      | Categorical | Country of residence of the student.                                               | USA, India, UK                       |
| `Avg_Daily_Usage_Hours`        | Float       | Average number of hours spent on social media daily.                               | 4.5, 6.2, 7.0                        |
| `Most_Used_Platform`           | Categorical | The social media platform most frequently used by the student.                     | Instagram, TikTok, Facebook          |
| `Affects_Academic_Performance` | Categorical | Whether social media usage affects academic performance.                           | Yes, No                              |
| `Sleep_Hours_Per_Night`        | Float       | Average hours of sleep per night.                                                  | 5.8, 6.5, 7.2                        |
| `Mental_Health_Score`          | Integer     | A subjective mental health score ranging from 1 (poor) to 10 (excellent).          | 4, 7, 9                              |
| `Relationship_Status`          | Categorical | Current relationship status of the student.                                        | Single, In Relationship, Complicated |
| `Conflicts_Over_Social_Media`  | Integer     | Number of conflicts with others due to social media usage.                         | 0, 2, 4                              |
| `Social_Media_Addiction_Score` | Integer     | A score indicating the level of social media addiction (1 to 10, higher is worse). | 3, 6, 9                              |

------------------------------------------------------------------------

## Notes:

-   The dataset contains 705 rows, each representing a unique student.
-   The `Social_Media_Addiction_Score` is an aggregated measure indicating the severity of social media dependency.
-   `Affects_Academic_Performance` and `Conflicts_Over_Social_Media` are subjective and self-reported measures.
-   Data can be used to analyze patterns and correlations between social media usage and its impact on students' academic, social, and personal well-being.
