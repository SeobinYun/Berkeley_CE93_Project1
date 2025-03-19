# CE93_Project1

## Fertility Rate and Life Expectancy Among Countries
By: Seobin Yun and Connor Clark


In recent years, earth can expect to introduce an astonishing 140 million
newborns to the new world! Without proper context, one might assume this
number to be extremely large or extremely small, depending on who you ask.
Nonetheless, certain variables should be considered when discussing the topic of
newborns each year, which we will refer to as **fertility rate**. The variable we will
focus on in relation to the fertility rate will be **life expectancy**. In this report, we
will analyze the potential relationship between life expectancy and fertility rate
within the United States for given years.
Firstly, let's define our variables to better understand the quantity assigned to
each variable. **Fertility rate** is define as the number of births per woman, while
the **life expectancy** is defined as the expected amount of years for that newborn
to live. 

To set up such a relationship, we have selected two data sets, both from
the CE93 Data Summaries spreadsheet (***CE93_08_Fertility_Expectancy.csv***) : (1) Fertility Rate (births) and (2) Average
Life Expectancy (yr). The data can be observed or downloaded into a CSV file by
visiting the gapminder website (https://www.gapminder.org/data/), where both
datasets have the year, as columns, along the x-axis, and the country, as rows, In [3]:
along the y-axis, with corresponding values in each cell. Along with the data
itself, the site provides sources from which data was collected to compile the
data set itself. However, we will instead be utilizing the provided data frame,
which merges the two data sets into a single data frame, rather than working
with two separate tables.
We have shown an idea of what you can expect from the datasets below. As one
can observe, the common variable between both data sets is the country along
with the corresponding year, which is where we will perform our analysis.

|Feature|Units|Description|Data type|
|:-|:-|:-|:-|
|country|N/A|country name|object|
|Fertility_rate|births|Average annual birth rate per country|float64|
|Life_expectancy|year|Average lifespan of individuals |float64|

**To check our conclusion, please refer to the file [CE 93 Engineering Data Analysis Project Final.ipynb](https://github.com/SeobinYun/Berkeley_CE93_Project1/blob/master/CE%2093%20Engineering%20Data%20Analysis%20Project%20Final.ipynb).**
