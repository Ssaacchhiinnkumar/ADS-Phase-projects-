# ADS_PHASE-Projects 

#importing the necessary python libraries and the dataset
import numpy as np 
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
data=pd.read_csv("country_vaccinationh")
data.head()

#data country and value counts
data.count.value_counts()

#Describe the data
data.describe()

#pre process they data
df=data[["vaccines","country"]]
df.head()

#prepare the data
dict={}
for I in df.vaccines.unique():
dict[i][df["country"][j] for j in df[df["vaccines"]==i].index]
vaccines={}
for key, value in dict.items():
vaccines[key]=set9value0
print(vaccines)

#visualize what combination of vaccines every country is using
import plotly.express as px
import plotly.offline as py
v_map=px.choropleth(data, location='iso_code',color='vaccines')
v_map.update_layout(height=100)
v_map.show()

#data of country and value counts
data.country.value_counts()

#data of vaccines and value counts
data.vaccines.value_counts()

#data of vaccines used in country
df=data[["vaccines","country"]]
df.head()

#line plot graph for country and value counts
plt.plot(data.country.value_counts())

#data of country and date with daily vaccination
df=data[["country","date","daily_vaccination"]]
df.head()

#data of source name qand source website
df=data[["source_name","source_website"]]
df.head()

pie chart statistical analysis
df=data[["source_name","source_website","total_vaccination"]
df.head()

#import p
