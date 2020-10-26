<p align="center">
  <a href="" rel="noopener">
 <img width=200px height=200px src="https://i.imgur.com/6wj0hh6.jpg" alt="Project logo"></a>
</p>

<h3 align="center">EDA: Analysis of Happiness Score of the Countries</h3>

<div align="center">

[![Status](https://img.shields.io/badge/status-active-success.svg)]()
[![GitHub Issues](https://img.shields.io/github/issues/kylelobo/The-Documentation-Compendium.svg)](https://github.com/kylelobo/The-Documentation-Compendium/issues)
[![GitHub Pull Requests](https://img.shields.io/github/issues-pr/kylelobo/The-Documentation-Compendium.svg)](https://github.com/kylelobo/The-Documentation-Compendium/pulls)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](/LICENSE)

</div>

---

<p align="center">  A report that breaks down the country's happiness score into meaningful insights.
    <br> 
</p>

## 📝 Table of Contents

- [Team](#Team)
- [About](#about)
- [Getting Started](#getting_started)
- [Observable Trends](#trends)
- [Acknowledgments](#acknowledgement)

## 🧐 Team <a name = "Team"></a>
•	Rye Capati
•	Sandra Teh
•	Cicily George
•	Bimal Prabha

## 🧐 About <a name = "about"></a>
**Description:**
Analysing the happiness index of the world from the period 2015-2019.
Data clean-up:
1.	Merging data from 2015 to 2019
2.	Check for duplication
3.	Check for invalid value
4.	Make sure the data frame is consistent for all the data set.
5.	Make sure no rows accidentally deleted


**Summary**
1.	The top 10 and bottom 10 <br>
2.	Factors contributing to Happiness Score: <br>
    •	Freedom to make life choices <br>
    •	GDP per capita <br>
    •	Generosity <br>
    •	Health Life expectancy <br>
    •	Perceptions of corruption <br>
    •	Family/social support <br>
    •	Dystopia Residual <br>

## 🏁 Getting Started <a name = "getting_started"></a>

**Questions to Answer:** <br>
1.	What is the correlation of country happiness and 7 factors?
2.	What is determining factor look like comparing to bottom 10?
3.	Do the countries in top 10 and bottom 10 stay consistent over the year?
4.	What are the countries that making greatest changes?
5.	What are the counties did not make any changes?
6.	Can we do a prediction in year 2020?
7.	Which region has the happiest countries?


## ✍️ Observable Trends <a name = "trends"></a>

![Happiness Ranking 2015-2019](Output/ranking.png)
* The world’s happiest countries are primarily in North Western Europe, North America, and Australia & New Zealand. 

* Economy (GDP per capita) is the most important factor in evaluating a country’s happiness.

* Economy is also strongly positively correlated with other factors like Family and Health. 

* Another interesting observable trend, GDP and generosity has negative correlation factor. Reinforcing that,income does not relate to how generous you are.

![Happiness Ranking 2015-2019](Output/2019 Heatmap.png)

*	Heatmap strongly suggest GDP and family with the score above 75%, has the highest cor-relationship with happiness score.

* In much lower ranked countries even though their score was low, their family score was almost on par with the top 10 countries. Yes, there is a noticeable dip in 2016 but it came back stronger than ever in the last 3 years.

![Happiness Ranking 2015-2019](Output/2019 TopBottom Analysis.png)

* In 2015  australia,north America  , some of European  and Asian countries were dominated by GDP. And again in 2016 majority of world happiness was influenced by GDP.

* From 2017 to 2019 we have another interesting observation – it was not the income, but in fact it was family score which dominated the world happiness score.

## 🎉 Acknowledgements <a name = "acknowledgement"></a>
- UWA Data Science
- Data source: https://www.kaggle.com/mathurinache/world-happiness-report?select=2020.csv
- Data source: Gmap – geography of the region and country
- Institute of Health Metrics and Evaluation (IHME), Global Burden of Disease (GBD): http://ghdx.healthdata.org/gbd-results-tool
- Rest Countries API: https://restcountries.eu/rest/v2/

