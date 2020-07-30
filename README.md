# IRONHACK 
## Data Analysis Bootcamp - Project II - Data Visualization  
  
![Image](https://images.unsplash.com/photo-1520611084738-c4ad1e2e1903?ixlib=rb-1.2.1&auto=format&fit=crop&crop=entropy&w=1620&h=500&q=80)  

## Table of Contents  

* [About the Project](#about-the-project)  
  * [Challenge 1](#pushpin-challenge-1)  
  * [Challenge 3](#pushpin-challenge-2)  
  * [Challenge 2](#pushpin-challenge-3)      
  * [Built With](#hammer-built-with)  
* [How to use the pipeline](#how-to-use-the-pipeline)  
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

  
###  :pushpin: Challenge 1  
  

  
###  :pushpin: Challenge 2  
  

  
  
###  :pushpin: Challenge 3  
  

  ###  :hammer: Built With   
The core of the project is Python 3.7.3, but you have to install those libraries for run the script.   
Native packages:  
- [Argparse](https://docs.python.org/3.7/library/argparse.html)  
- [Configparser](https://docs.python.org/3/library/configparser.html)  
- [Datetime](https://docs.python.org/2/library/datetime.html)  
- [Re](https://docs.python.org/3/library/re.html)  
- [Smtplib](https://docs.python.org/3/library/smtplib.html)  
- [Email](https://docs.python.org/3/library/email.examples.html)  
  
Furthermore, it is has to be installed the following libraries:  
- [SQL Alchemy (v.1.3.17)](https://docs.sqlalchemy.org/en/13/intro.html)  
- [Pandas (v.0.24.2)](https://pandas.pydata.org/pandas-docs/stable/reference/index.html)  
- [Numpy (v.1.18.1)](https://numpy.org/doc/stable/)  
- [Requests (v.2.23.0)](https://requests.readthedocs.io/)  
- [Beautiful Soup (v.4.9.1)](https://www.crummy.com/software/BeautifulSoup/bs4/doc/)  
- [Pysftp (0.2.9) ](https://pypi.org/project/pysftp/)  

  
## **How to use the pipeline**
###  **:page_with_curl:Prerequisites**  
Please, install all the libraries mentinoned in [Built With](#built-with) in your enviroment in order to run the script.  
   


  
### **:computer: Inputs**  

It is mandatory to connect those sources with the pipeline in order to get the expected results. 

- [Data base](/data/raw/raw_data_project_m1.db ) SQLAlchemy.  
- Data base procesed with Pandas  
- Job titles  [API](http://dataatwork.org/data/) with request.  
- Country codes [EuroStat](https://ec.europa.eu/eurostat/statistics-explained/index.php/Glossary:Country_codes) with request and beautifulsoup  
  
  
  
### :file_folder: **Folder structure**  
```
└── ih_datamadpt0420_project_m1  
    ├── __trash__  
  ├── .gitignore  
    ├── .env  
    ├── requeriments.txt  
    ├── README.md  
    ├── main_script.py  
    ├── config.ini  
    ├── notebooks  
    │   ├── notebook1.ipynb  
    │   └── notebook2.ipynb  
    ├── p_acquisition  
    │   ├── __init__.py  
    │   └── m_acquisition.py  
    ├── p_analysis  
    │   ├── __init__.py  
    │   └── m_analysis.py  
    ├── p_reporting  
    │   ├── __init__.py  
    │   └── m_reporting.py  
    ├── p_wrangling  
    │   ├── __init__.py  
    │   └── m_wrangling.py  
    └── data  
        ├── html  
        ├── raw  
        └── results  
```  
  

## **Processing stages**  
  
### **:electric_plug: Acquisition**  
  

 ---  
### ** Next stages**  
- Multiprocessing connection. 
- Object Oriented Programing data pipeline.
