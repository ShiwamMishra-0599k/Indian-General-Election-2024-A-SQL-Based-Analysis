# Indian General Election-2024 | A SQL Based Analysis
This project presents an in-depth analysis of the 2024 Indian General Election results, executed entirely through SQL. Hosted in a SQL Server Management Studio 21 environment, the analysis involved a series of targeted queries to transform raw electoral data into meaningful insights. The project moves from a high-level overview of the national mandate down to a granular, constituency-level examination of voting patterns, candidate performance, and alliance dynamics. It demonstrates a strong command of SQL for data manipulation, aggregation, and complex querying on a large, real-world dataset.

#Tech Stack
- SQL (Structured Query Language): The core technology for all data processing and analysis. The project utilizes a variety of SQL techniques, including multi-table joins, aggregate functions (COUNT, SUM), CASE statements, subqueries, and Common Table Expressions (CTEs).

- SQL Server Management Studio (SSMS) 21: The primary integrated environment used for database management and query execution.

#Data Source

Source: (https://drive.google.com/drive/folders/1TqnJbkpT_UfMekRxKeFQbYk0-WQ5r8vG?usp=sharing)

#Problem Statements Addressed
The analysis was structured to answer a series of key questions about the election outcome:

- I. National and Alliance-Level Performance
What was the total number of seats contested in the 2024 election?

How many seats were available for election in each state?

What was the total number of seats won by the NDA and I.N.D.I.A. alliances respectively?

Which individual parties within each alliance contributed to the total seat count?

Which alliance (NDA, I.N.D.I.A., or OTHER) secured the most seats overall?

- II. State and Constituency-Level Analysis
What was the breakdown of seats won by each party alliance within every state?

Who was the winning candidate in a specific constituency (e.g., Amethi), and what was their party, total votes, and margin of victory?

What was the distribution of EVM votes versus postal votes for candidates in a given constituency (e.g., Mathura)?

Which parties won the most seats in a particular state (e.g., Andhra Pradesh)?

- III. Advanced Analytical Queries
Who were the top 10 candidates with the highest number of EVM votes across the nation?

Using a CTE, who were the winning and runner-up candidates in each constituency of a specific state (e.g., Maharashtra)?

What were the aggregate statistics for a state like Maharashtra, including the total number of seats, candidates, parties, and the complete breakdown of EVM and postal votes?

#Key Insights and Impact
This project effectively demonstrates how to leverage SQL for comprehensive data storytelling. The queries provide a multi-layered view of the election, highlighting:

- Macro-Level Trends: A clear picture of the national mandate and the performance of major political alliances.

- Regional Dynamics: Insights into how electoral outcomes varied across different states, revealing regional strongholds and competitive areas.

- Granular Details: The ability to zoom into a single constituency to analyze victory margins and voting patterns, showcasing the depth of the analysis.

- Technical Proficiency: The use of advanced SQL techniques, such as data modification (ALTER TABLE, UPDATE) for creating analytical columns and CTEs for complex ranking, illustrates a robust skill set in database analysis.
