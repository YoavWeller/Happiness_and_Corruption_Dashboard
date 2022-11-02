# Happiness and Corruption Dashboard
## Authors
* [@LolipopnJoker](https://github.com/LolipopnJoker)
## Table of Contents
* [Business problem](https://github.com/LolipopnJoker/Happiness_and_Corruption_Dashboard/blob/main/README.md#business-problem)
* [Data source](https://github.com/LolipopnJoker/Happiness_and_Corruption_Dashboard/blob/main/README.md#data-source)
* [Methods](https://github.com/LolipopnJoker/Happiness_and_Corruption_Dashboard/blob/main/README.md#Methods)
* [Tech stack](https://github.com/LolipopnJoker/Happiness_and_Corruption_Dashboard/blob/main/README.md#tech-stack)
* [Quick glance at the results](https://github.com/LolipopnJoker/Happiness_and_Corruption_Dashboard/blob/main/README.md#quick-glance-at-the-results)
* [Lessons learned and recommendation](https://github.com/LolipopnJoker/Happiness_and_Corruption_Dashboard/blob/main/README.md#lessons-learned-and-recommendation)
* [Limitation and what can be improved](https://github.com/LolipopnJoker/Happiness_and_Corruption_Dashboard/blob/main/README.md#limitation-and-what-can-be-improved)
* [Repository structure](https://github.com/LolipopnJoker/Happiness_and_Corruption_Dashboard/blob/main/README.md#limitation-and-what-can-be-improved)
* [Run Locally](https://github.com/LolipopnJoker/Happiness_and_Corruption_Dashboard/blob/main/README.md#run-locally)
## Business problem
The purpse of this dashboard is to visually depict the average happiness score for almost every country in the world, as well as some other parameteres (for detailed explanation on the dashboard elemntes please read the [Data source](https://github.com/LolipopnJoker/Happiness_and_Corruption_Dashboard/blob/main/README.md#data-source) down below).
## Data source
* ['Happiness and Corruption 2015-2020'](https://www.kaggle.com/datasets/eliasturk/world-happiness-based-on-cpi-20152020?resource=download) - The data is based on the World Happiness Report published between 2015 and 2020. It was aggregated and preprocessed by [Elias Turk](https://www.kaggle.com/eliasturk).
## Methods
* Exploratory Data Analysis (EDA) - EDA is a statistical approach of analyzing data sets to summarize their main characteristics. Because my goal was to depict different trends that could be further analyzed, I believe that an EDA approach is the best way to do it.
## Tech stack
* [Tableau](https://www.tableau.com/) - An interactive data visualization software. I used the desktop version to create the dashboard.
## Quick glance at the results
## Lessons learned and recommendation
## Limitation and what can be improved
* Data integrity
  * Data source - as mentioned in the [Data source](https://github.com/LolipopnJoker/Happiness_and_Corruption_Dashboard/blob/main/README.md#data-source) section, I didn't rely on the original data as published by the [World Happiness Report](https://worldhappiness.report/) organization. Instead, I relied on a dataset aggregated and cleaned by someone who wasn't working in this organization. While I believe that most of the datasets found on [Kaggle]( https://www.kaggle.com/) are reliable, I always prefer to fetch the data from the original one who gathered it. In future updates to this project, I intend to build a Python script that will automatically retrieve the data from the [World Happiness Report]( https://worldhappiness.report/) website, insert it into a database/CSV file, and update the dashboard.
  * Data isn't fully up-to-date – since this dataset published on Kaggle, the [World Happiness Report](https://worldhappiness.report/) organization published two more reports. I believe that comparing the happiness scores of the last two years to previous years could be interesting, because the pandemic might had negative impact on those scores. 
## Repository structure
## Run Locally
