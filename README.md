# San Francisco Real Estate Investment 

---

![SanFran](Images/san-francisco-hero.jpg)

## Background

Skyler's company has just started a new Real Estate Investment division to provide customers with a broader range of portfolio options. Skyler was tasked with building a prototype dashboard, and she needed my help. The real estate team wants to trial this initial offering with investment opportunities for the San Francisco market. If the new service is popular, then they can start to expand to other markets.


---

Link to [Dashboard Code](https://github.com/onyxcollc/SanFrancisco_Real_Estate_Investment/blob/main/dashboard.ipynb)

Link to [Rental Analysis Code](https://github.com/onyxcollc/SanFrancisco_Real_Estate_Investment/blob/main/rental_analysis.ipynb)



To complete this task, you would first need to create an environment with all the proper imports.

Make sure if there are any updates needed, you should do so.

Keep in mind the data used was from 2010-2016 "sfo_neighborhoods_census_data.csv" & "neighborhoods_coordinates.csv".

```
import os
import pandas as pd
import matplotlib.pyplot as plt
import plotly.express as px
import hvplot.pandas
from pathlib import Path
from dotenv import load_dotenv

pn.extension('plotly')
%matplotlib inline

```

Some of the analysis completed:

#### Yearly Market Analysis
* Find the number of housing units sold per year.
* The average gross rent in San Fran. 
* The average sales price in San Fran.

#### Neighborhood Analysis
* San Fran sales per square foot per year.
* Top 10 Expensive Neighborhoods.

#### Parallel Plots Analysis


---

## Dashboard DEMO


![dashboard-demo.gif](Images/dashboard-demo.gif)

---

### Created By

__Nicholas Olumese__, Profile: [LinkedIn](https://www.linkedin.com/in/nicholas-olumese/)


