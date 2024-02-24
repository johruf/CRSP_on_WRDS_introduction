# README	



## Contact and citation

**Author and affiliation:**

Johannes Ruf [j.ruf@lse.ac.uk](), [www.maths.lse.ac.uk/Personal/jruf](http://www.maths.lse.ac.uk/Personal/jruf/), London School of Economics and Political Science.


28 February 2023

**Suggested citation:**

   J. Ruf, Empirical Finance with Equity Data (Ph.D. Course), LSE, 2023.
   
   
## Key words
CIZ; CRSP; STOCK & INDEXES; WRDS

## Introduction

The notebooks in this repository were developed for a Ph.D. course (taught in spring 2023 at the LSE) to explore the CRSP dataset, as provided by WRDS.

The course works with the updated file format (2.0, CIZ) introduced in July 2022 by CRSP.

The course starts with reviewing distributions and delistings before implementing some descriptive statistics on the US equity market and backtesting some simple trading strategies. The course also discusses some pitfalls of such empirical analyses (e.g., survivorship bias; data leakage; handling of stocks that default).

Comments and corrections are welcome.


## Updates

February 2024: Minor changes, including a short discussion concerning a data error in the table stocknames_v2 (see Notebook 2), provided  by WRDS.
(Update from WRDS: "What caused the issue for the date range you pointed out is the fact that Visa had SICCD code change from 7389 to 7374, and later on reverted back to 7389. As we used SICCD code as one of the grouping variables, it led to mistakenly include the period of SICCD = 7374 in the whole time range." -- WRDS will fix this issue.)