# Rim Protection Analysis
Finding a Measure for 'Rim Protection Ability' to Identify the Best Rim-Protecting Centers in the NBA

[Code (click here)](https://github.com/yashwantsathish/Rebounding-Analysis/blob/main/Rim%20Protection%20Analysis.ipynb)

Methodology:
1. Pulled 500+ data values from stats.nba.com API (using nba_api API Client). Extracted 'defensive' data for opponent shots taken within 6 feet of the basket (rim).
2. Structured data into Python Pandas DataFrame and cleaned to remove errors, duplicates, and irrelevant values (ex. filtered to keep only "Centers") and rename columns for clarity.
3. Deduced that horizontal bar chart was appropriate & used Python Library Plotly to plot 'PCTDiff' for each player (% effect on opponent shooting % within 6 ft).
