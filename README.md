# Dataclean - Data clean for Dash Project

## Table of Contents

- [General Info](#general-information)
- [Planning](#planning)
- [Lessons](#lessons)
- [How to Run Notebooks](#how-to-run-notebooks)
- [Technologies Used](#technologies-used)
- [Project Status](#project-status)
- [Contact](#contact)

## General Information

The administration of a well known retail store is interested in using data collected over time from their various branches to understand consumer behaviour in the different regions of the country. Our plan is to create interactive visualisations for them generated from their data which tells a story about their customers.

They’ve provided 10 years worth of data collected from all available branches. The data is inconsistent in terms of format and content as the data collection and storage strategy is decided by the manager of a store branch.
What the customer expects is a dashboard that allows them to:

- Track the most purchased and least purchased products & product categories
overall, per region and per city (limit to top 5 and least 5)

- Track the best performing branches overall per region and per city (performance is
measured in both item quantity sold and monetary value of sales made, limit to best
10 and worst 10)

- Per hour sales for the top 10 branches identified

- Identify the top 10 and bottom 10 profitable branches and indicate how profitable they
are. (Calculate profitability by subtracting expense from total sales)

## Planning

On my first pass of the data cleanse I decided that I would clean each file individually and then create a main data source that I could read from. 
**This did not work** down to a couple of reasons:
 - As memory was allocated to each clean this built up causing both VSCode and Computer to crash. 
 - With the memory being allocated to clean it could not completed the cleanse causing kernel crashing 

I decided to take another option with support from the tutor created a less memory intensive clean however this still caused memory issues so I was unable to completely clean the full data set having only the time to clean a few regions. 

The issues of this meant I was unable to completely visualise my graphs on the dash side of the project so I am unable to ascertain if my graph will show full data once that has been plotted into them.

## Lessons
This part of the project was very difficult due to outside time constraints, issues with my machine and I felt a lack of understanding how to clean these large files within python/vscode. 
If I was to do this again with more time I would have taken the data and put this in either a postgresql database or a SQL database to read from. This would have taken away the issue of cleaning locally and would have been able to create tables of the data I required using language I am familiar with.

I also found that I was overwhelmed by the sheer volume of data provided by the project as within the course we only worked on small bites of workable data and the only once did large file data reading come up in a single assignment. This meant I felt unprepared for this part of the project and the cleaning task required. I would have like to have had some more lesson time to work through large datasets and how you can manipulate the larger data within them, this would have helped with knowing some of the better ways to clean data other than spending time trying different methods that did not work fully. 

## How to Run Notebooks
There are two sets of notebooks within this deployment
- dataclean
    this is the first pass clean notebook which did not work as intened. This is here as an example of the error and issues that can be faced. 

- dataclean-working
    this is the working clean file, this will show how to create the clean files and how to call the files. It should allow to allow own deployment.

## Technologies Used

- VS-Code
- Github
- Python 3.9.
    pandas
    ipynb (notebooks)


## Project Status

Project is: _incomplete_
Based on specifications from the customer.


## Contact

Created by Andrew Ralph-Gledhill
