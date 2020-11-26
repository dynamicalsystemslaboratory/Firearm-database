# Firearm Data #
Data base for firearm and gun violence related data

Data were retrieved from FBI NICS (https://www.fbi.gov/services/cjis/nics). Daily NICS data was recently published and is available at a national level. 

The file "NICS-Firearm-Background-checks" is the latest file which contains data for all states (1999-2020). The data is further divided into subcategories such as Permit, Handgun, Long gun, Other, and multiple guns related background checks.

## Mass shootings ##
The data were retrieved from the Washington Post database for mass shootings (https://www.washingtonpost.com/graphics/2018/national/mass-shootings-in-america/). Datatest *Mass shootings data state by state 1999-2019 Washington Post corrected data.csv* contains data from 1999-2019. Dates for 5 data points were corrected (highlighted in the csv file) and data further divided for each state. Specific data on location, victims killed, victims injured, total victims, number of guns used, and number of shooters (dead/alive) is available.

## Gun ownership ##
These data were retrieved from Gallup’s GPSS Crime surveys between 2000-2019.

The respondents were asked three questions:
1. Do you have a gun at home?
2. Do you have a gun anywhere else on your property such as in your garage, barn, shed, or car?
3. Do you personally own a gun, or do the gun or guns in your household belong to another household member?

Question 2 was not asked in 2001, and 2005.
Question 3  was not asked in 2001-2004 and 2006.

Codes:
1 == ‘Yes’
2 == ‘No’
3 == ‘I don’t know’
4 == ‘Decline to answer’


## Suicides with guns ##
These data were retrieved from the CDC between 2000-2016 (https://wonder.cdc.gov/controller/saved/D140/D85F952), where suicides with guns are coded as 72:74.
Dataset *Number of Suicides with guns (1998-2016, FBI).csv* was collected from <source,links> between <years>. any exceptions/anomalies.
If used in paper, cite and provide link to github.


## Homicides with guns ##
These data were retrieved from Inter-university Consortium for Political and Social Research (ICPSR) between 1999-2016.
State codes are not standard: AK and HI are coded are States 50 and 51, respectively. Otherwise, the States are ordered alphabetically as usual. 
It appears that Florida did not report homicides. In Alabama between 2011-2016, only one county reported homicides.

Homicides with guns are coded [11:15].


## Robberies with guns ##
These data were retrieved from the FBI Uniform Crime Reports between 1999-2018.
Illinois did not reports robberies in 2005 and Hawaii did not reports robberies in 2011.


## Aggravated assaults ##
These data were retrieved from the FBI Uniform Crime Reports between 1999-2018. Column C (third column) contains the number of cases where a the aggravated assault was carried out with a gun.


## Hunting licenses ##
These data were retrieved from the U.S. Fish and Wildlife Service between 2000-2018. This data set does not include the District of Columbia.


## Fatal gun accidents ##
These data sets were retrieved from Inter-university Consortium for Political and Social Research (ICPSR) between 1999-2016. Among the circumstances, code [50:53] are for accidental killings (hunting accidents, gun-cleaning accident, children playing with guns, and other negligent gun handling, respectively).

## Arrests for weapon carrying ##
These data were retrieved from the FBI Uniform Crime Reports between 1999-2018.



# Socioeconomic Data #

## population size ##
Data retrieved from the US Census Bureau

## Unemployment rate, Unemployment (Raw numbers), Employment, and Labor Force ## 
Data retrieved from US Bureau of Labor Statistics Data. For additional series if required ( https://data.bls.gov/cgi-bin/dsrv?la ).
File "BLS Data - Seasonally adjusted" contains monthly seasonally adjusted data for all states from 1999 - 2020. 
File "BLS Data - Not seasonally adjusted" contains monthly unadjusted data for all states from 1999 - 2020.

If any questions or concerns please send an email to rrs441@nyu.edu

