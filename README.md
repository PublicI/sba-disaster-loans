# SBA Disaster Loans Data Analysis

For the story ["New data reveals why 800,000 applicants were denied federal disaster assistance loans"](https://publicintegrity.org/environment/new-data-reveals-why-800,000-applicants-were-denied-federal-disaster-assistance-loans/)

## Who did this?

This is an analysis from the Center for Public Integrity's environment and workers' rights team. It was created by data journalist Zach Goldstein. Environment reporter Rachel Leven provided FOIA assistance and general guidance. Research editor Peter Smith helped with FOIA requesting and fact-checking. The story was edited by environment editor Jamie Smith Hopkins and data-checked by data editor Chris Zubak-Skees. 

## What's here?

- Data - Datasets obtained via a Freedom of Information Act (FOIA) request to the U.S. Small Business Administration (SBA). These have been converted to .gz files, with separate files for [approvals](https://github.com/PublicI/sba-disaster-loans/blob/master/sba_disaster_loan_approvals.csv.gz), [withdrawals](https://github.com/PublicI/sba-disaster-loans/blob/master/sba_disaster_loan_withdrawals.csv.gz), and [declines](https://github.com/PublicI/sba-disaster-loans/blob/master/sba_disaster_loan_declines.csv.gz).
- [Analysis](https://github.com/PublicI/sba-disaster-loans/blob/master/SBA%20Data%20Analysis.ipynb) - An analysis of SBA disaster assistance loan approvals, withdrawals, and declines from fiscal year 2001-2018.
- [Data dictionary](https://github.com/PublicI/sba-disaster-loans/blob/master/sba_disaster_loan_codes.csv) - A data dictionary listing what the decline/withdrawal codes used in the data mean.

## Why did we do this?

Climate change is increasing the risk of more frequent and severe natural disasters. That means it's more important than ever to understand the federal disaster relief programs meant to help people recover from those disasters. So we wanted to shine a light on how the SBA's disaster loan program works, who it helps, who is left behind and why.

## How did we do it?

We used Python, Pandas, and Jupyter Notebook to analyze the data. Exploratory graphics were created with matplotlib, but the final graphics used for the story were created in JavaScript and the code for them is not included in this GitHub repository. 

## Contact information

- Email - zpgoldstein@gmail.com
- Twitter - @PublicIntegrity, @zpgoldstein
