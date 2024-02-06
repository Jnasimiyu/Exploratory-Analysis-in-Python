import pandas as pd
import numpy as np
from datetime import datetime
import seaborn as sns
import matplotlib.pyplot as plt
#importing  dataset
population=pd.read_csv('Global population Trends.csv')
# Display of the first 5 Rows of the dataset
population.head()
Country	Year	Total Population	Urban Population	Rural Population	Population Density	Life Expectancy	Birth Rate	Death Rate	Fertility Rate	Infant Mortality Rate	Growth Rate
0	Afghanistan	2017	-	-	-	55	63.0	37.342	7.027	5.129	49.4	-
1	Afghanistan	2018	36,686,784	9,353,296	27,333,488	56	63.0	36.927	6.981	5.002	47.8	3.0
2	Afghanistan	2019	37,769,499	9,727,157	28,042,342	58	64.0	36.466	6.791	4.87	46.3	3.0
3	Afghanistan	2020	38,972,230	10,142,913	28,829,317	60	63.0	36.051	7.113	4.75	44.8	3.0
4	Afghanistan	2021	40,099,462	10,551,772	29,547,690	-	62.0	35.842	7.344	4.643	43.4	3.0
type(population)
