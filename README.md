## Salary survey reports

Analysis & dynamic visualizations were built with pandas, numpy, matplotlib, plotly, and other common python libs.

Data for this report was collected from European IT community in 2015-2020. Special thanks to [Viktor](https://www.asdcode.de/) for great datasets!


### Analysis

Salary survey report 2019 - [click here](https://github.com/Ksyula/Salary-report/blob/master/Salary_servey_report_2019/salary-report-2019.ipynb)

Salary survey report 2020 - [click here](https://ksyula.github.io/Salary-report/index.html)

### Datasets
Data used for plotting is available in spreadsheets:

[2015](https://docs.google.com/spreadsheets/d/1HxFcvoUYCxHFYRQfnGkCWc2OydUyvL8J8SsH5aWmd8g/edit#gid=395050397)
[2016](https://docs.google.com/spreadsheets/d/1HxFcvoUYCxHFYRQfnGkCWc2OydUyvL8J8SsH5aWmd8g/edit#gid=1435836303)
[2017](https://docs.google.com/spreadsheets/d/14DvDMc-RWkZFBdaY5WvETiudWIe8u-DNarAoIqZemXU/edit#gid=1018969845)
[2018](https://docs.google.com/spreadsheets/d/1qRLoD-9vHUC76Wgh1eOqZWeGoSoNkWOnuV6vce5pmLo/edit#gid=825462253)
[2019](https://docs.google.com/spreadsheets/d/13p6Hr9kSZuVKbQgOT_BcgasEvOuqEvt0Y0c78S5rlvw/edit#gid=1753613754)
[2020](https://docs.google.com/spreadsheets/d/1DjPgQeBu53I0Dws4YMbXyyQdWDLpMtkSu4FhGux0epY/edit#gid=1727021736)

### List of available plotly/matplotlib charts

1. Overall dynamics over 2015-2019 years
* interactive plotly line plot of number of responses
* interactive plotly line plot of median of salaries
2. Age of respondents participating in salary survey 2019
* interactive plotly bar chart
3. Gender of respondents participating in salary survey 2019
* interactive plotly pie chart representing the proportion of respondents by gender
4. Cities & countries of respondents
* static matplotlib donut chart of the major cities in the survey responses & average salaries in cities
* static matplotlib donut chart of the major german cities & average salaries in cities
5. Languages of respondents participating in salary survey 2019
* static matplotlib Pie-in-a-Donut chart of the most common languages at work in common countries
* stacked bar chart by company types and used languages
6. Salaries of tech specialists from survey 2019
* interactive plotly scatter of salaries (EUR/year) vs. total experience in years of developers and technical specialists
* interactive plotly rug plots of salaries by seniority level
7. Salaries of specialists by technology/programming language
* interactive plotly bar chart of responders' shares by technologies
* interactive plotly ensemble of boxplots by technologies
8. Yearly brutto salaries of specialists in Germany in 2018-2019 years with bonuses and stocks
* interactive plotly facet boxplots to compare salaries distributions over 2018-2019 with bonuses and stocks
9. Yearly brutto yearly salaries of all specialists from Germany participated in surveys from 2015 to 2019.
* interactive plotly 1D density curves of brutto salaries by years
* interactive plotly rug plots of salaries by years
10. Yearly brutto salaries across the most represented cities in survey 2019
* interactive plotly 1D density curves of brutto salaries by cities
* interactive plotly rug plots of salaries by years
11. Yearly brutto salaries of specialists by seniority level in two german cities
* ensemble of interactive plotly histograms by seniority level per city
