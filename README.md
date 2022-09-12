# **Impact of Abortion ban in Foster care system based on political Ideology and Restrictiveness of Abortion Bans**

# Use Case
On June 24, 2022, the U.S. Supreme Court overturned Roe v. Wade, ending the constitutional right to an abortion. This will impact public health, access to education and the general economy. Proponents of overturning Roe have proposed adoption as an alternative to abortion, but there is a political debate about whether increasing the number of unwanted births will lead to increased numbers of children left behind in the foster care system. 
This project takes a dive into the impact that restrictive abortion laws have on the US foster care system.

# Overview 
This project focuses on:
 * Exploring the relationship between abortion rates and foster care entry rates for infants
 * Understanding the impact of abortion laws (and therefore, state’s political ideology) on rates of abortion, foster care entry, and adoption
 * Determining what factors contribute to an increase/decrease of foster care entry rates
 
Methodology / Analytic Technique:
  * Descriptive analysis
  * Time series analysis
  * Correlation Analysis
  * Hypothesis Testing

# Data Understanding
**Abortions dataset** :  (https://osf.io/kthnf/)
Comprehensive historical statistics on the incidence of pregnancy, birth and abortion for people of all reproductive ages in the US, state-level (1988-2017).

**Foster Care & Adoptions** : (https://datacenter.kidscount.org/)
Number of US children, broken down by age groups, who have entered foster care and/or been adopted by year and state in 2000-2020.

**Political Idelogy** :
The data is split into three groups - Republican, Split and Democrat

**Restrictiveness of abortion ban** : (https://www.washingtonpost.com/politics/2022/06/24/abortion-state-laws-criminalization-roe/)
grouping states based on severity of adoption ban 1-5 scale, 1 - banned or mostly banned, 2 - will be banned imminently, 3 - likely to ban, 4 - legal for now, 5 - legal and likely to be protected

# Data preparation 
 * All the datasets have been cleaned and merged based on state codes and year
 * Missing data that were not recorded for all the states are dropped
 * Missing data for certain years are imputed based on "MODE" using SimpleImputer Function

# Abortion Data Analysis
![Image](img/abortion_rate.PNG)

# Coin Comparison Screen:
- This allows you to select two cryptocurrencies to compare against each other, for all the metrics listed in the overview view.
- Select Coin 1 and Coin 2, Compare the price trends and volume
- Used multiple line charts to compare price and bar chart to compare volume
- Dynamically select open price, close price, high price and low price
- Date and Time Filters allows you to select a specific time frame for analysis
![Image](img/CoinCompare.PNG)

# Scenario Builder Screen
- This view allows you to choose a purchase date and volume and run scenarios for what that purchase would be worth in today's dollars, based on the value of the coin selected.
- Analyze the current price, profit/loss of your investments 
![Image](img/ScenarioBuilder.PNG)

