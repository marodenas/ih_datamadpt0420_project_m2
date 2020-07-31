
# IRONHACK 
## Data Analysis Bootcamp - Project II - Data Visualization  
  
![Image](https://images.unsplash.com/photo-1520611084738-c4ad1e2e1903?ixlib=rb-1.2.1&auto=format&fit=crop&crop=entropy&w=1620&h=500&q=80)  

## Table of Contents  

* [About the Project](#about-the-project)  
  * [Challenge 1](#pushpin-challenge-1)  
  * [Challenge 3](#pushpin-challenge-2)  
  * [Challenge 2](#pushpin-challenge-3)      
  * [Built With](#hammer-built-with)  
* [Project Structure](#project-structure)  
  * [Prerequisites](#page_with_curl-prerequisites)  
  * [Inputs](#computer-inputs)  
  * [Folder Structure](#file_folder-folder-structure)  
 * [Procesing Stages](#procesing-stages)
	  * [Acquistion](#electric_plug-acquisition)  
	  * [Wrangling](#wrench-wrangling)  
	  * [Analysis](#rocket-analysis)  
	  * [Reporting](#mailbox-reporting)  
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
  

  ###  :hammer: Built With   
The core of the project is Python 3.7.3, but you have to install those libraries for run the analysis.   
- [Pandas (v.0.24.2)](https://pandas.pydata.org/pandas-docs/stable/reference/index.html)  
- [Numpy (v.1.18.1)](https://numpy.org/doc/stable/)  
- [Matplotlib(v.3.2.1)](https://matplotlib.org/)  
- [Seaborn(v.0.10.1)](https://seaborn.pydata.org/)  
- [Plotly(v.4.8.2)](https://plotly.com/)  

  
## **Project Structure**
###  **:page_with_curl:Prerequisites**  
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
  

## **Tableau Report**  
  
  If you want to see the final dashboard, click on this link to see it. 
[  Tableau Dashboard](https://public.tableau.com/profile/miguel.ngel.r.denas#!/vizhome/DiamondsDatasetExploration-Ironhack-Module2/Diamonsdataset)
  

 ---  
### ** Next stages**  

