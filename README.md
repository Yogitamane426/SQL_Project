Analyzing Unicorn Companies

Overview

This project focuses on analyzing unicorn companies—startups with a valuation of over $1 billion—across various industries. The goal is to understand the trends of high-growth companies by evaluating key metrics such as their industry, valuation, founding year, unicorn year, and more. By performing detailed data analysis, we uncover insights into which industries are most successful in producing unicorns, their growth over time, and the factors influencing their valuation.

Key Objectives:

- Identify the industries with the highest number of unicorns.
- Analyze unicorn companies by year, valuation, and industry.
- Determine the average valuation and growth of unicorns.
- Analyze the time taken for companies to reach unicorn status and their valuation trends.

Database Structure

The PostgreSQL database for this project consists of a table called unicorn_companies, which contains the following columns:

company_id: Unique identifier for each unicorn company.

company_name: Name of the unicorn company.

industry: The industry the company belongs to (e.g., E-commerce, Fintech, Healthtech).

valuation: The company's valuation in billions of dollars.

founded_year: The year the company was founded.

unicorn_year: The year the company reached unicorn status.

country: The country where the company is based.

number_of_employees: The number of employees in the company.


Advanced Queries

The project includes several advanced queries using CASE statements, aggregation, and time-based analysis to uncover deeper insights:

Industry-wise classification: Group unicorns based on whether their valuation is above or below 2 billion dollars.
Year-over-year growth analysis: Calculate how unicorn production has grown each year within industries.
Valuation trends: Examine the relationship between valuation and time taken for a company to reach unicorn status.

Results & Insights

Top Industries: E-commerce, Fintech, and Healthtech produced the most unicorn companies.
Valuation Trends: E-commerce unicorns had the highest average valuations.
Year-over-Year Growth: The number of unicorns in the Fintech industry increased steadily after 2017.
Industry-Specific Growth: Healthtech companies had a higher percentage of unicorns with valuations over $2 billion.

















