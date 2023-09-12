# Data Visualization and Presentation

## Overview 

<a href="https://en.wikipedia.org/wiki/Karamoja">Karamoja</a> is the most food-insecure region of Uganda. One of the main reasons is the low productivity level of the crops due to intense droughts as well as pest and disease outbreaks.

In Karamoja, several NGOs provide technical support as well as farm inputs to the farmers experiencing extremely low yield. Though, they lack visibility into the overall state of the region and often need to rely on some very local sources of information to prioritize their activities.

_Dalberg Data Insights_ (DDI) has been requested to develop a new food security monitoring tool to support the decision making of one of those NGOs active in Karamoja.

To do so, Dalberg Data Insights developed a methodology to remotely measure the yield of the two main staple crops of the region (i.e. sorghum and maize) based on satellite images. The agri-tech team just ran the model for the 2017 crop season.

## Research Question

As a _Data Scientist_, the agri-tech team is asking you to develop an interactive visualization tool of the results for this first crop season. This visualization tool that you will develop will be used as a first mockup of the Food Security Monitoring tool that DDI will develop for the NGO.

Based on your experience, the team expects you to come up with a first draft within the coming 3 working days. They give you carte blanche in terms of structure and functionalities but they know that the client wants:

* At least a map in the dashboard
* The possibility of visualizing the results by district or sub-county (two administrative levels used by the NGO)

## Dataset Files 

Data Source <a href="https://archive.org/download/data_20190829/DATA.zip">[Link]</a>

### 1. Shapefiles

* Boundaries of Uganda Subcounties 
* Boundaries of Uganda Districts 
* Crop Type Map for Sorghum (i.e. position of the Sorghum fields)
* Crop Type Map for Maize

### 2. Tables
#### Yield and Population per Subcounty
| Column       | Description                                            |
| ------------- | ------------------------------------------------------ |
| POP           | Total population for the sub-county                     |
| S_Yield_Ha    | Average yield for sorghum for the sub-county (Kg/Ha)    |
| M_Yield_Ha    | Average yield for maize for the sub-county (Kg/Ha)      |
| Crop_Area_Ha  | Total crop area for the sub-county (Ha)                |
| S_Area_Ha     | Total sorghum crop area for the sub-county (Ha)         |
| M_Area_Ha     | Total maize crop area for the sub-county (Ha)           |
| S_Prod_Tot    | Total productivity for sorghum for the sub-county (Kg)  |
| M_Prod_Tot    | Total productivity for maize for the sub-county (Kg)    |
  #### Yield and Population per District 

