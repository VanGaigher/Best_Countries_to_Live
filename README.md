<p align="center">
  ![OIP](https://github.com/VanGaigher/Best_Contries_to_Live/assets/127983483/7a68bf97-18d2-40d5-a232-ac2a1afc9823)
</p>


# Happiness 2024: An Emotional World Snapshot


## Context

This analysis was conducted with the initial motivation to understand which factors influence a country being considered a good place to live. To achieve this, the World Happiness level in 2024 was considered. The dataset used in this study was found on Kaggle and is in the public domain.

## Columns in the Dataset

- `population_2024`: Estimated population of countries in 2024.
- `population_growthRate`: Percentage growth rate of population to 2024.
- `land_area`: Total land area of countries.
- `country`: Country name.
- `region`: Geographical region (e.g., Asia, Europe, Africa).
- `unMember`: Binary indicator (yes/no) denoting UN membership.
- `population_density`: Population density (people per sq km).
- `population_densityMi`: Population density (people per sq mile).
- `share_borders`: Number of countries sharing borders.
- `Hdi2021`: Human Development Index (HDI) for 2021.
- `Hdi2020`: HDI for 2020.
- `WorldHappiness2022`: Happiness score or ranking for 2022.

## Analysis Steps

The analysis was conducted using Python to answer the question, "Which factors impact the World Happiness level in a country?" Initially, an exploratory analysis was performed to identify general characteristics of the data, the best places to live (considering the world population happiness feeling), characteristics related to the Human Development Index, Population Growth Rate, and how these are correlated with the happiness level in 2024.

After this step, some hypothesis tests were conducted to verify similarities and differences between happiness levels among continents.

Finally, some correlations were analyzed to understand how and which variables were correlated.

## Key Findings

According to the analyzed data, the countries that top the ranking of the 5 best countries to live in are Finland, Denmark, Iceland, Switzerland, and the Netherlands. These countries share common characteristics revealing high levels of per capita wealth, low inequality, and extensive social well-being, which seem to be relevant to the population's sense of happiness.

![Top 5 Countries](https://github.com/VanGaigher/Best_Contries_to_Live/assets/127983483/dd35f4bc-29a3-48ff-b6d0-74634bbc55a8)

This observation directed attention to the variables in the dataset that impact these characteristics. In the map below, we can visualize the global happiness levels.

![Global Happiness Levels](https://github.com/VanGaigher/Best_Contries_to_Live/assets/127983483/18c59950-cc81-441b-9fae-12c6f3e3ecee)

We observe that the regions with the highest levels of happiness are in North America, Oceania, followed by European countries, and South American countries. Grouping countries according to the continents they belong to allowed a better analysis of the relationships between HDI level, Growth rate, and the happiness level.

Our exploratory analysis indicated how the data was distributed among different continents, and after some hypothesis tests, it was possible to conclude that there are no significant differences, at a 95% confidence level, between the happiness levels of European and North American countries, as well as between North American and South American countries. However, for any other combination between regions, such differences exist.

With this information and the initial analyses, we can assert with 95% confidence that the happiness levels across continents follow the ranking:
- 1st: Oceania
- 2nd: Europe
- 3rd: North America
- 4th: South America
- 5th: Asia
- 6th: Africa

Next, we observed that the HDI level has a moderate positive correlation with the happiness level. That is, as the HDI level increases, there is an increase in the sense of happiness.
![Captura de ecrã 2024-01-26 141911](https://github.com/VanGaigher/Best_Contries_to_Live/assets/127983483/695fcc88-3bb5-40f7-931e-6f9df9610f56)

Similarly, a correlation test was conducted to check if happiness levels are correlated with the Growth rate variable.

![Captura de ecrã 2024-01-26 142102](https://github.com/VanGaigher/Best_Contries_to_Live/assets/127983483/b5978c58-6acf-4b95-aa36-8649d2d66d4b)

Observing the graph, we see a negative linear correlation, but with not very strong intensity, as confirmed by the Pearson correlation. This may be derived from the influence of other variables that are not explicit. For example, we see in the graph below that the variables Growth rate 2022 and HDI 2022 are linearly correlated. The direction of the correlation is negative, i.e., when one increases, the other decreases, with a moderate intensity of approximately -0.69 (value given by Pearson correlation).

![Captura de ecrã 2024-01-26 142822](https://github.com/VanGaigher/Best_Contries_to_Live/assets/127983483/5bed9f3d-997d-4568-a06e-e4ca346942fd)


