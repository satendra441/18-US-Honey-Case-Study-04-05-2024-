# US_Honey_Production-EDA
Explporatory data analysis on "Honey Production" data in US from the year 1998 to 2021
## Objectives of this project
- To get insights about the United States Honey Production from 1998 to 2021
- Get information about the honey production trend in United States

## Dataset
- Get the [dataset here](https://github.com/avinabagh98/US_Honey_Production-EDA/blob/66fbc4963f445d44990cb4e432af162564ebdcf8/honeyproduction%201998-2021.csv)
- The dataset is having 986 rows and 8 columns. It has size of 49.9 KB

## Background of Dataset
In 2006, global concern was raised over the rapid decline in the honeybee
population, an integral component of American honey agriculture. Large
numbers of hives were lost to Colony Collapse Disorder, a phenomenon of
disappearing worker bees causing the remaining hive colony to collapse.
Speculation as to the cause of this disorder points to hive diseases and
pesticides harming the pollinators, though no overall consensus has been
reached. The U.S. used to locally produce over half the honey it consumes
per year. Now, honey mostly comes from overseas, with 350 of the 400
million pounds of honey consumed every year originating from imports. This dataset provides insight into honey production supply and demand in
America from 1998 to 2021.

## About Dataset
- **State**: Various states of the United States.
- **numcol**: : Number of honey-producing colonies. Honey producing colonies
are the maximum number of colonies from which honey was taken during
the year. It is possible to take honey from colonies that did not survive the
entire year.
- **yieldpercol**: : Honey yield per colony. Unit is pounds.
- **totalprod**: Total production (numcol x yieldpercol). Unit is pounds.
- **stocks**: : Refers to stocks held by producers. Unit is pounds.
- **priceperlb**: Refers to average price per pound based on expanded sales. The
unit is dollars.
- **prodvalue**: Value of production (totalprod x priceperlb). The unit is dollars.
- **year**: Year of production.

## Insights from Data
In this data, there is no missing value spotted. So lets talk about the data.
The data is all about honey production, supply and demand in United States from 1998 to 2021. Over the year the production goes down and down.
The **all time best production** happened in the year **2000**. The total production in 2000 is of **219,558,000 pounds**.<br>
<p align ="center">
<img src = "https://github.com/avinabagh98/US_Honey_Production-EDA/blob/main/1.png"/>
</p>

In this dataset we have 44 states. Their production trends shows that **North Dakota** has the highest production from the year span of 1998 to 2021.
Production wise Top  10 cities are as follows - 
- North Dakota    (797,000,000 pounds)
- California      (457,195,000 pounds)
- South Dakota    (417,516,000 pounds)
- Florida         (343,697,000 pounds)
- Montana         (265,742,000 pounds)
- Minnesota       (210,530,000 pounds)
- Texas           (177,325,000 pounds)
- Michigan        (116,067,000 pounds)
- Wisconsin       (106,716,000 pounds)
- Idaho            (95,207,000 pounds)

<p align ="center">
<img src = "https://github.com/avinabagh98/US_Honey_Production-EDA/blob/main/2.png"/>
</p>

But take a peak at the production per year wise. It shows that, for the year 1998 the highest production happened in the California, but soon after North Dakota
takes the place and stand there for year and year and year. Also read [North Dakota leads nation in honey production for 15th year](https://apnews.com/article/5749289cc5ee41cf83c5e8a59825e3ac)

<p align ="center">
<img src = "https://github.com/avinabagh98/US_Honey_Production-EDA/blob/main/3a.png"/>
<img src = "https://github.com/avinabagh98/US_Honey_Production-EDA/blob/main/3b.png"/>
<img src = "https://github.com/avinabagh98/US_Honey_Production-EDA/blob/main/3c.png"/>
<img src = "https://github.com/avinabagh98/US_Honey_Production-EDA/blob/main/3d.png"/>
<img src = "https://github.com/avinabagh98/US_Honey_Production-EDA/blob/main/3e.png"/>
<img src = "https://github.com/avinabagh98/US_Honey_Production-EDA/blob/main/3f.png"/>
</p>

Here we can see the data of every other year. And as seen in the charts, second place by production, the states "California" and "South Dakota" are giving tough
fight to each other.

<p align ="center">
<img src = "https://github.com/avinabagh98/US_Honey_Production-EDA/blob/main/3g.png"/>
<img src = "https://github.com/avinabagh98/US_Honey_Production-EDA/blob/main/3h.png"/>
<img src = "https://github.com/avinabagh98/US_Honey_Production-EDA/blob/main/3i.png"/>
<img src = "https://github.com/avinabagh98/US_Honey_Production-EDA/blob/main/3j.png"/>
<img src = "https://github.com/avinabagh98/US_Honey_Production-EDA/blob/main/3k.png"/>
<img src = "https://github.com/avinabagh98/US_Honey_Production-EDA/blob/main/3l.png"/>
</p>


### But Why North Dakota?
Well ! as per internet, North Dakota's climate is just right. It's conducive to flowers' production of nectar, which bees use to make honey. “Warm days and cool nights 
are optimal for nectar secretion for a number of plants that honeybees visit.

In 2006, large and mysterious losses of honey bee colonies led entomologists to classify a set of diagnostic symptoms as Colony Collapse Disorder (CCD) and spurred major efforts to measure, quantify, and understand pollinator loss.

Before 2006 trend look like this -
<p align="center">
<img src= "https://github.com/avinabagh98/US_Honey_Production-EDA/blob/main/4.png"/>
</p>

Honey production colonies are going less and less in number, so downward trend created towards 2006.

<p align="center">
<img src= "https://github.com/avinabagh98/US_Honey_Production-EDA/blob/main/5.png"/>
</p>

And after 2006, though the colony number grows up but the production goes down.<br>
The total honey production per year goes down i.e. the honey production is decreasing.
As the production is decreasing, the cost of production is increasing year by year, cause the demand is growing due to the growing population.
Read also [Demand for honey reaches all-time high, says USDA](https://www.snackandbakery.com/articles/99265-demand-for-honey-reaches-all-time-high-says-usda#:~:text=The%20growth%20in%20demand%2C%20in,honey%20being%20a%20healthy%20sweetener.)

<p align="center">
<img src= "https://github.com/avinabagh98/US_Honey_Production-EDA/blob/main/6a.png"/>
</p>
Highest cost of production comes in the year 2014 and the lowest is in 1999 (From the chart). 






