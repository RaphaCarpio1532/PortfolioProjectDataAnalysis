Covid-19 Data Exploration Project
Project Overview
This project explores Covid-19 data, focusing on infection rates, death percentages, and vaccination metrics across various countries and continents. Using SQL techniques, it breaks down complex data to make meaningful comparisons and visualizations possible.

Skills Used
Joins: To combine Covid-19 cases and vaccination data for enhanced insights.
CTEs: To improve readability and structure in multi-step queries.
Temporary Tables: For calculations that require staging data.
Window Functions: For cumulative metrics, like rolling vaccination counts.
Aggregate Functions: To summarize key indicators like total cases and deaths.
Data Type Conversions: Ensuring compatibility for calculations and accurate data analysis.
Views: For reusable data structures useful in visualization.
Project Breakdown
Data Preparation

Filtered the initial dataset by non-null continents and ordered data by location and date.
Analysis of Key Metrics

Death Percentage: Calculated the likelihood of death upon contracting Covid-19, country by country.
Infection Rate: Showed the percentage of the population infected, illustrating impact by population size.
Highest Infection and Death Rates: Identified countries with the highest infection and death counts in relation to their population.
Continent-Wide Analysis

Highlighted death rates by continent, providing a broader view of Covid-19’s impact globally.
Global Metrics

Summed new cases and smoothed deaths to determine global infection and death rates.
Vaccination Progress

Explored the percentage of vaccinated individuals per population.
Used CTEs, temporary tables, and views to calculate cumulative vaccination rates efficiently.
Data Storage for Visualization

Created a view for PercentPopulationVaccinated, facilitating visualization of vaccination progress over time.
How to Use the Code
Data Filtering and Exploration: Queries in this project can be used for filtering locations and continents and for viewing daily infection and death trends.
Metrics Calculation: These queries calculate percentages of death rates and infection, providing insights into the Covid-19 impact on specific populations.
Vaccination Tracking: Use vaccination queries to track cumulative vaccination percentages across locations.
Potential Applications
Data Analysis and Visualization: Integrate the views and datasets into BI tools for further analysis.
Public Health Insights: Use calculated metrics to inform strategies and understand regional Covid-19 trends.
Questions and Feedback
Feel free to explore the queries and contribute with feedback or suggestions for improving data insights and analytical techniques.
