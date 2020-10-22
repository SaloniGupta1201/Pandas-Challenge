# Pandas-Challenge
**Submitted By:** Saloni Gupta\
_Date_: october, 22nd, 2020\
Pandas Homework - **HeroesOfPymoli** <br/>
Heroes Of Pymoli Game Data Analysis using Pandas Library and Jupyter Notebook

# Pymoli-Purchase-Analysis <br/>
## Purpose <br/>
This jupyter notebook analyzes trends in purchasing data included in the csv files Purchase_data.csv.
Each object in the csv file contains the following information about a purchase:
Purchaser's [ID],
Purchaser's Screen Name [SN],
Purchaser's [Age],
Purchaser's [Gender],
Purchased [Item ID],
Purchased [Item Name],
Purchase [Price]

It finds some general summary stats about all of the purchases, breaks down the gender demographics of the purchasers, analyzes the purchasing habits of different genders,breaks down the age demographics of the purchasers,finds the players who spent the most purchasing items, finds the most popular items purchased, and finds the items that were the most profitable.

## Requirements <br/>
Jupyter Notebook was used during development. It also utilizes the python library to read the data files. Pandas version 3.8.3 and jupyter notebook version 6.0.3 were used to develop this code.

Running the Code To run the notebook enter the following into the command line: $ jupyter notebook Open up the notebook HeroesOfPymoli.ipynb in your browser and then click the 'Kernel' and 'Restart and run all' option

## Methods <br/>
This notebook relies heavily on the summary statstical functions built into pandas such as sum, mean, count, and nunique. It also utilizes pandas indexing,sorting and grouping functions such as loc, sort_values, and groupby.

**************************************
The result looks as follows.

![Homework Image](./Images/Image1.png)

## Results <br/>
Observations in Data <br/>
1) Of the 780 players list, there are 576 unique players, the vast majority are male (84%) and smaller proportion of female players (14%).
2) Our peak age demographic falls between 20-24 (44.8%) with secondary groups falling between 15-19 (18.6%) and 25-29 (13%).
3) The majority of purchases were also done by the age group 20-24 with total purchase value of $1,114 although maximum purchase of 5 items is done by Lisosia93 who falls in age group 25-29.
4) Out of 183 items on purchase list, the item 'Final Critic' is the most profitable as well as the most popular item with total purchase value $59.99 having sold max 13 items, followed by 'Oathbreaker, Last Hope of the Breaking Storm' with total purchase value $50.76, selling 12 items.
5) Since the participating players were predominantly male 484 compared to 81 females, the majority of purchases were done by Male with no significant difference in the total item purchased by male vs total item purchased by female.

