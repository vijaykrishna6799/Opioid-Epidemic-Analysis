# PROJECT (Data Science)
***
## U.S. Opioid Epidemic Analysis


This is a repository where the analysis for the Opioid Epidemic in United States is performed. This work is to fulfill the requirements for the DATA SCIENCE course (CSC-605) for the Fall semester (Fall 2022) at UNCG.
Main aim is to collect the data from different datasets such as Drug Overdose Dataset, County Health Rankings, County Opioid Dispensing Rates and understand and visualize them with the help of Data Science techniques to estimate the impact of Opioid Epidemic across different socio-economic, demographic, geographic variables that are present for the counties in US and to give future predictions.

![opioid](https://www.hhs.gov/opioids/sites/default/files/inline-images/opioids-infographic.png)

## Structure of this repository
***
|-- README.md                       # the README file of this repo π 

|-- data                            # the datasets used in this repository π

|-- docs                            # documentation of the project reports and presentationsπ

|-- images                          # All the images/plots/graphs generated are found here ππ

|-- src                             # the code and notebooks! ππ




## Software used (open source):
***
+ [python](https://www.python.org/download/releases/3.0/)
+ [NumPy](https://numpy.org/)
+ [pandas](https://pandas.pydata.org/)
+ [plotly](https://plotly.com/)
+ [Jupyter Notebook](https://jupyter.org/)
+ [Seaborn](https://seaborn.pydata.org/)
+ [Scipy](https://scipy.org/)
+ [jupyter_dash](https://dash.plotly.com/workspaces/using-dash-in-jupyter-and-workspaces)


## Stage I - Data Understanding and Linking.
***
In this stage we acquire different datasets. The below links can be used to download these datasets.

+ [Drug Overdose Dataset](https://wonder.cdc.gov/ucd-icd10.html)
+ [County Health Rankings](https://www.countyhealthrankings.org/)
+ [County Opioid Dispensing Rates](https://www.cdc.gov/drugoverdose/maps/rxcounty2019.html)

#### Opioid overdose dataset linking - tasks performed:
- In stage 1, we link different datasets available to obtain a super dataframe which can be used for further analysis.
- Analyse the different variables present in the data and formulate a data dictionary.
- Identifying issues with the data.
_ Identifying the top counties and states with highest opioid mortality rates.

## Stage II - Data Modeling.
***
In this stage we develop the data for modelling and comparitive analysis. Here we are analysing county based information for different states in the US.
- Dataset used in this stage is [opioid  related mortality from 1999-2019](https://wonder.cdc.gov/wonder/help/ucd.html#Drug/Alcohol%20Induced%20Causes)

#### Tasks Performed:
- In this stage we are graphically comparing how different states are doing with respect to opioid mortality rate.
- Histogram plot with mean and median of Normalized Deaths for entire US as a distribution.
- Adding a label column by performing a quantile distribution of the Normalized Deaths.
- Plotting the variables identified in stage1 (Scatter Plot). Developing an interactive method to display all the variables in Plotly widget for jupyter.[Plotly Widget](https://plotly.com/python/figurewidget-app/)
- Calculating the mean opioid mortality for states and US per year. Identifying the peaks in the data.
- Identifying the relation between mortality and population of a state.


## Stage III - Distributions and Hypothesis Testing.
***
#### Task1: Distribution Analysis:
- In this we perform Opioid Mortality data analysis by using the Distribution Analysis
- Distribution Analysis is done by Distribution Estimators- Method of Moments (MoM), Maximum Likelihood Estimator (MLE) and Kernel Density Estimation (KDE).
#### Task2: Hypothesis Testing and Regression:
- We perform Hypothesis test on some important variables of the merded super dataframe and analyse the effect of various parameters on the number of deaths related to drug overdose. 
- Performing Linear, Multi-linear and non-linear regression to estimate the effect of number of deaths over time based on Opioid prescription rates.

## Stage IV - Dashboard.
***
Developing a simple interactive dashboard. Utilizing [plotly](https://plotly.com/) along with the [Dash](https://plotly.com/dash/) as a framework.

- From the super dataframe we build a comparision between each variable to the drug overdose death rate and also evaluate the behaviour by plotting linear/non-linear trend line.

- the interactive dashboard contains a Data Table and a map as well, Along with selectors to display the linear and log values of the variables.

- Created a map (chloropleth) to display the selected variable.
### Project Setup:
***
1. Clone the repository - Clone the repository by pasting this [link](https://github.com/vijaykrishna6799/Opioid-Epidemic-Analysis) in your favorite terminal.
2. Make sure you have the above used Software in your local machine.
3. Some additional python packages required to run the code properly can be installed by running the following code.



- All the project Questionaire is in the Stages Folder (ipython notebooks)



