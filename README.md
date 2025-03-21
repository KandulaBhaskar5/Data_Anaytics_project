# Data_Anaytics_project
# Dataset: Class Marks

## Description
This dataset contains students' scores across multiple questions in an exam. Each column represents a different question, with some having sub-parts. The dataset includes missing values, which indicate that the student did not attempt or answer the respective question.

## File Information
- **Filename:** class_marks.csv
- **Total Rows:** 86
- **Total Columns:** 12

## Column Descriptions
1. **Total** - The total marks obtained by the student.
2. **Q1aM4** - Score for Question 1a (Maximum: 4)
3. **Q1bM6** - Score for Question 1b (Maximum: 6)
4. **Q2aM6** - Score for Question 2a (Maximum: 6)
5. **Q2bM4** - Score for Question 2b (Maximum: 4)
6. **Q3aM5** - Score for Question 3a (Maximum: 5)
7. **Q3bM5** - Score for Question 3b (Maximum: 5)
8. **Q4aM3** - Score for Question 4a (Maximum: 3)
9. **Q4bM7** - Score for Question 4b (Maximum: 7)
10. **Q5M10** - Score for Question 5 (Maximum: 10)
11. **Q6aM4** - Score for Question 6a (Maximum: 4)
12. **Q6bM6** - Score for Question 6b (Maximum: 6)

## Data Characteristics
- The dataset contains **numerical** values, with some missing values.
- The maximum possible marks for each question are indicated in the column name (e.g., Q1aM4 means max 4 marks for Question 1a).
- Missing values are represented as `NaN`.

## Usage
This dataset can be used for:
- Analyzing student performance.
- Identifying trends in question difficulty.
- Understanding scoring distribution.

## Notes
- Ensure to handle missing values appropriately when analyzing the dataset.
- The `Total` column represents the sum of all question scores per student.
- Some students may not have attempted certain questions, resulting in missing values.

