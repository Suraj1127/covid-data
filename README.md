# COVID Notebooks

###### Work done by Nepal Poverty Team, The World Bank

COVID Notebooks are a series of notebooks which have been used for extracting, wrangling, and merging data related to COVID from different sources. The notebooks are a part of the work done by Nepal Poverty Team of the World Bank for creating COVID dashboard. These notebooks are well annotated so as to show Python's use (especially pandas) in data wrangling to Python newbies and to help others (programmers as well as non-programmers) follow the code. 

## Notebooks
### _01 Merging Data GCMR OWID OXCGRT WB.ipynb_
Jupyter notebook to merge COVID related data from Google, Oxford, Our World in Data and World Bank.
#### Data Sources:
1. [Google Community Mobility Reports](https://www.google.com/covid19/mobility/)
2. [The Oxford COVID-19 Government Response Tracker](https://www.bsg.ox.ac.uk/research/research-projects/coronavirus-government-response-tracker) 
3. [Our World in Data](https://ourworldindata.org/coronavirus) 
4. [World Bank's list of economies](https://datahelpdesk.worldbank.org/knowledgebase/articles/906519-world-bank-country-and-lending-groups)

### _02 Merging Nepal Data FB Google.ipynb_
Jupyter notebook for merging Facebook movement range maps, Google mobility data, and Oxford policy data for Nepal
#### Data Sources:
1. [Google Community Mobility Reports](https://www.google.com/covid19/mobility/)
2. [The Oxford COVID-19 Government Response Tracker](https://www.bsg.ox.ac.uk/research/research-projects/coronavirus-government-response-tracker) 
3. [Facebook Movement Range Maps](https://data.humdata.org/dataset/movement-range-maps) 

### _03 Nepal COVID Data Extraction and Aggregation.ipynb_
Jupyter notebook to extract COVID data for Nepal from an API and aggregate the data on the basis of date and admins (municipality, district, and province).
#### API:
1. [Nepal Coronavirus Information](https://nepalcorona.info/)

#### Nepal COVID
The exports for this notebook are saved in the Nepal COVID folder. 

### _04 Nepal Mobility Data and Google Trends.ipynb_
Jupyter notebook to compare and visualize trend of some COVID Google search phrases with Google mobility data

#### Data sources
1. [Google Trends](https://trends.google.com/trends/explore?geo=NP&q=corona%20death,nepal%20news,nepal%20weather,corona%20nepal)
2. [Google Community Mobility Reports](https://www.google.com/covid19/mobility/)

## Environment setup
Running of this notebook requires Jupyter software system. Either Jupyter notebook or Jupyter lab can be installed on the system. In addition, two additional Python packages -- like pycountry and pandas -- are required. The required packages are mentioned in each notebook. 

### Jupyter Software Installation
Please follow the below link for installation of Jupyter software.
https://jupyter.org/install

### Example Python package installation
#### pycountry Package Installation
https://pypi.org/project/pycountry/

After all the dependencies are installed the notebook can be imported to the Jupyter software and run. More information about dependencies and required packages is given in respective notebook.

