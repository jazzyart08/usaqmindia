usaqmindia
==========

The U.S. Embassy and Consulates General in India maintain an air quality monitoring program with on-site measuring instruments and put the corresponding data [on this website](http://newdelhi.usembassy.gov/airqualitydata.html). There are csv files for 2013 and 2014, for 2015 except December which is in a pdf, and various csv for the months of the beginning of 2016.

In this repository I have made a copy of these files and provide a R code for wrangling them to get a single csv with all measures for Delhi, Mumbai, Kolkata, Hyderabad and Chennai. Refer to original source for licensing questions.

You will find the raw data in inst/extdata and my wrangling code in inst. I have made a R package out of the data so that my fellow R users can easily play with the data, and I will eventually show to examples of visualizations below.
