# data-for-good
## Motivation
This project is part of a research initiative by the [Rights CoLab] (https://rightscolab.org) and the Columbia Data Science Institute. Rights CoLab is working with the Sustainability Accounting Standards Board (SASB) to develop and define a strengthened set of disclosure standards that investors can use to persuade companies to improve labor rights for both direct employees and workers in their supply chains. I'm working on this initiative as a DSI scholar under the mentorship of Rights CoLab co-founders Joanne Bauer and Paul Rissman.
## Introduction
I used Google Big Query to access a sample of size 10,000 of company 10-K data and break down data by industry and other relevant indicators. Data was formatted in Pandas DataFrames. Using regex frameworks previously built by other contributors, I parsed for practice & risk terms that considered to be financial materiality to find co-occurrences using natural language processing techniques. I then sampled 100 data points and flagged whether each data point (represented as a paragraph) was actually financially material or not in Excel, and would update the dictionary of regex terms accordingly. I repeated this step until the sample returned an accuracy above 90% for paragraphs considered financially material. **All the relevant code can be found [here](https://github.com/jat2211/data-for-good/blob/main/10K_Labor_Practices.ipynb).**
## Visuals
For visualizations of the data, I primarily used MatPlotLib, which includes:
- [Box Plot](https://github.com/jat2211/data-for-good/blob/main/Screen%20Shot%202021-12-22%20at%202.48.34%20AM.png) that shows the percentage of companies in a given industry that had practice or labor-related risk terms that co-occurred with terms relating to supply chains from 2013 to 2021.
- [Graph](https://github.com/jat2211/data-for-good/blob/main/numcomp_chart.png) that displays the top 15 industries with the most companies that had the same practice/labor-related risk terms and supply-chain terms co-occurrences across all years.
- [Graph](https://github.com/jat2211/data-for-good/blob/main/pct_chart.png) that displays the top 15 industries with the highest percentage of companies that had practice/labor-related risk terms and supply-chain terms co-occurrences across all years.
## Media
For more insight into how the results of my work has led to "some important findings here that we would not have been able to otherwise surface", please check out this [article](https://rightscolab.org/applying-our-methods-to-advance-standard-setting-for-diversity-equity-inclusion-dei/) highlighting my work on 10-K's in parallel with my team member's work on a separate dataset.
## Revelant Skills Used
- Python
- SQL
- Excel
- Pandas
- NumPy
- MatPlotLib
- **Broader Domains: natural language processing, data science**
