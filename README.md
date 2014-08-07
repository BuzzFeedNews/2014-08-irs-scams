# IRS Scams Analysis

This repository contains data and analysis used for the August 7, 2014 article "[Tax Collection Scams Skyrocket](http://www.buzzfeed.com/johntemplon/tax-collection-scams-skyrocket)."

## Data

- [data/FTC_2011-43014.csv](data/FTC_2011-43014.csv): All complaints to the Federal Trade Commission that mention IRS in the complaint. The data was received via a Freedom of Information Request. This is the first half of the data, which contains all complaints from January 1, 2011 through April 30, 2014.

- [data/FTC_5114-71014.csv](data/FTC_5114-71014.csv): All complaints to the Federal Trade Commission that mention IRS in the complaint. The data was received via a Freedom of Information Request. This is the second half of the data, which contains all complaints from May 1, 2014 through July 10, 2014 — the data the FTC received the FOIA request.

- [data/state_pop_2013.csv](data/state_pop_2013.csv): The estimated population of every state in the United States as of July 1, 2013.

- [data/state_abbreviations.csv](data/state_abbreviations.csv): A CSV designed to convert state abbreviations to full state names. Used to join the states in the FTC data with the population CSV.

## Analysis

Analysis for this project was conducted in an IPython notebook, the raw version of which can be found [here](notebooks/irs-scams.ipynb). A rendered version of the notebook, can be [viewed here](http://nbviewer.ipython.org/github/buzzfeednews/2014-08-irs-scams/blob/master/notebooks/irs-scams.ipynb).
