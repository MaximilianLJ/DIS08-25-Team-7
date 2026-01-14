# DIS08-25-Team-7 - Group 7 - Data Modelling DIS08
## 1. Team
- Maximilian Leonard Jäger - 11333148
- Emirhan Hamit Eraslan - 11404231 

## 2. Project Topic
Migration and Public Opinion in Germany (2010 - 2024)  
This project examines how net migration to Germany developed between 2010 and 2024 and how public concern about migration changed during the same period. In addition, the project analyses whether there is an empirical relationship between actual migration levels, public concern and online attention to migration related topics.

## 3. Data Selection

### 3.1 Open Data Sources
- [Eurostat](https://ec.europa.eu/eurostat/databrowser/view/demo_gind__custom_19448125/default/table?lang=en) Annual data on net migration, population change and migration rates in Germany
- [Eurobarometer](https://europa.eu/eurobarometer/screen/home) Survey data on public attitudes and concerns, including the share of respondents who identify immigration as one of the two most important problems facing Germany.

### 3.2 Enrichment
- [Google Trends](https://trends.google.de/trends/) Search interest for migration-related terms such as *Migration* and *Flüchtlinge* (refugees), used as a proxy for online and media attention.


## 4. Research Question

RQ1: How has net migration to Germany developed between 2010 and 2024?
RQ2: How has public concern about migration in Germany changed in that time period?
RQ3: Is there an empirical relationship between migration levels and public concern? 
RQ4: How does online attention to migration related topcis relate to the concern? 

## 5. Tools used
- Jupyter Notebooks (Python & Markdown)
- Pandas, Matplotlib, Requests
- Git / GitHub

## 6. Folder Structure
```
DIS08-25-Team-7
├───data
│   ├───figures
│   ├───processed
│   └───raw
│       └───eurobarometer_pdfs
├───docs
└───notebooks
```

## 7. How to reproduce

This project is implemented as a Jupyter Notebook-based analysis pipeline.

### 7.1 Requirements 
- Python 3.9 or higher
- Jupyter Notebook or Lab
- Packages:
  - pandas
  - matplotlib
  - requests
  - scipy

### 7.2 Setup
1. Clone the repo
```bash
git clone https://github.com/MaximilianLJ/DIS08-25-Team-7
cd DIS08-25-Team-7
```
2. pip install pandas matplotlib requests scipy

### 7.3 Notebooks
- Use the Notebooks in /notebook to extract, clean and transform the data 
- alternatively get the finished dataset from /data/processed

#### 7.31 Do it yourself 
1. Run extraction.ipynb
2. Run the 2 cleaning notebooks google_t_transf_clean.ipynb & eurostat_transf_clean.ipynb
3. Either use my manually compiled .csv for Eurobarometer or get the Data yourself from the pdf files in /data/raw/eurobarometer_pdfs
4. Run merge_data.ipynb
5. Look at the interpretation and analysis in analysis.ipynb