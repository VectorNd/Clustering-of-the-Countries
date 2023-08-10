# Clustering-of-the-Countries

## Objective 
Categorise and cluster countries based on their socio-economic and health factors . Based on this , We will find out the countries which are in dire need of help .

## Data Description
We have 167 countries reflected by 9 different socio-economic/health features:

| Variable | Description | Type     |
| :-------------: | :---------- | :-----------: |
|`country`|Name of country|`chr`|
|`child_mort`|Death of children under 5 years of age per 1000 live births|`dbl`|
|`exports`|Exports of goods and services per capita.  Given as %age of GDP per capita.|`dbl`|
|`health`|Total health spending per capita.  Given as %age of GDP per capita.|`dbl`|
|`imports`|Imports of goods and services per capita.  Given as %age of the GDP per capita|`dbl`|
|`income`|Net income per person|`int`|
|`inflation`|The measurement of the annual growth rate of the Total GDP|`dbl`|
|`life_expec`|The average number of years a new born child would live if the current mortality patters are to remain the same|`dbl`|
|`total_fer`|The number of children that would be born to each woman if the current age-fertility rates remain the same|`dbl`|
|`gdpp`|The GDP per capita.  Calculated as the Total GDP divided by the total population|`int`|

We will perform some **principal component analysis**, **k-means clustering**, and **hierarchical clustering** using scikit-learn and matplotlib.
