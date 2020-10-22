# Pandas-Challenge
**Submitted By:** Saloni Gupta\
_Date_: october, 22nd, 2020\
Python Homework - **Pandas-HeroesOfPymoli** <br/>
Heroes Of Pymoli Game Data Analysis using Pandas Library and Jupyter Notebook

# Pymoli-Purchase-Analysis <br/>
## Purpose <br/>
This jupyter notebook analyzes trends in purchasing data included in the csv files Purchase_data.csv.
Each object in the csv file contains the following information about a purchase:
Purchaser's [ID]
Purchaser's Screen Name [SN]
Purchaser's [Age]
Purchaser's [Gender]
Purchased [Item ID]
Purchased [Item Name]
Purchase [Price]

It finds some general summary stats about all of the purchases, breaks down the gender demographics of the purchasers, analyzes the purchasing habits of different genders,breaks down the age demographics of the purchasers,finds the players who spent the most purchasing items, finds the most popular items purchased, and finds the items that were the most profitable.

## Requirements <br/>
Jupyter Notebook was used during development. It also utilizes the python library to read the data files. Pandas version 3.8.3 and jupyter notebook version 6.0.3 were used to develop this code.

Running the Code To run the notebook enter the following into the command line: $ jupyter notebook Open up the notebook HeroesOfPymoli.ipynb in your browser and then click the 'Kernal' and the 'Restart and run all option'

## Methods <br/>
This notebook relies heavily on the summary statstical functions built into pandas such as sum, mean, count, and nunique. It also utilizes pandas indexing,sorting and grouping functions such as loc, sort_values, and groupby.

## Results <br/>
Observations in Data <br/>
The average item's purchase price was highest for other/nongender users. The average item's purchase price for men was greater than that for women.

The largest portion of users were between the ages of 20-24. Over 40% of users fell in this age range.

The most profitable items were bought fewer times for a greater cost than the most popular items.
