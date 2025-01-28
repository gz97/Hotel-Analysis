## Overview
-	Deadline is **Thursday, 30th January 2025, 12:00pm**
-	Your report should encompass **insights, visualizations, etc.**, presented **using Power BI, highlighting your skills with the tool**. The **content** and **presentation** of results will be evaluated.
-	Dedicate approximately 2-4 hours to this task. While you have the liberty to choose your preferred tool, please specify the use of Power BI. If any coding is involved (e.g., in R), include it in the final report but exclude it from the 2 standard A4 pages limit.
-	The reservations dataset contains arrivals during the first week of October for two properties, while the folio invoices dataset includes expenses per reservation from the first set. **Begin with an exploratory data analysis, employing *statistical* tests to uncover correlations between features**.
-	The data should be self-explanatory with headers providing sufficient context. In case of any ambiguity, document your queries and make reasonable assumptions where necessary, recording these assumptions before proceeding with the analysis. If an answer is crucial and unobtainable, feel free to reach out via email.

## Steps taken
1.	Load data into Power BI
    1. Changed certain column names, table names, data types
    2.	Added ct column to FACTs
2.	Added DIM Date table and Measures table
3.	Created GitHub Kanban board
4. Performed EDA of reservations
   1. Categorical variables
      1. Histograms to see the distribution of categorical variables
      2. Heat maps of categorical variables
   2. Continuous variables
      1. Added stay length 
         1. Actual arrival and departure times used, unless blank, then assumed arrival and departure times used
         2. Noticed stay length = 0 for a handful of data
            ![alt text](image.png)
           3. I assume most are data errors, like the example below. This guest was the only one with a duplicate record here showing the reason
            ![alt text](image-1.png) 
        4. 