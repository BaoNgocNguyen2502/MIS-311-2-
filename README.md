# Part 1: Data Overview
## Context and Objective
The dataset “Most Visited Countries” contains information about international tourist arrivals across 206 countries. It includes both actual data (2022–2023) and predicted arrivals for 2024, measured in millions of visitors.
The dataset also includes references from the World Bank, providing context for global tourism performance.
This data helps identify recovery trends after COVID-19 and compare top tourism destinations worldwide.
- Rows: 206
- Columns: 6
- Data Source: Provided for MIS 311 course (simulated dataset based on World Bank data)
# Part 2: Data Cleaning
The dataset initially contained several missing values, especially in the 2022–2024 tourist arrival columns and two World Bank reference columns. These missing values were handled using a forward-fill and backward-fill method to maintain data continuity.
Additionally, three duplicate records were detected and removed to ensure data integrity.
After cleaning, the dataset consists of 203 unique rows with no missing or duplicate values, making it ready for statistical analysis.
# Part 3:  Descriptive Statistics và Insights
<img width="790" height="490" alt="image" src="https://github.com/user-attachments/assets/68c5f7ed-0474-4378-8fbd-f68d5df0c980" />
The chart shows that the average number of international tourist arrivals decreased from 22.8 million in 2022 to 15.3 million in 2023, followed by a slight recovery to 16.5 million (predicted) in 2024. This trend indicates that global tourism has not yet fully recovered to pre-2022 levels, possibly due to lingering travel restrictions, economic slowdown, or shifts in traveler behavior after the COVID-19 pandemic. However, the predicted increase in 2024 suggests a gradual rebound and renewed global travel confidence.





  
<img width="989" height="590" alt="image" src="https://github.com/user-attachments/assets/748b8739-add6-48c4-b650-2a5397e80ef1" />
https://colab.research.google.com/drive/1VE8C-oiaUbFlWunNi57xuBWQnnbngWTA
