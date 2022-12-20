
# homework 3: Data Wrangling (Due on 10/25/2022)

In this homework, you need to work on the following datasets to generate a tidy dataset similar to `gdpminder` used in our class.

All these datasets were downloaded from gdpminder website without altering file names.

* `child_mortality_0_5_year_olds_dying_per_1000_born.csv`: to a variable with name of `child_mortality`.
* `children_per_woman_total_fertility.csv`: to a variable with name of `fertility`.
* `income_per_person_gdppercapita_ppp_inflation_adjusted.csv`: to a variable with name of `gdppc`.
* `life_expectancy_years.csv`: to a variable with name of `life_expectancy`.
* `murder_total_deaths.csv`: to a variable with name of `murder_total`.
* `population_total.csv`: to a variable with name of `population`.

* `ddf--entities--geo--country.csv` contains general information of all countries. In this homework, we need to assign countries with different types of regions.

* `ddf--entities--geo--unhcr_region.csv`: to a variable with name of `region_unhcr`.
* `ddf--entities--geo--unicef_region.csv`: to a variable with name of `region_unicef`.
* `ddf--entities--geo--world_4region.csv`: to a variable with name of `region4`.
* `ddf--entities--geo--world_6region.csv`: to a variable with name of `region6`.

# Requirment

* Use `read_csv()`.
 
* Values of variables `country` and different types of regions should be real names, not simplified code.

* All numeric variables should contain numeric values (be careful population file). 

* Please remove rows with all `NA`s on all numeric variables.

* Make figures similar to those in section 2.6 of Lecture 6. You may use `life_expectancy` vs `child_mortility`. For the count plot, you may choose any numeric variable.

# Final thoughts

Since this homework is using real datasets, which I have not used before, there may have some problems such as matching country names. I also found that the numbers of countries in numeric data files and `ddf-entities--geo--country.csv` are different. Please discuss whatever problems you find when you are generating your version of `gdpminder`.

I will also working on this homework and incorporating some good parts of your homework to make a key for this homework.




