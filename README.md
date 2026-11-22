# Portfolio Projects

Data analysis projects in Python and Jupyter: cleaning messy data, exploring it with charts, and building simple regression models to answer a question.

I'm a product manager who uses side projects to keep my data skills sharp. Each project starts with a question, works through the data, and ends with what I found and what I'd look at next.

## Projects

| Project | Question | Methods | What I found |
| --- | --- | --- | --- |
| [US Medical Insurance Costs](Portfolio_US_Medical_Insurance_Costs/Portfolio%20Project%20-%20US%20Medical%20Insurance.ipynb) | What drives yearly medical insurance charges? | Correlation, scatter plots, linear regression | Smoking is the biggest driver: about $23,650 more a year, all else equal. The model explains about 78% of the variation in charges. |
| [Life Expectancy and GDP](Life-Expectancy-and-GDP/life_expectancy_gdp.ipynb) | Does GDP track life expectancy across six countries from 2000 to 2015? | Summary stats, per-country regression, Pearson correlation | GDP and life expectancy rose together in every country, with correlations of 0.91 to 0.98. |
| [Stack Overflow Developer Survey](StackOverflow_Client_Project/stack_overflow_dataset_cleaning_project.ipynb) | For a staffing-agency client: what developers are out there, and what do they earn? | Missing-data analysis, deletion, backfill and iterative imputation | Most respondents work full time, and computer science is the most common major, though its share fell over the survey years. Pay is charted against years of experience after filling in missing values. |
| [Yelp Rating Predictor](Yelp%20Regression%20Workbook%20Project/yelp_regression.ipynb) | Which restaurant features predict a Yelp rating? | Merging six datasets, feature selection, linear regression | Review sentiment does most of the work: alone it explains about 61% of the variation in ratings, and all features together about 68%. |
| [US Census Cleaning](US_census_cleaning_practice/Cleaning%20US%20Census%20Data.ipynb) | Can scattered census files be turned into clean, chartable data? | Combining files, text cleanup, type conversion, histograms | Ten raw files combined into one table, cleaned and charted by income, gender and race. |

## Tools

Python, pandas, NumPy, matplotlib, seaborn, scikit-learn, SciPy, Jupyter.

## Running the notebooks

The notebooks render directly on GitHub with their charts, so you can read them without running anything.

To run them yourself, use Python 3.11 or newer:

```
pip install -r requirements.txt
jupyter notebook
```

Open a notebook from inside its own folder so it finds its data. The insurance, life expectancy and census projects include their data and run as they are. The Stack Overflow and Yelp datasets aren't stored here; each of those folders has a README that says where to get them.
