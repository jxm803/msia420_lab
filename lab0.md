# MSIA 420 Lab 0

## Date: January 9, 2020

This is an introductory lab session meant to test your data manipulation skills in R. This lab consists of a set of tasks analyzing the NYC-flights14 dataset. It contains flights' data from the Bureau of Transporation Statistics for all the flights that departed from New York City airports beteen Jan and Oct 2014. The dataset is available at:

https://raw.githubusercontent.com/Rdatatable/data.table/master/vignettes/flights14.csv 

## Tasks

1. Find the 10 most common destinations from NYC airports from Jan-Oct 2014?
2. Find the top 3 routes (origin-dest pair) with the maximum number of flights.
3. For each NYC airport (JFK,LGA and EWR), plot the total number of flights each day in the month of June(6).
4. Find the number of unique routes served by each carrier
5. Rate the airlines (carrier) according to their on-time performance (arr_delay).
6. Rate the airlines according to the total number of miles flown - do both unweighted and weighted (weighted by the total number of flights).
7. Among flights with delayed departures (dep_delay positive), find the number of flights that have arrived early or on-time at the destination (arr_delay non-positive)? Does this "making up" have anything to do with the distance?