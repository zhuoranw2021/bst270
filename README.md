
Final project for BST 270: Reproducible Data Science

Instructor: Viola Fanfani

Author: Zhuoran (Joanne) Wei

Contact: zhuoranwei@hsph.harvard.edu

School: Harvard School of Public Health

Date; 01/22/2023

The goal of this project is to reproduce COVID-19 visualizations and tables published by the New York Times (https://www.nytimes.com/interactive/2021/us/covid-cases.html). 

There are 4 plots/tables to reproduce: 

1. New cases as a function of time with a rolling average plot - the first plot on the page (you don’t need to recreate the colors or theme)

2. Table of cases and deaths - the first table on the page

3. The county-level map for previous week (‘Hot spots’) - the second plot on the page (only the ‘Hot Spots’ plot)

4. Table of cases by state - the second table on the page (do not need to include per 100,000, 14-day change, or fully vaccinated columns columns)

The data I used is from NYT GitHub repository (us-counties.csv in https://github.com/nytimes/covid-19-data). Data for county populations was downloaded from The US Census Bureau (https://www2.census.gov/programs-surveys/popest/datasets/2010-2019/counties/totals/co-est2019-alldata.csv).


The rmarkdown file "270_individual_project.Rmd" contains the codes, steps and comments for reproducing the four plots/tables. 

The html file named "270_individual_project.html" is the knitted rmarkdown "270_individual_project.Rmd".  

The folder "original_figures" contains the .png files for the original plots/tables.

The plots/tables I reproduced are saved in the folder "reproduced_figures." 


Coding language: R

Rstudio Version 2022.12.0+353 (2022.12.0+353)

R version 4.2.2 (2022-10-31)






