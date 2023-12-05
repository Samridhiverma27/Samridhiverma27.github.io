---
name: Final Project IS 445 
tools: [Python, HTML, ipywidgets]
image: assets/pngs/Gender_Distribution_of_Unemployment.png
description: Decades of Unemployment - A Comprehensive Analysis Across US States. Team members - Samridhi Verma & Mahir Thakkar
custom_js:
  - vega.min
  - vega-lite.min
  - vega-embed.min
  - justcharts
---

# Decades of Unemployment - A Comprehensive Analysis Across US States¶
### Team members : Samridhi Verma and Mahir Thakkar

## 1.1 Objective:

Unemployment, a persistent challenge in the United States, extends beyond mere statistics—it has far-reaching consequences that touch every aspect of society. This report seeks to unravel the intricate story of unemployment trends across US states over the past four decades, employing a comprehensive analysis of meticulously gathered data.

## 1.2 Purpose:

Our data visualisation notebook has one main goal: to show unemployment trends across US states in a way that's easy to understand. We're using reliable data from the Bureau of Labor Statistics to create pictures and charts that tell the story of job situations over many years. Our aim is to help everyone – from everyday people to decision-makers – see the impact of unemployment on society. Through simple and interactive visuals, we want to start conversations and help find solutions to unemployment challenges. This isn't just about numbers; it's about making the information clear and encouraging everyone to think about how we can create a stronger and fairer economy together.

## 1.3 About the Data

## Primary Dataset:
Our primary dataset, the backbone of our analysis, is sourced from the Bureau of Labor Statistics (BLS). Specifically, we rely on the BLS's Economic News Release on (Monthly) State Employment and Unemployment. This dataset, spanning from January 1976 to the present, provides a detailed account of unemployment rates across US states. The statistics encompass crucial variables such as the Year/Month of Statistic, Total Civilian Non-Institutional Population in State/Area, Total Civilian Labor Force in State/Area, Percent (%) of State/Area's Population, Total Employment in State/Area etc. The meticulous documentation by the BLS ensures the reliability and accuracy of the information, forming the cornerstone of our comprehensive analysis.

## Additional Datasets:

In addition to our primary dataset, we incorporate two supplementary datasets to enrich our understanding of the unemployment landscape. The first supplementary dataset delves into demographic breakdowns, offering insights into how unemployment affects different segments of the population. Sourced from https://www.kaggle.com/datasets/asaniczka/unemployment-rates-by-demographics-1978-2023, this dataset includes variables such as age, gender, ethnicity, and education levels, providing a nuanced perspective on the social dimensions of unemployment.

The second supplementary dataset focuses on minimum wage dynamics across US states. Acquired from https://www.kaggle.com/datasets/lislejoem/us-minimum-wage-by-state-from-1968-to-2017, this dataset elucidates the variations in minimum wage rates over time. By examining the intersection of minimum wage policies and unemployment trends, we aim to uncover potential correlations and implications for the labor market.

Together, these datasets form a comprehensive foundation for our analysis, allowing us to explore the intricate interplay of economic, demographic, and policy factors influencing unemployment across the United States

Let’s look at our dataset

<vegachart schema-url="{{ site.baseurl }}/assets/json/interactive_unemployment_chart.json" style="width: 100%"></vegachart>

<div class="left">
{% include elements/button.html link="https://raw.githubusercontent.com/Samridhiverma27/Samridhiverma27.github.io/main/python_notebooks/Unemployment%20in%20USA.csv" text="The Data" %}
</div>


<div class="right">
{% include elements/button.html link="https://github.com/Samridhiverma27/Samridhiverma27.github.io/blob/main/python_notebooks/Final%20Project%20Part%203%20-%20Samridhi%20Verma%20and%20Mahir%20Thakkar%20.ipynb" text="The Analysis" %}
</div>

### Analysis
In this interactive visualization, we aim to explore and analyze the trends in unemployment across different U.S. states over the years. By selecting a specific state using the dropdown menu, users can dynamically observe the variations in the monthly unemployment rates. The bar plot visually represents the percentage of the labor force unemployed for each month in the chosen state and year, offering a clear depiction of the fluctuations in unemployment levels. This visualization enables users to identify patterns, seasonal trends, and potential anomalies in the unemployment data. By interacting with the widgets, researchers, policymakers, and analysts can gain valuable insights into the dynamics of the labor market, aiding in the formulation of targeted policies and strategies to address unemployment challenges in specific regions and time periods.

<vegachart schema-url="{{ site.baseurl }}/assets/json/altair_minimum_wage_data.json" style="width: 100%"></vegachart>

### Contextual Plots
These visualizations offer a glimpse into unemployment trends based on age groups and gender. The first plot illustrates how unemployment rates vary across different age brackets over time, helping identify age-specific patterns. The second plot, a stacked area chart, provides insights into the gender distribution of unemployment, showcasing the relative contributions of male and female unemployment rates to the overall trend. These visualizations enable a quick and clear understanding of how different demographic factors influence and contribute to overall unemployment rates, aiding policymakers and analysts in developing targeted strategies for specific groups in the labor market.

<vegachart schema-url="{{ site.baseurl }}/assets/json/altair_unemployment_data_gender.json" style="width: 100%"></vegachart>

<vegachart schema-url="{{ site.baseurl }}/assets/json/altair_unemployment_data_age_groups.json" style="width:100%"><vegachart>

## CITATIONS
Lislejoem. (2020, December 31). US minimum wage by state from 1968 to 2020. Kaggle. 
https://www.kaggle.com/datasets/lislejoem/us-minimum-wage-by-state-from-1968-to-2017

USA unemployment rates by Demographics & Race. Kaggle. (n.d.). 
https://www.kaggle.com/datasets/asaniczka/unemployment-rates-by-demographics-1978-2023

## Random:
andhsbdjasasbsdmsjdjcksdkd - gibberish text to check formatting. 

