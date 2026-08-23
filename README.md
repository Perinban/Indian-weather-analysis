# India Weather ML Analysis

This project analyzes Indian weather observations to study regional differences and relationships among temperature, humidity, wind, pressure, and air-quality indicators. The work combines data preparation, relational database design, statistical testing, machine learning, and Tableau visualization so the same source data can be examined from both analytical and reporting perspectives.

## What the project does

1. Prepare and validate the source weather dataset.
2. Normalize the data and define the relational database structure used by the project.
3. Load analysis-ready records into database tables.
4. Explore regional and variable-level weather patterns.
5. Test relationships such as temperature vs. humidity, wind speed vs. gusts, and pressure-related patterns.
6. Apply machine-learning models to selected analysis questions.
7. Present the results through charts and Tableau visualizations.

## Methods and technologies

- Python and Jupyter Notebook
- Pandas
- SciPy
- scikit-learn
- XGBoost
- Random Forest
- K-Nearest Neighbors
- Linear regression
- Pearson correlation and t-tests
- Matplotlib and Seaborn
- Oracle Database and SQLAlchemy
- Tableau

## Project resources

These are the original supporting files used by the project.

| Resource | Description | Link |
| --- | --- | --- |
| `IndianWeatherRepository.csv` | Source weather data used in the analysis. | [Open file](https://drive.google.com/file/d/1WU2gaQcZGCR9-GhW-aVLsW1OvDTTZ2PO/view?usp=sharing) |
| `Database Setup.docx` | Database configuration and setup details used for the project. | [Open document](https://docs.google.com/document/d/1FJYrRqlW07cPM0plBZPTvYztKKLE3ajl/edit?usp=sharing&ouid=114840663789662506255&rtpof=true&sd=true) |
| Entity Relationship Model | ER diagram for the normalized weather database structure. | [Open DrawSQL diagram](https://drawsql.app/teams/de-28/diagrams/regional-weather) |
| Tableau visualization | EDA visualizations created from the prepared weather data. | [Open Tableau dashboard](https://public.tableau.com/app/profile/perinban.parameshwaran/viz/EDAAnalysisonIndianWeather/Myth1) |
| `Normalization Table Details.xlsx` | Table and normalization details used to transform the source data into the relational model. | [Open workbook](https://docs.google.com/spreadsheets/d/1LmDfrxFcBLyQZUiiYTFK6aFexb3S06VZ/edit?usp=sharing&ouid=114840663789662506255&rtpof=true&sd=true) |

## Repository contents

```text
.
├── Source Code.ipynb     # Cleaning, statistical analysis, ML, and visualization workflow
├── Database Tables.sql   # Relational table definitions
├── media/                # Project figures and report assets
└── README.md
```

## Run the project

Install the notebook dependencies, configure the source-data path and database connection values used by the relevant cells, and run:

```bash
jupyter notebook "Source Code.ipynb"
```

The external resources above provide the source data, database setup information, normalization details, ER model, and Tableau output used alongside the notebook.
