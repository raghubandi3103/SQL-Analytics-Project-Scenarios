# 💼 SQL Analytics Real-World Use Cases

This repository contains 20+ real-world SQL use cases designed for HR analytics, compensation benchmarking, workforce planning, and market research.


🔍 20 Real-World SQL Analytics Use Cases

📁 Use Case 01: Remote Manager Salaries > $90K
Scenario: Identify countries offering fully remote roles to managers with salaries above $90,000.
Purpose: Help relocation and remote hiring decisions for senior positions.
SQL Concepts: DISTINCT, LIKE, WHERE, AND

📁 Use Case 02: Top 5 Countries with Most Large Companies Hiring Freshers
Scenario: Find countries with the highest number of large-sized companies hiring entry-level candidates.
Purpose: Useful for HR tech firms placing freshers in big companies.
SQL Concepts: GROUP BY, COUNT(), TOP, ORDER BY

📁 Use Case 03: Highest Paid Part-Time Jobs in 2023
Scenario: Identify job titles with the highest average salary among part-time positions in 2023.
Purpose: Helps part-time candidates find high-paying roles.
SQL Concepts: AVG(), GROUP BY, ORDER BY, WHERE

📁 Use Case 04: % of Fully Remote Employees Earning > $100K
Scenario: Calculate what percentage of employees earning over $100K are working fully remotely.
Purpose: Highlight the attractiveness of remote, high-paying jobs.
SQL Concepts: DECLARE, SET, IF, calculations

📁 Use Case 05: Locations Where Entry-Level Salaries Exceed Market Average
Scenario: Identify countries where entry-level job salaries are higher than the global average for that role.
Purpose: Target high-opportunity locations for freshers.
SQL Concepts: CTE, JOIN, GROUP BY, ORDER BY

📁 Use Case 06: Country with Max Avg Salary per Job Title
Scenario: For each job title, find the country offering the highest average salary.
Purpose: Helps in strategic relocation and salary benchmarking.
SQL Concepts: RANK(), PARTITION BY, CTE, JOIN

📁 Use Case 07: Countries with 3-Year Continuous Salary Growth
Scenario: Detect countries where average salaries have grown steadily from 2022 to 2024.
Purpose: Indicates strong, sustainable markets.
SQL Concepts: Multiple CTEs, year-on-year comparisons

📁 Use Case 08: Remote Work % by Experience Level (2021 vs 2024)
Scenario: Compare fully remote adoption for each experience level across two years.
Purpose: Monitor shifts in remote work trends.
SQL Concepts: Subqueries, ROUND(), JOIN, percentages

📁 Use Case 09: Salary Growth % by Role and Experience (2023–2024)
Scenario: Calculate the average salary increase percentage for each job title and experience level.
Purpose: Show market movement to help adjust compensation packages.
SQL Concepts: JOIN, ROUND(), CAST(), ORDER BY

📁 Use Case 10: Employees Count by Company Size (2021)
Scenario: Count how many people worked in different company sizes in 2021.
Purpose: HR planning and historical trend analysis.
SQL Concepts: COUNT(), GROUP BY, WHERE

📁 Use Case 11: Top 3 Highest Paying Part-Time Jobs (2023)
Scenario: Find the top 3 part-time roles with the highest average salary in 2023.
Purpose: Helps consultants guide part-time seekers better.
SQL Concepts: TOP, GROUP BY, AVG(), ORDER BY

📁 Use Case 12: Countries Where Mid-Level Salary > Global Avg (2023)
Scenario: Identify countries where mid-level salaries exceed the global mid-level average.
Purpose: Guides job seekers and companies on competitive markets.
SQL Concepts: HAVING, GROUP BY, subqueries

📁 Use Case 13: Highest & Lowest Avg Senior-Level Salary by Country (2023)
Scenario: Find the best and worst paying countries for senior-level professionals in 2023.
Purpose: Salary benchmarking and global equity analysis.
SQL Concepts: TOP, ORDER BY, GROUP BY

📁 Use Case 14: Job Title-wise Salary Growth %
Scenario: Calculate % salary increase for each job title from 2023 to 2024.
Purpose: Analyze fast-growing roles.
SQL Concepts: JOIN, CASE, ROUND(), ORDER BY

📁 Use Case 15: Employment Type % Breakdown by Job Title
Scenario: Show % share of Full-time, Part-time, Contract, Freelance for each job title.
Purpose: Useful for workforce planning and job type trends.
SQL Concepts: CASE, GROUP BY, COUNT(), ROUND()

📁 Use Case 16: Top 3 Countries with Highest Entry-Level Salary Growth (2020–2023)
Scenario: Identify where entry-level roles saw the biggest salary hikes.
Purpose: Market research & hiring focus areas.
SQL Concepts: TOP, JOIN, ROUND(), ORDER BY

📁 Use Case 17: Update Remote Ratio for High-Paid Workers in US & AU
Scenario: Set remote_ratio = 100 for employees in the US or Australia earning > $90K.
Purpose: Automate remote eligibility management.
SQL Concepts: UPDATE, WHERE, TRY-CATCH for error handling

📁 Use Case 18: Apply Salary Increases by Experience Level (2024)
Scenario: Increase 2024 salaries by specific % per experience level.
Purpose: Apply mass salary corrections based on business rules.
SQL Concepts: UPDATE, CASE, WHERE

📁 Use Case 19: Year with Highest Avg Salary per Job Title
Scenario: For each job title, find which year had the highest average salary.
Purpose: Historical salary analysis for trends.
SQL Concepts: RANK(), PARTITION BY, CTE

📁 Use Case 20: Employment Type % by Role (Matrix Format)
Scenario: Create a matrix showing % distribution of employment types per job title.
Purpose: Understand contract patterns and hiring trends.
SQL Concepts: CASE, GROUP BY, ROUND()

---

## 🚀 Technologies

- SQL Server / T-SQL
- Window Functions
- CTEs
- Data Aggregation
- Case Statements





