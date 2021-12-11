# VaxPredictor
### Group Members
- Alex Liang
- Xing Yang
- Edgar Pineda

### Repository Structure
List each file and what it's purpose it. Make sure you indicate where your data cleaning code and data dictionary are! 

### Runing the Code - All Python file can be open in Google colab, jupyter notebook or Visual Studio Code
With Vs Code
1. Press F1 to display the command palette. At the command palette prompt, enter gitcl, select the Git: Clone command, and press Enter.

2. Execute 'git clone' command with the path to the repository you would like to clone in the integrated terminal.
  ```
  git clone https://github.com/edgarp2017/VaxPredictor.git  This clones the repo
  ```


For example:
- `data`
  - `continents2.csv`: data related to the continents and subcontinents which are the regions and subregions of the country
  - `country_vaccinations.csv`: data related to the daily and total vaccination and vaccines used in each country
  - `country_vaccinations.csv`: data related to the daily and total vaccination and vaccines used in each country
  - `population_by_country_2020.csv`: data related to the population of each country in year of 2020
  - `cleaned.csv`: The cleaned and combined dataset for modeling. 
  - `data_dictionary.csv`: The data dictionary for cleaned. 

- `code` This will change the Data.csv file do not run this code
  - `etl_continents2.ipynb`: Cleans `continents2.csv`
  - `etl_country_vaccinations.ipynb`: Cleans `country_vaccinations.csv`
  - `etl_country_vaccinations_by_manufacturer.ipynb`: Cleans `country_vaccinations_by_manufacturer.csv` and charts. 
  - `models.ipynb`: Builds Regression models. 

- `visualization `
  - `vax_map.ipynb` : 3-D visual map for vax per country
  - `daily_vax_graph.ipynb` : Line graph for vaccinationed per day for all country(file too big hard to load)
  - `covid_vax_bar_graph.ipynb` : Bar Charts 
  - `pie_chart_for_manufacturer.ipynb` : Pie chart for vax used for selected Country
  - `vacci_percentage.ipynb` : Choropleth Map that show % vaccinated
  - `main.app.ipynb` : Combination of all Sunburst charts, Choropleth Map, Bar Charts, Pie Charts, and Treemap.

### Contributions
Describe the contributions that each group member made.
- Alex Liang - `etl_population_by_country_2020.ipynb` and `preliminary_analysis.ipynb` and `models.ipynb`
- Xing Yang - `etl_country_vaccinations_by_manufacturer.ipynb`
- Edgar Pineda `etl_continents2.ipynb` and `etl_country_vaccinations.ipynb`and `cleaned.csv` and `data_dictonary.csv` and `models.ipynb`
Everyone was able to help out with the visualization. 