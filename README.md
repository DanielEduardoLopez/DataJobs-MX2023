<p align="center">
	<img src="Images/Header.png?raw=true" width=80% height=80%>
</p>

# Data Jobs Salaries in Mexico in February 2023
#### By Daniel Eduardo López

**28/02/2023**

**[LinkedIn](https://www.linkedin.com/in/daniel-eduardo-lopez)**

**[Github](https://github.com/DanielEduardoLopez)**

____
### **1. Introduction**
With the emergence of the big data, new jobs have appeared demanding new sets of skills and expertise for extracting value from data (Axis Talent, 2020):

- Business Analysts (BA)
- Data Analysts (DA)
- Data Architects (DR) 
- Data Engineers (DE) 
- Data Scientists (DS)

Which one is the most valued in the Mexican labor market currently?

____
### **2. General Objective**
To identify which data job category has the highest salary in the Mexican labor market in February 2023 according to the OCC website.
____
### **3. Research Question**
Which data job category has the highest salary in the Mexican labor market in February 2023 according to the OCC website?
____
### **4. Hypothesis**
The **Data Scientist** position has the highest salary in the Mexican labor market in February 2023 according to the OCC website.
____
### **5. Abridged Methodology**
The methodology of the present study is based on Rollin’s Foundational Methodology for Data Science (Rollins, 2015).

1) **Analytical approach**: Descriptive and inferential statistics.
2) **Data requirements**: Data about job positions such as job name, salary, employer and location.
3) **Data collection**: Data was collected from the OCC Website (Mexico) on 04 February 2022, through web scraping with Python 3 and its libraries Selenium and BeautifulSoup.
4) **Data exploration and preparation**: Data then was explored and cleaned with Python 3 and its libraries Pandas and Numpy. 
5) **Data analysis**: Data was analyzed with Python 3 and its libraries Pandas, Scipy and Statsmodels and visualized with Matplotlib, Seaborn, Folium and Plotly. 
6) **Statistical analysis**: The D'Agostino-Pearson normality test was used to assess the normality of the data jobs salary distribution. Then, both parametric (ANOVA and t-test with unequal variance) and non-parametric (Mann-Whitney U and Kruskal-Wallis H) tests were carried out to assess the significance of the obtained results.

Furthermore:

7) A **dashboard** was built with Python 3 and its libraries Plotly and Dash.
8) A **final report** was written with the complete results obtained from the data.
9) Some **slides** were prepared with the **most important insights** from the report.

___
### **6. Main Results**
Pending...


___
### **7. Dashboard**
Pending...


___
### **8. Conclusions**
Pending...

___
### **9. Partial Bibliography**
- **Axis Talent. (2020).** *The Ecosystem of Data Jobs - Making sense of the Data Job Market*. Retrieved from Axis Talent: https://www.axistalent.io/blog/the-ecosystem-of-data-jobs-making-sense-of-the-data-job-market
- **Rollins, J. B. (2015).** *Metodología Fundamental para la Ciencia de Datos*. Somers: IBM Corporation. Retrieved from https://www.ibm.com/downloads/cas/WKK9DX51

___
### **10. Description of Files in Repository**
File | Description 
--- | --- 
1_DataJobsMX2023_DataCollection.ipynb | Notebook with the Python code for collecting the required data from the OCC website through web scraping.
Dataset_Raw.csv | Raw data retrieved from the web scraping.
