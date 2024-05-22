# ProgrammingLanguageTrends
 Exploratory analysis of Kaggle dataset on programming languages.

Original data found at: https://www.kaggle.com/datasets/nextmillionaire/programming-languages-trend-over-time/code

## Folder Structure
- data
  - archive.zip (contains zipped csv of data which should be renamed to data.csv in the data folder)
  - data.csv 
    - Week: Object type with date data in month/day/year format
    - Python/Java/C++: Cols with search count of that language for each week
- imgs
  - folder with images created throughout analysis
  - img paths are used in this readme, so moving or renaming them may break links
- notebooks
  - collection of jupyter notebooks, each of which is designed to run along
  - InitialEDA.ipynb
    - ingest data
    - run skimpy analysis
    - show basic summary descriptive stats
  - PropheModels.ipynb 
    - ingest data
    - use Meta's [Prophet](https://facebook.github.io/prophet/) model to:
      - visualize data and trends
      - forecast data to predict next time points
- LICENSE
  - MIT license for usage
- README.md
  - This file with project details, results, and summary information
    
## Data Summary

Data summary generated by [Skimpy](https://pypi.org/project/skimpy/) package `skim` function summarizing data after initial processing from `notebooks/InitialEDA.ipynb`. 

![Data Summary](imgs/data_summary.svg)


#### To-do Items
- Add all figures
- Expalin sliders for plotly
- Table of metrics
- Environment file(s)
