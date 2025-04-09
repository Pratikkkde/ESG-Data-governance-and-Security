# ESG-Data-governance-and-Security
The project is all about digging into ESG (Environmental, Social, and Governance) data and figuring out what it tells us about different countries around the world. We used Power BI to explore this data in detail, and it turned out to be insightful.
I had access to a rich dataset spread across six different tables — each containing specific info about countries, indicators, years, definitions, and more. The main goal was to find the connection between all the given data and create a dashboard that could help visualize ESG trends globally.
Here’s a breakdown of the six tables we used:

ESGFootNote
Gave extra details or descriptions for specific data points using CountryCode, SeriesCode, and Year.

ESGCountrySeries
Mapped ESG indicators to different countries with a short description.

ESGData
This was the core table with actual indicator values for each country, from 1960 all the way to 2020 (and even projections for 2050!).

ESGSeriesTime
Provided time-specific descriptions for each indicator series.

ESGSeries
Explained what each indicator actually means — including its topic, definitions, units, and how it was measured.

ESGCountry
Contained detailed metadata about each country like income group, region, currency, national accounting methods, etc.
The tools used for this analysis were Excel and PowerBI with the help of DAX and advanced excel Commands.

WorkFlow:
Data Cleaning & Shaping
All the six tables were cleaned using Excel and further cleaning was done with the help of Power BI, which included handling missing values, cleaning up column names, making sure all the tables were connected properly through keys like CountryCode and SeriesCode and much more.

Model Building
Created logical relationships between the tables so we could slice and filter data smoothly across different visuals.

Dashboard Design
Built a dynamic and interactive dashboard that:
Shows ESG trends over time.
Compares countries based on specific indicators.
Highlights top and bottom performers.
Lets users explore indicators by region, income group, and more.
and much more....

Insights & Observations
We found some interesting trends, like how certain indicators improved in some countries but stayed stagnant in others. The regional and economic group comparisons also gave us a clearer picture of ESG development worldwide.

Key TakeAways:

Built a working ESG analytics dashboard from raw structured data.
Learned how to manage and make sense of multi-table data models.
Got better at storytelling through data using visuals.
Understood the importance of ESG data for global policy and planning.

