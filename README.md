

# IRONHACK 
## Data Analysis Bootcamp - Project II - Data Visualization  
  
![Image](https://images.unsplash.com/photo-1520611084738-c4ad1e2e1903?ixlib=rb-1.2.1&auto=format&fit=crop&crop=entropy&w=1620&h=500&q=80)  

## Table of Contents  

* [About the Project](#about-the-project)  
  * [Challenge 1](#pushpin-challenge-1)  
  * [Challenge 2](#pushpin-challenge-2)  
  * [Built With](#hammer-built-with)  
* [Project Structure](#project-structure)  
  * [Dataset Analysis](#page_with_curl-dataset-analysis)  
  * [Tableau Report](#tableau-report)  
* [Next Stages](#next-stages) 
  
## About the project  
  
The aim of this repository is to show the adquire skills throught Module 1 of Data Analytics in IronHack's Bootcamp [PT2020]  


  
###  :pushpin:  **Challenge 1: Exploratory Data Visualization Charts and Summary Statistics**

The goal of this challenge is to build an **exploratory data analysis report** in order to gain initial insight on our diamonds dataset. Your notebook must include:

-   Summary statistics including descriptive statistics (max, min, mean, standard deviation, percentiles, correlations, etc.) and data types (integer, float, boolean, string, etc.).
-   Data visualizations charts in order to capture a large amount of data all at once in a clear and concise manner (Box Plots, Histograms, Bar Plots, Scatter Plots, Correlation Matrix, etc.).
  
###  :pushpin: Challenge 2  Tableau Data Dashboard
  
Dashboards are powerful tools for communicating important information **at-a-glance**. The goal of this challenge is to build a data dashboard using our diamonds dataset that will help the final user
  
 Instead, a data dashboard should be **a single interactive interface built around a specific objetive and which components are logically arranged in order to provide data relevant insights effectively**.

### :pushpin:  Bonus Challenge: Hypothesis Testing

- Test 1 
One sample vs constant hypothesis test. We know from the available literature that diamonds average price rounds about 4000 USD. The aim is to test whether the prices in our sample are significantly different from the literature value. Give some conclusions about the implications of your test results.

- Test 2 
Two independent samples. Our sample includes diamonds with different features (carat, cut, color clarity, etc.). It seems clear that the carat plays an important role in price. However, it's not that clear whether the prices of some "sub-groups" are significantly different from each other. These are the "sub-groups" that you might feel suspicious about it:

    Sub-Test 1: Fair cut + color G vs. Fair cut + color I
    Sub-Test 2: Good cut + color E vs. Good cut + color F
    Sub-Test 3: Ideal cut + color D vs. Ideal cut + color E
    Sub-Test 4: Premium cut + color D vs. Premium cut + color E
    Sub-Test 5: Very Good cut + color I vs. Very Good cut + color J
    Sub-Test 6: All cuts + color D vs. All cuts + color E


 ###  :hammer: Built With   
The core of the project is Python 3.7.3, but you have to install those libraries for run the analysis.   
- [Pandas (v.0.24.2)](https://pandas.pydata.org/pandas-docs/stable/reference/index.html)  
- [Numpy (v.1.18.1)](https://numpy.org/doc/stable/)  
- [Matplotlib(v.3.2.1)](https://matplotlib.org/)  
- [Seaborn(v.0.10.1)](https://seaborn.pydata.org/)  
- [Plotly(v.4.8.2)](https://plotly.com/)  

  
## **Project Structure**
###  **:page_with_curl:Dataset Analysis**  
The following structure has been followed to analyzed all the dataset. 

```
## Index
- **Libraries used**
- **Dataset Exploration**
    - Shape
    - Data types and null values
- **Basic Statistics of diamons' dataframe**
- **Diamons' dataframe operations**
    - Missing Data
    - Weird data
    - Duplicated data
- **Analysis by type of data**
    - Quantitative data
        - Cut
        - Color 
        - Clarity
    - Qualitative data
        - Carat
        - Price
        - Table
        - Depth
        - Size (x,y,z)
- **How previous columns are performing together**    
    - Correlation
    - Contingency table
    - Cramer's V
    - Custom Rapaport table
- **Conclusions**
- **Export data filtered**
- **Hypothesis testing**

```

If you want to see online, you could view the entire analysis throught this link. [Project Analysis](https://marodenas.es/ironhackm2/)
   


  
  
  
  
### :file_folder: **Folder structure**  
```
└── ih_datamadpt0420_project_m2  
    ├── __trash__  
    ├── .gitignore  
    ├── README.md  
    ├── notebooks  
    │   ├── data_analysis_report.ipynb  
    ├── data_analysis_html  
    │   ├── data_analysis_report.py  
    └── data  
        ├── raw  
        └── results  
```  
  

### **Tableau Report**  
  
  If you want to see the final dashboard, click on this link to see it. 
[  Tableau Dashboard](https://public.tableau.com/profile/miguel.ngel.r.denas#!/vizhome/DiamondsDatasetExploration-Ironhack-Module2/Diamonsdataset)
  

 ---  
### ** Next stages**  

- Update notebook with deeper analysis per group. 