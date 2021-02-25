# Diamonds Analysis 
## _“Remember diamonds are created under pressure so hold on, it be your time to shine soon.”_ - Sope Agbelusi

<p align="left"><img src="https://cdn-images-1.medium.com/max/184/1*2GDcaeYIx_bQAZLxWM4PsQ@2x.png" width="80"></p>
___________________________

**Owner**: Alvaro Gil

**Bootcamp**: Ironhack - Data Analytics Part Time Nov 2020

## Overview
This is the first project of two. In this one, I have done an analysis on the diamonds data, understanding the different kinds of diamonds, according to their color, their carats, their cut...

There are two different analysis in this proyect:

- **Jupyter Notebook:** Exploratory analysis with insights regarding price depending on different characteristics of diamonds. The file can be found in this GitHub with the name: data_analysis_report. Also, at the end of this Jupyter, there is a brief Hypothesis Testin regarding prices of different subgroups of diamonds depending on their color for different cuts. For what we've tested, it doesn't seem like there is much different in prices between colors.
- **Tableau Dashboard:** Analysis made on Tableau, with three different sections:
  - Identifying the data: here we try to understand what information we are dealing with in the dataset
  - Price - Characteristics Relationships: to understand the relationship between the prices of the diamonds and their different characteristics,
  - Characteristics Deep Dive: the last section is used to understand the relationship of the characteristics between them regarding the price.

This **Tableau Dashboard** can be found in the following [link](https://public.tableau.com/profile/alvaro5559#!/vizhome/ih_datamadpt1120_project_m2_16142733820460/DiamondsAnalysis?publish=yes).

<p align="center"><img src="https://i.pinimg.com/originals/1d/f3/f9/1df3f91c7178c847952248e74eefb74b.jpg" width="500"></p>

## Results
1. There is a strong correlation between Carats and Price (calculated around 0.9)
2. Also the shape of the diamond (x, y, z) is also relevant for the price
3. Average price of Diamonds is around 4.000USD and validated after testing (p-value < 0.05 )
4. Cut might not be a strong game changer with respect to price, as Fair diamonds are, on average, more expensive than the rest of the cuts, excepting Premium. However, Fair diamonds are few in the dataset (compared to the rest of the cuts), so might be a component of lack of information.
5. Regarding clarity, SI2 diamonds seem the most expensive while IF the cheapest.
6. Finally, regarding color, I and J diamonds are the most expensive, however the seem to have a lot of dispersion regarding the price.
