# FBI NICS Firearm Background Check Data
## Introduction: 
The dataset used in this analysis comes from FBI's National Instant Criminal Background Check System.The dataset used in this analysis comes from FBI's National Instant Criminal Background Check System. NICS is mandated by the Brady Handgun Violence Prevention Act of 1993 and launched by the FBI on November 30, 1998. NICS is used by Federal Firearms Licensees (FFLs) to instantly determine whether a prospective buyer is eligible to buy firearms or explosives. Before ringing up the sale, cashiers call in a check to the FBI or to other designated agencies to ensure that each customer does not have a criminal record or isn’t otherwise ineligible to make a purchase. The FBI provides data on the number of firearm checks by month, state, and type. These statistics represent the number of firearm background checks initiated through the NICS.Sales estimates are calculated from handgun and long gun background checks. Permit checks and other categories of background checks are excluded. The purpose of this analysis is to check the trend in background checks on hand gun and long run and as well check the top 5 states that have the highest background checks for fire arms.

The purpose of this analysis is to check the trend in background checks on hand gun and long run and as well check the top 5 states that have the highest background checks for fire arms.

## Data wrangling process
I imported the following libraries for this project:
Pandas

Numpy

Matplotlib

Seaborn

The dataset consists of 12485 observations or rows and 27 columns or variables. Most columns were drooped becuase they were not relevant to answer the above questions. I worked with three columns which are long run, short gun and I created a column to sum the two columns up and named it 'Totals'. I changed the data type of date to datetime which was initially string.

## Conclusion
From the analysis, it is shown that the highest background checks for handgun was done in the year 2016 and highest background checks for longgun done was in 2013. The trend also shows that there will be decrease in background checks in the coming year due to new laws to hold a firearm. 

The top 5 states with highest background checks are: 
1.California 

2.Alabama 

3.Arizona 

4.Arkansas 

5.Alaska 

Furthermore the analysis shows that 1999 background checks are higher than the ones in 2017 when comparing the total checks between 1999 and 2017.

Limitations: During the analysis some columns were dropped due to the fact that they are not up to date which I have to drop them. If they had been in the analysis, more insights would have been deduced.
