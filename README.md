# gc_budget

## Motivation
Have you ever worked on a multi-year grant application and had to calculate the amount spent on a salary by FTE adjusted by inflation? How about factoring in the amount that should be spent on benefits?

This jupyter notebook provides functions that allow you to do the following:
- calculate number of FTEs over the course of a multi-year project from a given total budget, assuming that the FTEs are equally distributed each year (assumes a given inflation that is compounded annually)
- calculate the total salary for a position over the course of a multi-year project given a budget for the salary and the number of FTEs (assuming FTEs are equally distributed each year, assuming a given inflation rate that compounds annually)
- calculate a position's annual base salary given total annual salary and a benefit rate

Hopefully this is useful and takes some of the guess-work out of preparing budgets.

## Required Libraries
None

## Files
- `README.md` - This file
- `LICENSE.md` - Legal information
- `salary_calculations.ipynb` - jupyter notebook that contains functions to perform the calculations described above