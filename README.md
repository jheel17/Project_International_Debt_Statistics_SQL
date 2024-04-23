# Introduction:

![image](image-1.png)

In this project, I delved into the International Debt dataset, exploring the multifaceted financial obligations that countries across the globe manage. This investigation took me  through various aspects of debt, from the kinds of financial instruments in play to the magnitudes of debts that countries contend with. The objective was to glean a comprehensive understanding of how debt is distributed internationally, which countries shoulder the heaviest burdens, and where financial reforms or aid may be most urgently needed.

# Dataset:

The dataset for this project comes from The World Bank’s international debt statistics,[The World Bank](https://www.worldbank.org/en/home) which catalogs the financial liabilities of countries across various categories. The data captures a comprehensive array of indicators related to debt, detailing the obligations countries have incurred. Structured in a relational format, the dataset is apt for performing robust analysis to dissect the complexities of global debt.

The following table schema provides an overview of the debt_indicators table within the database, which is central to the analysis:

| Column         | Definition                               | Data Type |
|----------------|------------------------------------------|-----------|
| country_name   | Name of the country                      | varchar   |
| country_code   | Code representing the country            | varchar   |
| indicator_name | Description of the debt indicator        | varchar   |
| indicator_code | Code representing the debt indicator     | varchar   |
| debt           | Value of the debt indicator (in current US dollars) | float     |


# Project Objective:

The core aim of the project is to uncover insights into the international debt structure by examining the data collected by The World Bank. 

- I seek to identify which countries have the most complex array of debt instruments.

- The types of debt that are most prevalent.

- The magnitudes of the largest debts incurred.

 By doing so, I aimed to contribute to a better understanding of global financial health.


# Tools Used:

- In this project, I employed SQL for data querying and analysis, with PostgreSQL serving as the backbone for database and table creation. 

- Python was the language of choice for visualization and further analysis within a Jupyter Notebook environment, where pandas facilitated data manipulation, and matplotlib was instrumental in creating clear, informative graphs. 

- Psycopg2 provided the bridge between the Jupyter Notebook and the PostgreSQL database, enabling seamless integration and interaction. 

- Additionally, GitHub was used as a platform to host and launch the project, providing a space for version control, collaboration.


