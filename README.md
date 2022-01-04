# data-for-good
## Introduction
I used Google Big Query to access a sample of size 10,000 of company 10-K data and break down data by industry and other relevant indicators. Data was formatted in Pandas DataFrames. Using regex frameworks previously built by other contributors, I parsed for practice & risk terms that considered to be financial materiality to find co-occurrences using natural language processing techniques. I then sampled 100 data points and flagged whether each data point (represented as a paragraph) was actually financially material or not in Excel, and would update the dictionary of regex terms accordingly. I repeated this step until the sample returned an accuracy above 90% for paragraphs considered financially material. Finally, I created box plots and graphs that assess the industries holding the most flagged companies and the change over fiscal years from 2013 to 2021.

## Visuals

## Revelant Skills Used
- Python
- SQL
- Excel
- Pandas
- NumPy
- MatPlotLib
