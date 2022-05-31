# Investigating Suicide Rates Overview 1985 to 2016.
## by Kirill Konovalov

The dataset consists of inormation regarding suicide numbers around 101 countries in period from 1985 to 2016 years.

The dataset contains below variables:

- `country` - country to where the statistics belong.
- `year` - year from where the statistics was taken.
- `sex` - cohort sex.
- `age` - cohort age group.
- `suicides_no` - the total number of sucides in the country for the given cohort.
- `population` - the size of the cohort for the given year.
- `suicides/100k pop` - suicides per 100k for this particular cohort.
- `contry-year` - country-year pair.
- `HDI for year` - Human Development index for the given year.
- `gdp_for_year($)` - Country GDP.
- `gdp_per_capita ($)` - Country GDP per household.
- `generation` - social generation to which the current generation belong.

The date was taken from [Kaggle](https://www.kaggle.com/russellyates88/suicide-rates-overview-1985-to-2016) with more information available.

## Summary of Findings

In this analysis my primary focus is to investigate factors that could possibly influence suicide rates, as well as to get some insight on suicide rates among different generations and genders, as well as to discover some general trends.

To do this, at first I've investigated the most recent data on suicide rates among different countries to discover possible patterns, and later will focus on trends comparison of suicide rates per 100k population within different generations and gender.

The primary focus of the analysis was around universal suicide ratio of the number of suicides per 100k population. 

This metric was taken as a centralised object of analysis as it is independent from population size and therefore will be more objective in representing general trends.

## Key Insights for Presentation

During the investigation I found that middle of 1990ies was really harsh period in terms of the suicides per 100k population, hitting males especially hard.

In particular, ex-USSR countries (Russia, Lithuania) suffered especially hard, having one of the highest suicide rates per 100k in total history.

However, overall the suicide rates was declining gradually from this time onwards, as more and more countries were shifting from extreme and high suicide rates towards moderate/low category.

Together, a few more things were discovered:

##### Men tend to commit suicide more often, than women.

First of all, males tend to be more vulnerable group than females, as their suicide rates per 100k population is many times higher than females. That pattern is observed among all age groups, and observed consistently over the course of the given time period from 1985 to 2015.

##### The older the person, the higher the suicide rate is.

Another interesting discovery was done based on the age. The older the group, the higher suicide rate per 100k population is. This trend is consistent across sex, and probably partially driven by decrease of the size of the group, as well as increased number of suicides. 

It is alarming considering that planet population is getting older in general.

##### Almost all countries with high and extreme suicide rates are sitting within countries with low GDP and GDP per capita.

After additional segmentation it was discovered that pretty much all countries with high and extreme suicide rates per 100k population are coming from countries with low GDP & GDP per capita. Therefore, less lucky countries that are more economically vulnerable are prone to population suicide.



```python

```
