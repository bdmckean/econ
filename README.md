econ
====

## Analysis of Chinese economy.
I have the question: is China about to suffer a lost decade like
Japan suffered in the 1990's.

I will look at three areas:
1. Population:
  * total population
  * percent of population that is working age
2. GDP
  * total GDP
  * per person GDP
3. Debt

### Anaconda Environment
to setup conda emnvironment for project:  
conda env create -f environment.yaml

### Project organization
####data/ - directory of data files, not in github -- data created by code
####population/ - code for generating population data
1. download and process UN dtaa
2. download and process FRED data
3. generate combined historical and predictions for population 

