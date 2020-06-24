# Data Analysis Portfolio
Portfolio of data analysis related projects by Ryan Carroll.
* [Main Github Page](https://github.com/ryanjcarroll)
* [LinkedIn](https://www.linkedin.com/in/ryan770)

# Project 1: [MLB Free Agent Contract Analysis](https://github.com/ryanjcarroll/MLB-Free-Agents-Data-Analysis)
*Technologies Used: Jupyter, Python, Pandas, Matplotlib, Seaborn, BeautifulSoup, JSON, SciKit-Learn*
* Web scraped all MLB free agent contract signings (2006-2019) from tables on ESPN.com, using BeautifulSoup and JSON.
* Used Pandas to clean the scraped data, ignoring certain types of low-value data such as minor league signings and retirements. Also converted several scraped values from formatted strings to integers and corrected bad values.
* Generated visualizations of how contract sizes vary by player age and the year they were signed, using Seaborn and Matplotlib.
* Used Linear Regression packages to estimate a player's contract value based on the linear weights of their age and previous statistics.
* Also web scraped the primary and secondary colors for each MLB team to format team-breakdown graphs.
<img src="https://i.imgur.com/4VR4Svb.png" alt="Bar chart showing MLB contract values by player age" width="500"/>
<img src="https://i.imgur.com/p1ZD6hL.png" alt="Bar chart showing largest MLB contract values by team" width="500"/>

# Project 2: [Recipe Analysis from Allrecipes](https://github.com/ryanjcarroll/Recipes-Data-Analysis)
*Technologies Used: Jupyter, Python, Pandas, Matplotlib, Seaborn, BeautifulSoup, JSON, Regex*
* Web scraped ~4,000 recipes from Allrecipes.com using Python's BeautifulSoup and JSON libraries.
* Using Pandas, cleaned the data. This included extracting ingredient names, converting various cook time formats to consistent numerical values, and locating HTML elements across multiple webpage layouts.
* Generated charts of the most common ingredients, title keywords, and instructions using Matplotlib.
* Analyzed distribution of recommended serving sizes and cook times, and generated visualizations using Matplotlib.
* Analyzed pairs of ingredients which appear commonly together.
<img src="https://i.imgur.com/8Bj57tA.png" alt="Bar chart showing most common ingredient pairings in Allrecipes posts" width="600"/>

# Project 3: [Exit Surveys and Employee Dissatisfaction](https://github.com/ryanjcarroll/Exit-Surveys-Data-Analysis)
*Technologies Used: Jupyter, Python, Pandas, Matplotlib, Seaborn*
* Used publicly available data sets from Queensland, Australia government to analyze employee dissatisfaction in exit surveys.
* Extensively cleaned two data sets of different formats and created common variables to merge them with.  This involved extracting career start and end dates, categorizing employees based on age and service time ranges, and isolating the surveys which were explicitly related to employee resignations.
* Used heatmaps to locate and visualize missing data, trimming down the initial datasets to find the most complete columns to use in the analysis.
* Created a boolean measure of dissatisfaction based on answers to certain survey questions across the two survey formats.
* Conducted an analysis of employee dissatisfaction by age and service time, generating visualizations.
<img src="https://i.imgur.com/rYRnvGU.png" alt="Bar chart showing percent of dissatisfied employee resignations by age group" width="300"/><img src="https://i.imgur.com/ZuFPXiS.png" alt="Heatmap showing missing values in one of the project datasets" width="300"/>
