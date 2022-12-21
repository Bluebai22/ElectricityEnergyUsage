# ElectricityEnergyUsage
This is the data analysis and visualization project I worked on with team of 4, using data from U.S. electricity website and telling the story of CO2 emission and energy usage in  electricity industry.

# Project Background
Climate change affects all human beings, and many impacts are projected to worsen as temperatures and sea levels continue to rise and some extreme weather events become more common. Hence, We aimed to provide insights to the federal government and cooperates by visualizing and analyzing data of CO2 emission in electricity industry in the United States. We used Tableau Prep and Tableau and R language to conduct data visualization and statistical analysis.

#Data Source
The dataset is downloaded from U.S. Energy Information Administration (EIA) and United States Environmental Protection Agency (EPA) and from 1990 to 2020.

#Data Preparation
To maintain a high level data quality, we delete some irrelavant roles and missing data with Tableau Prep. Then, we use inner join to merge two datasets into one.
![plot](https://github.com/Bluebai22/MoviePreference/blob/main/Github/TableauPrep_Cleaning.png)

#Data Visualization
We used different charts to demonstarte various types of data 

Frist, we used line chart to show the CO2 emission and net electricity generation.

![plot](https://github.com/Bluebai22/MoviePreference/blob/main/Github/Line%20Chart.png)

Second, we used treemap to demonstrate the industry source of CO2 emission

![plot](https://github.com/Bluebai22/MoviePreference/blob/main/Github/Treemap.png)

Then, we used multi-dimension bar chart to show the CO2 Emission of different state in the U.S.

![plot](https://github.com/Bluebai22/MoviePreference/blob/main/Github/BarChart.png)

Meanwhile, we used heatmap to show the net electricity generation by energy source of different state.

![plot](https://github.com/Bluebai22/MoviePreference/blob/main/Github/Heatmap.png)

Lastly, we used map plot to indicated the average revenue of electricity industry in different state.

![plot](https://github.com/Bluebai22/MoviePreference/blob/main/Github/map.png)

#Data Analysis
We aslo build a liner regression model with multiple regressors to test the relationship between CO2 emission in electricity industry and electricity generation from different energy sources. It can be observed that the overall fit of this liner regression model is good since R-squared equals to 0.9985. Nuclear and renewables source are not significant related to CO2 emission, and coal, natural gas and petroleum have the significantly liner relationship to CO2 emission at 1% significant level. Furthermore, coal shows the strongest impact on CO2 emission since the estimated coefficient is the highest.

![plot](https://github.com/Bluebai22/MoviePreference/blob/main/Github/linerregression.png)

We furthur discovered that the non-liner relationship bwtween CO2 emission and Natural gas, which furthur proved natural gas is a cleaner energy source.

![plot](https://github.com/Bluebai22/MoviePreference/blob/main/Github/CO2vsNaturalGas.png)
