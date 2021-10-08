# pandas-challenge
Repo for Pandas Homework

Please see the pandas source code for HeroesOfPymoli.ipynb

Analysis is documented in the Analysis.txt file. 

## Player Count

* Total Number of Players is calculated with the value_counts() on the "SN" field.

### Purchasing Analysis (Total)

* Number of Unique Items -calculated using value_counts() on the "Iem ID"
* Average Purchase Price -calculated using mean() on the "Price"
* Total Number of Purchases - calculated by finding the length of the  "Purchase  ID"
* Total Revenue - calculated using sum() on the "Price"

purchase_analysis_df  data frame is created and populated with the above calculations.

### Gender Demographics
Rows with null values are removed from the dataframe.
Data frame is grouped on "Gender" and unique values of the SN are found.

Below calculations are done with the values grouped on gender.
* Percentage and Count of Male Players 
* Percentage and Count of Female Players
* Percentage and Count of Other / Non-Disclosed

### Purchasing Analysis (Gender)

Data is grouped by gender and the unique values of SN are found.
Below values are calculated with the grouped information.

  * Purchase Count
  * Average Purchase Price
  * Total Purchase Value
  * Average Purchase Total per Person by Gender
  
  New data frame for the purchase analysis is created and populated with the calculated info.

### Age Demographics
Bins are created for age groups  and a column of Age_summary is created and grouped on the field.

Below calculations are done for the age_summary data frame

  * Purchase Count
  * Average Purchase Price
  * Total Purchase Value
  * Average Purchase Total per Person by Age Group
  * Purchase Count
  * Average Purchase Price
  * Total Purchase Value
  * Average Purchase Total per Person by Age

### Top Spenders

* Identify the the top 5 spenders in the game by total purchase value, then list (in a table):
  * SN
  * Purchase Count
  * Average Purchase Price
  * Total Purchase Value

### Most Popular Items
Items are listed in the descending order of the purchase counts .

### Most Profitable Items
Items are listed in the descending order of the total purchase value.

