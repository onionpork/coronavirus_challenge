# coronavirus_challenge

## My github repo link:-
https://github.com/onionpork/coronavirus_challenge


## Introduction
For this challenge, datasets in Kaggle 'Novel Corona Virus 2019 Dataset' were used. Only data produced in USA has been utilitzed to complete this challenge, COVID-19 observations in other regions were not included in this challenge. 

Add: Find accessible datasets in Johns Hopkins github Repo link:-
https://github.com/CSSEGISandData/COVID-19

## Libraries used
- numpy
- pandas
- searborn
- matplotlib.pylot
- sklearn
- plotly
- dash
- scripy


## Files included
- Two spreadsheet have been used in this small project, which are stored in 'data' folder
- Output figures are saved in folder 'Figure'
- Three complete jupypter notebooks:  
      - DRAFT__draft_coronavirus_challenge.ipynb
      - covid19_draft_data_visual.ipynb
      - covid19_draft_data_SIR.ipynb
- One incomplete jupypter notebook
      - covid19_draft_model.ipynb

## Process involved
The process starts with business understanding. 
1. Posing Question - Details please see in my medium post
2. Preparing data - from Kaggle coronavirus challenge, in which there are five infos.  
    - date
    - states(location)
    - confirmed case
    - death case
    - population size in each location
3. Data processing - data wrangling, and putting into good shape.
4. Analysing Modelling and Visualizing
5. Evaluation- TBD. Since the COVID-19 crsis is still happening, I would update it monthly.  

## Conclusion
1. It's not saft to conclude that we are off-peak. 
2. Nearby states should stay together since the strong correlation between near states.
3. Population size does not influences the spread.
4. Our ability to have enough kits to test coronavirus is under doubt.  
5. The simulated recovery rate is arounf 0 based on SIR model, which may indicate we are still in the spreading phase

